![]

Introduction
============

#### Background

This is a report for the first project of the [Reproducible Research
Course](https://www.coursera.org/) on
[Coursera](https://www.coursera.org/learn/reproducible-research/home/welcome).
The full activity description can be found
[here](https://www.coursera.org/learn/reproducible-research/peer/gYyPt/course-project-1)

#### Assignment

This assignment will be described in multiple parts. You will need to
write a report that answers the questions detailed below. Ultimately,
you will need to complete the entire assignment in a single R markdown
document that can be processed by knitr and be transformed into an HTML
file.

Throughout your report make sure you always include the code that you
used to generate the output you present. When writing code chunks in the
R markdown document, always use echo = TRUE so that someone else will be
able to read the code. **This assignment will be evaluated via peer
assessment so it is essential that your peer evaluators be able to
review the code for your analysis.**

For the plotting aspects of this assignment, feel free to use any
plotting system in R (i.e., base, lattice, ggplot2)

Fork/clone the [GitHub repository created for this
assignment](https://github.com/rdpeng/RepData_PeerAssessment1). You will
submit this assignment by pushing your completed files into your forked
repository on GitHub. The assignment submission will consist of the URL
to your GitHub repository and the SHA-1 commit ID for your repository
state.

------------------------------------------------------------------------

Body
====

In the section *Body* we will be answering the questions proposed by the
Professor. TO make the compreension easier, these questions will be
separated by headings and lists.

#### Loading and preprocessing the data

1.  Load the data

First we must unzip the data and load it using the read.csv function.

    unzip("./activity.zip") 
    rawdt <- read.csv("./activity.csv",stringsAsFactors = F)

1.  Process/transform the data (if necessary) into a format suitable for
    your analysis

<!-- -->

    str(rawdt)

    ## 'data.frame':    17568 obs. of  3 variables:
    ##  $ steps   : int  NA NA NA NA NA NA NA NA NA NA ...
    ##  $ date    : chr  "2012-10-01" "2012-10-01" "2012-10-01" "2012-10-01" ...
    ##  $ interval: int  0 5 10 15 20 25 30 35 40 45 ...

    navalues <- sum(is.na(rawdt$steps))
    napercentage <- round(mean(is.na(rawdt$steps))*100,2)

Upon taking a look at the data we notice that there are 2304 missing
values, which corresponds to 13.11% of the data, and that *Date* values
are not classified as so.

    dt <- rawdt
    dt$date <- as.Date(dt$date)
    str(dt)

    ## 'data.frame':    17568 obs. of  3 variables:
    ##  $ steps   : int  NA NA NA NA NA NA NA NA NA NA ...
    ##  $ date    : Date, format: "2012-10-01" "2012-10-01" ...
    ##  $ interval: int  0 5 10 15 20 25 30 35 40 45 ...

#### What is mean total number of steps taken per day?

For this part of the assignment, you can ignore the missing values in
the dataset.

1.  Calculate the total number of steps taken per day

<!-- -->

    bydate <- aggregate(dt$steps, by = list(dt$date), sum)
    colnames(bydate) <- c("Date","Step")
    mean(bydate$Step, na.rm = T)

    ## [1] 10766.19

1.  Make a histogram of the total number of steps taken each day

<!-- -->

    library(ggplot2)
    ggplot(dt, aes(date,steps)) + 
            geom_bar(stat = "identity") +
            labs(x = "Days", y = "Steps taken", title = "Numbers of steps taken each day")

    ## Warning: Removed 2304 rows containing missing values (position_stack).

![](PA1_template_files/figure-markdown_strict/unnamed-chunk-5-1.png)

1.  Calculate and report the mean and median of the total number of
    steps taken per day

In this case, we will disconsider the days with *NA* values

    bydate.nona <- na.exclude(bydate)
    dtmean <- mean(bydate.nona[,2])
    dtmedian <- median(bydate.nona[,2])

So the mean of the total numbers of steps taken per day is
1.076618910^{4} and the median is 10765.

#### What is the average daily activity pattern?

1.  Make a time series plot (i.e. type = "l") of the 5-minute
    interval (x-axis) and the average number of steps taken, averaged
    across all days (y-axis)

<!-- -->

    dt.nona <- na.exclude(dt) #removing NA values
    byinterval <- with(dt.nona, aggregate(steps, by = list(interval), FUN = mean))
    colnames(byinterval) <-  c("Intervals","Average.Steps.Taken")
    ggplot(byinterval, aes(Intervals,Average.Steps.Taken)) + 
            geom_line() +
            labs(x = "Intervals", y = "Average Steps taken", title = "Average Steps taken in each interval")

![](PA1_template_files/figure-markdown_strict/unnamed-chunk-7-1.png)

1.  Which 5-minute interval, on average across all the days in the
    dataset, contains the maximum number of steps?

<!-- -->

    maxinterval <- byinterval[,1][which.max(byinterval[,2])]
    valuemaxinterval <- byinterval[,2][which.max(byinterval[,2])]

As we can see by the graph, the Interval that contains the highest
*Average steps taken* is 835 which contais 206.1698113 steps.

#### Imputing missing values

Note that there are a number of days/intervals where there are missing
values (coded as NA). The presence of missing days may introduce bias
into some calculations or summaries of the data.

1.  Calculate and report the total number of missing values in the
    dataset (i.e. the total number of rows with NAs)

As calculated before, the number of missing values (NAs) is 2304, which
accounts for 13.11% of the total data.

1.  Devise a strategy for filling in all of the missing values in
    the dataset. The strategy does not need to be sophisticated. For
    example, you could use the mean/median for that day, or the mean for
    that 5-minute interval, etc.

Strategy chosen: **We are going to replace the NA of a determined
interval by the average value of steps taken at that specific interval
in the whole data.**

    newdt <- dt
    for (i in seq(0, 2355, 5)) {
            newdt[which(is.na(newdt$steps) & newdt$interval == i),][,1] <- byinterval[byinterval$Intervals == i,][2]
    }

1.  Create a new dataset that is equal to the original dataset but with
    the missing data filled in.

Done on last item:

    head(newdt)

    ##       steps       date interval
    ## 1 1.7169811 2012-10-01        0
    ## 2 0.3396226 2012-10-01        5
    ## 3 0.1320755 2012-10-01       10
    ## 4 0.1509434 2012-10-01       15
    ## 5 0.0754717 2012-10-01       20
    ## 6 2.0943396 2012-10-01       25

    summary(newdt)

    ##      steps             date               interval     
    ##  Min.   :  0.00   Min.   :2012-10-01   Min.   :   0.0  
    ##  1st Qu.:  0.00   1st Qu.:2012-10-16   1st Qu.: 588.8  
    ##  Median :  0.00   Median :2012-10-31   Median :1177.5  
    ##  Mean   : 37.38   Mean   :2012-10-31   Mean   :1177.5  
    ##  3rd Qu.: 27.00   3rd Qu.:2012-11-15   3rd Qu.:1766.2  
    ##  Max.   :806.00   Max.   :2012-11-30   Max.   :2355.0

    sum(is.na(newdt))

    ## [1] 0

1.  Make a histogram of the total number of steps taken each day and
    Calculate and report the mean and median total number of steps taken
    per day. Do these values differ from the estimates from the first
    part of the assignment? What is the impact of imputing missing data
    on the estimates of the total daily number of steps?

###### Raw data with NA values

Histogram

    library(ggplot2)
    ggplot(dt, aes(date,steps)) + 
            geom_bar(stat = "identity") +
            labs(x = "Days", y = "Steps taken", title = "Numbers of steps taken each day")

    ## Warning: Removed 2304 rows containing missing values (position_stack).

![](PA1_template_files/figure-markdown_strict/unnamed-chunk-11-1.png)

Mean: 1.076618910^{4} Median: 10765.

###### New data without NA values

New Histogram

    library(ggplot2)
    ggplot(newdt, aes(date,steps)) + 
            geom_bar(stat = "identity") +
            labs(x = "Days", y = "Steps taken", title = "Numbers of steps taken each day with NA values replaced")

![](PA1_template_files/figure-markdown_strict/unnamed-chunk-12-1.png)

    newbydate <- aggregate(newdt$steps, by = list(newdt$date), sum)
    colnames(newbydate) <- c("Date","Step")
    newdtmean <- mean(newbydate[,2])
    newdtmedian <- median(newbydate[,2])

Mean: 1.076618910^{4} Median: 1.076618910^{4}.

Adding NA values influences in the histogram shown, but it does not
seems to have a significant change on the median and mean values.

#### Are there differences in activity patterns between weekdays and weekends?

For this part the weekdays() function may be of some help here. Use the
dataset with the filled-in missing values for this part.

1.  Create a new factor variable in the dataset with two levels â
    âweekdayâ and âweekendâ indicating whether a given date is a
    weekday or weekend day.

<!-- -->

    newdt$Weekend = strftime(dt$date,'%u')
    newdt$Weekend <- gsub("1|2|3|4|5","Weekday",newdt$Weekend)
    newdt$Weekend <- gsub("6|7","Weekend",newdt$Weekend)
    table(newdt$Weekend)

    ## 
    ## Weekday Weekend 
    ##   12960    4608

1.  Make a panel plot containing a time series plot (i.e. type = "l") of
    the 5-minute interval (x-axis) and the average number of steps
    taken, averaged across all weekday days or weekend days (y-axis).
    See the README file in the GitHub repository to see an example of
    what this plot should look like using simulated data.

<!-- -->

    finaldt <- aggregate(steps ~ Weekend + interval, data = newdt, FUN = 'mean')
    ggplot(finaldt, aes(interval,steps)) + 
            geom_line() +
            labs(x = "Intervals", y = "Average Steps taken", title = "Average Steps by Weekdays/Weekends") +
            facet_grid(Weekend ~ .)

![](PA1_template_files/figure-markdown_strict/unnamed-chunk-14-1.png)
