





<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="utf-8">
  <link rel="dns-prefetch" href="https://assets-cdn.github.com">
  <link rel="dns-prefetch" href="https://avatars0.githubusercontent.com">
  <link rel="dns-prefetch" href="https://avatars1.githubusercontent.com">
  <link rel="dns-prefetch" href="https://avatars2.githubusercontent.com">
  <link rel="dns-prefetch" href="https://avatars3.githubusercontent.com">
  <link rel="dns-prefetch" href="https://github-cloud.s3.amazonaws.com">
  <link rel="dns-prefetch" href="https://user-images.githubusercontent.com/">



  <link crossorigin="anonymous" href="https://assets-cdn.github.com/assets/frameworks-bedfc518345498ab3204d330c1727cde7e733526a09cd7df6867f6a231565091.css" integrity="sha256-vt/FGDRUmKsyBNMwwXJ83n5zNSagnNffaGf2ojFWUJE=" media="all" rel="stylesheet" />
  <link crossorigin="anonymous" href="https://assets-cdn.github.com/assets/github-8aa35c6c95ecb92a72b495f0f2caaafde4edfc5052a27619cc11137db76a384d.css" integrity="sha256-iqNcbJXsuSpytJXw8sqq/eTt/FBSonYZzBETfbdqOE0=" media="all" rel="stylesheet" />
  
  
  
  

  <meta name="viewport" content="width=device-width">
  
  <title>datasciencecoursera/PA1_template.md at master · dchen71/datasciencecoursera</title>
  <link rel="search" type="application/opensearchdescription+xml" href="/opensearch.xml" title="GitHub">
  <link rel="fluid-icon" href="https://github.com/fluidicon.png" title="GitHub">
  <meta property="fb:app_id" content="1401488693436528">

    
    <meta content="https://avatars3.githubusercontent.com/u/4143686?v=4&amp;s=400" property="og:image" /><meta content="GitHub" property="og:site_name" /><meta content="object" property="og:type" /><meta content="dchen71/datasciencecoursera" property="og:title" /><meta content="https://github.com/dchen71/datasciencecoursera" property="og:url" /><meta content="datasciencecoursera - Leek Datasharing" property="og:description" />

  <link rel="assets" href="https://assets-cdn.github.com/">
  <link rel="web-socket" href="wss://live.github.com/_sockets/VjI6MjA1Njc0MzM2OjQ0ZjNkYWVlMzE4YTBhYzQzZDUyNzVkZjhhMzI0MzdjN2RlYmNlMzJjYTIzNTljYmZjZDFmYmRhYzRlYzI1NjE=--feb2310891b83c63eedae9ab1ac426a063bf6936">
  <meta name="pjax-timeout" content="1000">
  <link rel="sudo-modal" href="/sessions/sudo_modal">
  <meta name="request-id" content="37B8:3DE7:23CF4C9:3D756CE:59B9FCE4" data-pjax-transient>
  

  <meta name="selected-link" value="repo_source" data-pjax-transient>

  <meta name="google-site-verification" content="KT5gs8h0wvaagLKAVWq8bbeNwnZZK1r1XQysX3xurLU">
<meta name="google-site-verification" content="ZzhVyEFwb7w3e0-uOTltm8Jsck2F5StVihD0exw2fsA">
    <meta name="google-analytics" content="UA-3769691-2">

<meta content="collector.githubapp.com" name="octolytics-host" /><meta content="github" name="octolytics-app-id" /><meta content="https://collector.githubapp.com/github-external/browser_event" name="octolytics-event-url" /><meta content="37B8:3DE7:23CF4C9:3D756CE:59B9FCE4" name="octolytics-dimension-request_id" /><meta content="iad" name="octolytics-dimension-region_edge" /><meta content="iad" name="octolytics-dimension-region_render" /><meta content="26240926" name="octolytics-actor-id" /><meta content="aniket-sarkar-tcs" name="octolytics-actor-login" /><meta content="361c3134f9ac39abcd1cb782f14b05a96ca9f0ceb0c56a632a3f44f059183427" name="octolytics-actor-hash" />
<meta content="/&lt;user-name&gt;/&lt;repo-name&gt;/blob/show" data-pjax-transient="true" name="analytics-location" />




  <meta class="js-ga-set" name="dimension1" content="Logged In">


  

      <meta name="hostname" content="github.com">
  <meta name="user-login" content="aniket-sarkar-tcs">

      <meta name="expected-hostname" content="github.com">
    <meta name="js-proxy-site-detection-payload" content="NDE3MWMwOGNjMGI0ZDEyMGYyNjk1Y2NiZGE0NDgyNDQ2Y2FkZmZjM2Q3NzEzOTlhN2M5ZmM0NmQ2ODY1NzZlNXx7InJlbW90ZV9hZGRyZXNzIjoiMjAyLjE0Mi42OS45NyIsInJlcXVlc3RfaWQiOiIzN0I4OjNERTc6MjNDRjRDOTozRDc1NkNFOjU5QjlGQ0U0IiwidGltZXN0YW1wIjoxNTA1MzYxMTI4LCJob3N0IjoiZ2l0aHViLmNvbSJ9">

    <meta name="enabled-features" content="UNIVERSE_BANNER">

  <meta name="html-safe-nonce" content="8ff7aa92046294e25085ef59f3a5e80391777ae3">

  <meta http-equiv="x-pjax-version" content="4b1a743e61662861281566902d1c74de">
  

      <link href="https://github.com/dchen71/datasciencecoursera/commits/master.atom" rel="alternate" title="Recent Commits to datasciencecoursera:master" type="application/atom+xml">

  <meta name="description" content="datasciencecoursera - Leek Datasharing">
  <meta name="go-import" content="github.com/dchen71/datasciencecoursera git https://github.com/dchen71/datasciencecoursera.git">

  <meta content="4143686" name="octolytics-dimension-user_id" /><meta content="dchen71" name="octolytics-dimension-user_login" /><meta content="27462223" name="octolytics-dimension-repository_id" /><meta content="dchen71/datasciencecoursera" name="octolytics-dimension-repository_nwo" /><meta content="true" name="octolytics-dimension-repository_public" /><meta content="false" name="octolytics-dimension-repository_is_fork" /><meta content="27462223" name="octolytics-dimension-repository_network_root_id" /><meta content="dchen71/datasciencecoursera" name="octolytics-dimension-repository_network_root_nwo" /><meta content="false" name="octolytics-dimension-repository_explore_github_marketplace_ci_cta_shown" />


    <link rel="canonical" href="https://github.com/dchen71/datasciencecoursera/blob/master/Reproducible%20Research/Project%201/PA1_template.md" data-pjax-transient>


  <meta name="browser-stats-url" content="https://api.github.com/_private/browser/stats">

  <meta name="browser-errors-url" content="https://api.github.com/_private/browser/errors">

  <link rel="mask-icon" href="https://assets-cdn.github.com/pinned-octocat.svg" color="#000000">
  <link rel="icon" type="image/x-icon" href="https://assets-cdn.github.com/favicon.ico">

<meta name="theme-color" content="#1e2327">


  <meta name="u2f-support" content="true">

  </head>

  <body class="logged-in env-production page-blob">
    

  <div class="position-relative js-header-wrapper ">
    <a href="#start-of-content" tabindex="1" class="bg-black text-white p-3 show-on-focus js-skip-to-content">Skip to content</a>
    <div id="js-pjax-loader-bar" class="pjax-loader-bar"><div class="progress"></div></div>

    
    
    



        
<header class="Header  f5" role="banner">
  <div class="d-flex px-3 flex-justify-between container-lg">
    <div class="d-flex flex-justify-between">
      <a class="header-logo-invertocat" href="https://github.com/" data-hotkey="g d" aria-label="Homepage" data-ga-click="Header, go to dashboard, icon:logo">
  <svg aria-hidden="true" class="octicon octicon-mark-github" height="32" version="1.1" viewBox="0 0 16 16" width="32"><path fill-rule="evenodd" d="M8 0C3.58 0 0 3.58 0 8c0 3.54 2.29 6.53 5.47 7.59.4.07.55-.17.55-.38 0-.19-.01-.82-.01-1.49-2.01.37-2.53-.49-2.69-.94-.09-.23-.48-.94-.82-1.13-.28-.15-.68-.52-.01-.53.63-.01 1.08.58 1.23.82.72 1.21 1.87.87 2.33.66.07-.52.28-.87.51-1.07-1.78-.2-3.64-.89-3.64-3.95 0-.87.31-1.59.82-2.15-.08-.2-.36-1.02.08-2.12 0 0 .67-.21 2.2.82.64-.18 1.32-.27 2-.27.68 0 1.36.09 2 .27 1.53-1.04 2.2-.82 2.2-.82.44 1.1.16 1.92.08 2.12.51.56.82 1.27.82 2.15 0 3.07-1.87 3.75-3.65 3.95.29.25.54.73.54 1.48 0 1.07-.01 1.93-.01 2.2 0 .21.15.46.55.38A8.013 8.013 0 0 0 16 8c0-4.42-3.58-8-8-8z"/></svg>
</a>


    </div>

    <div class="HeaderMenu d-flex flex-justify-between flex-auto">
      <div class="d-flex">
            <div class="">
              <div class="header-search scoped-search site-scoped-search js-site-search" role="search">
  <!-- '"` --><!-- </textarea></xmp> --></option></form><form accept-charset="UTF-8" action="/dchen71/datasciencecoursera/search" class="js-site-search-form" data-scoped-search-url="/dchen71/datasciencecoursera/search" data-unscoped-search-url="/search" method="get"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /></div>
    <label class="form-control header-search-wrapper js-chromeless-input-container">
        <a href="/dchen71/datasciencecoursera/blob/master/Reproducible%20Research/Project%201/PA1_template.md" class="header-search-scope no-underline">This repository</a>
      <input type="text"
        class="form-control header-search-input js-site-search-focus js-site-search-field is-clearable"
        data-hotkey="s"
        name="q"
        value=""
        placeholder="Search"
        aria-label="Search this repository"
        data-unscoped-placeholder="Search GitHub"
        data-scoped-placeholder="Search"
        autocapitalize="off">
        <input type="hidden" class="js-site-search-type-field" name="type" >
    </label>
</form></div>

            </div>

          <ul class="d-flex pl-2 flex-items-center text-bold list-style-none" role="navigation">
            <li>
              <a href="/pulls" aria-label="Pull requests you created" class="js-selected-navigation-item HeaderNavlink px-2" data-ga-click="Header, click, Nav menu - item:pulls context:user" data-hotkey="g p" data-selected-links="/pulls /pulls/assigned /pulls/mentioned /pulls">
                Pull requests
</a>            </li>
            <li>
              <a href="/issues" aria-label="Issues you created" class="js-selected-navigation-item HeaderNavlink px-2" data-ga-click="Header, click, Nav menu - item:issues context:user" data-hotkey="g i" data-selected-links="/issues /issues/assigned /issues/mentioned /issues">
                Issues
</a>            </li>
                <li>
                  <a href="/marketplace" class="js-selected-navigation-item HeaderNavlink px-2" data-ga-click="Header, click, Nav menu - item:marketplace context:user" data-selected-links=" /marketplace">
                    Marketplace
</a>                </li>
            <li>
              <a href="/explore" class="js-selected-navigation-item HeaderNavlink px-2" data-ga-click="Header, click, Nav menu - item:explore" data-selected-links="/explore /trending /trending/developers /integrations /integrations/feature/code /integrations/feature/collaborate /integrations/feature/ship showcases showcases_search showcases_landing /explore">
                Explore
</a>            </li>
          </ul>
      </div>

      <div class="d-flex">
        
<ul class="user-nav d-flex flex-items-center list-style-none" id="user-links">
  <li class="dropdown js-menu-container js-header-notifications">
    <span class="d-inline-block  px-2">
      

    </span>
  </li>

  <li class="dropdown js-menu-container">
    <details class="dropdown-details js-dropdown-details d-flex px-2 flex-items-center">
      <summary class="HeaderNavlink"
         aria-label="Create new…"
         data-ga-click="Header, create new, icon:add">
        <svg aria-hidden="true" class="octicon octicon-plus float-left mr-1 mt-1" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M12 9H7v5H5V9H0V7h5V2h2v5h5z"/></svg>
        <span class="dropdown-caret mt-1"></span>
      </summary>

      <ul class="dropdown-menu dropdown-menu-sw">
        
<a class="dropdown-item" href="/new" data-ga-click="Header, create new repository">
  New repository
</a>

  <a class="dropdown-item" href="/new/import" data-ga-click="Header, import a repository">
    Import repository
  </a>

<a class="dropdown-item" href="https://gist.github.com/" data-ga-click="Header, create new gist">
  New gist
</a>

  <a class="dropdown-item" href="/organizations/new" data-ga-click="Header, create new organization">
    New organization
  </a>



  <div class="dropdown-divider"></div>
  <div class="dropdown-header">
    <span title="dchen71/datasciencecoursera">This repository</span>
  </div>
    <a class="dropdown-item" href="/dchen71/datasciencecoursera/issues/new" data-ga-click="Header, create new issue">
      New issue
    </a>

      </ul>
    </details>
  </li>

  <li class="dropdown js-menu-container">

    <details class="dropdown-details js-dropdown-details d-flex pl-2 flex-items-center">
      <summary class="HeaderNavlink name mt-1"
        aria-label="View profile and more"
        data-ga-click="Header, show menu, icon:avatar">
        <img alt="@aniket-sarkar-tcs" class="avatar float-left mr-1" src="https://avatars0.githubusercontent.com/u/26240926?v=4&amp;s=40" height="20" width="20">
        <span class="dropdown-caret"></span>
      </summary>

      <ul class="dropdown-menu dropdown-menu-sw">
        <li class="dropdown-header header-nav-current-user css-truncate">
          Signed in as <strong class="css-truncate-target">aniket-sarkar-tcs</strong>
        </li>

        <li class="dropdown-divider"></li>

        <li><a class="dropdown-item" href="/aniket-sarkar-tcs" data-ga-click="Header, go to profile, text:your profile">
          Your profile
        </a></li>
        <li><a class="dropdown-item" href="/aniket-sarkar-tcs?tab=stars" data-ga-click="Header, go to starred repos, text:your stars">
          Your stars
        </a></li>
          <li><a class="dropdown-item" href="https://gist.github.com/" data-ga-click="Header, your gists, text:your gists">Your Gists</a></li>

        <li class="dropdown-divider"></li>

        <li><a class="dropdown-item" href="https://help.github.com" data-ga-click="Header, go to help, text:help">
          Help
        </a></li>

        <li><a class="dropdown-item" href="/settings/profile" data-ga-click="Header, go to settings, icon:settings">
          Settings
        </a></li>

        <li><!-- '"` --><!-- </textarea></xmp> --></option></form><form accept-charset="UTF-8" action="/logout" class="logout-form" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="7iui4MLuXyfnHlNHAJEfyr2CLq77siFQbknEyVd1+h9hwZmyQU7Qkq5OoIYeXE2ZjrVydBGBK7E1tANhRhGy/Q==" /></div>
          <button type="submit" class="dropdown-item dropdown-signout" data-ga-click="Header, sign out, icon:logout">
            Sign out
          </button>
        </form></li>
      </ul>
    </details>
  </li>
</ul>


        <!-- '"` --><!-- </textarea></xmp> --></option></form><form accept-charset="UTF-8" action="/logout" class="sr-only right-0" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="PBci9AepTdKysQIVFy3k2dCXD/xuvGuQ5mZOvlDLNDuz/RmmhAnCZ/vh8dQJ4LaK46BTJoSPYXG9m4kWQa982Q==" /></div>
          <button type="submit" class="dropdown-item dropdown-signout" data-ga-click="Header, sign out, icon:logout">
            Sign out
          </button>
</form>      </div>
    </div>
  </div>
</header>


      

  </div>

  <div id="start-of-content" class="show-on-focus"></div>

    <div id="js-flash-container">
</div>



  <div role="main">
        <div itemscope itemtype="http://schema.org/SoftwareSourceCode">
    <div id="js-repo-pjax-container" data-pjax-container>
      





    <div class="pagehead repohead instapaper_ignore readability-menu experiment-repo-nav">
      <div class="container repohead-details-container">

        <ul class="pagehead-actions">
  <li>
        <!-- '"` --><!-- </textarea></xmp> --></option></form><form accept-charset="UTF-8" action="/notifications/subscribe" class="js-social-container" data-autosubmit="true" data-remote="true" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="jecOXebcVFuxOMIvJpTo6ieslTNQms7/P3ou3/m/ZZBe12yC0OpNjz0TUgFlEAZm3zsexU9NPRLQOWOV6fNORQ==" /></div>      <input class="form-control" id="repository_id" name="repository_id" type="hidden" value="27462223" />

        <div class="select-menu js-menu-container js-select-menu">
          <a href="/dchen71/datasciencecoursera/subscription"
            class="btn btn-sm btn-with-count select-menu-button js-menu-target"
            role="button"
            aria-haspopup="true"
            aria-expanded="false"
            aria-label="Toggle repository notifications menu"
            data-ga-click="Repository, click Watch settings, action:blob#show">
            <span class="js-select-button">
                <svg aria-hidden="true" class="octicon octicon-eye" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M8.06 2C3 2 0 8 0 8s3 6 8.06 6C13 14 16 8 16 8s-3-6-7.94-6zM8 12c-2.2 0-4-1.78-4-4 0-2.2 1.8-4 4-4 2.22 0 4 1.8 4 4 0 2.22-1.78 4-4 4zm2-4c0 1.11-.89 2-2 2-1.11 0-2-.89-2-2 0-1.11.89-2 2-2 1.11 0 2 .89 2 2z"/></svg>
                Watch
            </span>
          </a>
            <a class="social-count js-social-count"
              href="/dchen71/datasciencecoursera/watchers"
              aria-label="2 users are watching this repository">
              2
            </a>

        <div class="select-menu-modal-holder">
          <div class="select-menu-modal subscription-menu-modal js-menu-content">
            <div class="select-menu-header js-navigation-enable" tabindex="-1">
              <svg aria-label="Close" class="octicon octicon-x js-menu-close" height="16" role="img" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M7.48 8l3.75 3.75-1.48 1.48L6 9.48l-3.75 3.75-1.48-1.48L4.52 8 .77 4.25l1.48-1.48L6 6.52l3.75-3.75 1.48 1.48z"/></svg>
              <span class="select-menu-title">Notifications</span>
            </div>

              <div class="select-menu-list js-navigation-container" role="menu">

                <div class="select-menu-item js-navigation-item selected" role="menuitem" tabindex="0">
                  <svg aria-hidden="true" class="octicon octicon-check select-menu-item-icon" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5z"/></svg>
                  <div class="select-menu-item-text">
                    <input checked="checked" id="do_included" name="do" type="radio" value="included" />
                    <span class="select-menu-item-heading">Not watching</span>
                    <span class="description">Be notified when participating or @mentioned.</span>
                    <span class="js-select-button-text hidden-select-button-text">
                      <svg aria-hidden="true" class="octicon octicon-eye" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M8.06 2C3 2 0 8 0 8s3 6 8.06 6C13 14 16 8 16 8s-3-6-7.94-6zM8 12c-2.2 0-4-1.78-4-4 0-2.2 1.8-4 4-4 2.22 0 4 1.8 4 4 0 2.22-1.78 4-4 4zm2-4c0 1.11-.89 2-2 2-1.11 0-2-.89-2-2 0-1.11.89-2 2-2 1.11 0 2 .89 2 2z"/></svg>
                      Watch
                    </span>
                  </div>
                </div>

                <div class="select-menu-item js-navigation-item " role="menuitem" tabindex="0">
                  <svg aria-hidden="true" class="octicon octicon-check select-menu-item-icon" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5z"/></svg>
                  <div class="select-menu-item-text">
                    <input id="do_subscribed" name="do" type="radio" value="subscribed" />
                    <span class="select-menu-item-heading">Watching</span>
                    <span class="description">Be notified of all conversations.</span>
                    <span class="js-select-button-text hidden-select-button-text">
                      <svg aria-hidden="true" class="octicon octicon-eye" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M8.06 2C3 2 0 8 0 8s3 6 8.06 6C13 14 16 8 16 8s-3-6-7.94-6zM8 12c-2.2 0-4-1.78-4-4 0-2.2 1.8-4 4-4 2.22 0 4 1.8 4 4 0 2.22-1.78 4-4 4zm2-4c0 1.11-.89 2-2 2-1.11 0-2-.89-2-2 0-1.11.89-2 2-2 1.11 0 2 .89 2 2z"/></svg>
                        Unwatch
                    </span>
                  </div>
                </div>

                <div class="select-menu-item js-navigation-item " role="menuitem" tabindex="0">
                  <svg aria-hidden="true" class="octicon octicon-check select-menu-item-icon" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5z"/></svg>
                  <div class="select-menu-item-text">
                    <input id="do_ignore" name="do" type="radio" value="ignore" />
                    <span class="select-menu-item-heading">Ignoring</span>
                    <span class="description">Never be notified.</span>
                    <span class="js-select-button-text hidden-select-button-text">
                      <svg aria-hidden="true" class="octicon octicon-mute" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M8 2.81v10.38c0 .67-.81 1-1.28.53L3 10H1c-.55 0-1-.45-1-1V7c0-.55.45-1 1-1h2l3.72-3.72C7.19 1.81 8 2.14 8 2.81zm7.53 3.22l-1.06-1.06-1.97 1.97-1.97-1.97-1.06 1.06L11.44 8 9.47 9.97l1.06 1.06 1.97-1.97 1.97 1.97 1.06-1.06L13.56 8l1.97-1.97z"/></svg>
                        Stop ignoring
                    </span>
                  </div>
                </div>

              </div>

            </div>
          </div>
        </div>
</form>
  </li>

  <li>
    
  <div class="js-toggler-container js-social-container starring-container ">
    <!-- '"` --><!-- </textarea></xmp> --></option></form><form accept-charset="UTF-8" action="/dchen71/datasciencecoursera/unstar" class="starred" data-remote="true" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="CMoo/IYFKPt+O4BArEpupkp4BWOI+ezAugoKLctEifnUy0lnxvNU/1bcShYj5d3jt/QF21XssN8TXr6SEUuykw==" /></div>
      <button
        type="submit"
        class="btn btn-sm btn-with-count js-toggler-target"
        aria-label="Unstar this repository" title="Unstar dchen71/datasciencecoursera"
        data-ga-click="Repository, click unstar button, action:blob#show; text:Unstar">
        <svg aria-hidden="true" class="octicon octicon-star" height="16" version="1.1" viewBox="0 0 14 16" width="14"><path fill-rule="evenodd" d="M14 6l-4.9-.64L7 1 4.9 5.36 0 6l3.6 3.26L2.67 14 7 11.67 11.33 14l-.93-4.74z"/></svg>
        Unstar
      </button>
        <a class="social-count js-social-count" href="/dchen71/datasciencecoursera/stargazers"
           aria-label="0 users starred this repository">
          0
        </a>
</form>
    <!-- '"` --><!-- </textarea></xmp> --></option></form><form accept-charset="UTF-8" action="/dchen71/datasciencecoursera/star" class="unstarred" data-remote="true" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="27K0v5ipWyM6wgId8yMmVe2IoedAhI0D3mEbuIK82X6RIgCmqarMWfO/ZVCB2qHeZQP7bQnPWge+maoe5RBYJg==" /></div>
      <button
        type="submit"
        class="btn btn-sm btn-with-count js-toggler-target"
        aria-label="Star this repository" title="Star dchen71/datasciencecoursera"
        data-ga-click="Repository, click star button, action:blob#show; text:Star">
        <svg aria-hidden="true" class="octicon octicon-star" height="16" version="1.1" viewBox="0 0 14 16" width="14"><path fill-rule="evenodd" d="M14 6l-4.9-.64L7 1 4.9 5.36 0 6l3.6 3.26L2.67 14 7 11.67 11.33 14l-.93-4.74z"/></svg>
        Star
      </button>
        <a class="social-count js-social-count" href="/dchen71/datasciencecoursera/stargazers"
           aria-label="0 users starred this repository">
          0
        </a>
</form>  </div>

  </li>

  <li>
          <!-- '"` --><!-- </textarea></xmp> --></option></form><form accept-charset="UTF-8" action="/dchen71/datasciencecoursera/fork" class="btn-with-count" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="QUqyUOVQo0nYurRSE9EiNk1pQCxMQisc3ZdRMdLrCOA1H3RIdqUw/6U9vIOO5ZqvO+RJGudfwySIzN24qa5HZw==" /></div>
            <button
                type="submit"
                class="btn btn-sm btn-with-count"
                data-ga-click="Repository, show fork modal, action:blob#show; text:Fork"
                title="Fork your own copy of dchen71/datasciencecoursera to your account"
                aria-label="Fork your own copy of dchen71/datasciencecoursera to your account">
              <svg aria-hidden="true" class="octicon octicon-repo-forked" height="16" version="1.1" viewBox="0 0 10 16" width="10"><path fill-rule="evenodd" d="M8 1a1.993 1.993 0 0 0-1 3.72V6L5 8 3 6V4.72A1.993 1.993 0 0 0 2 1a1.993 1.993 0 0 0-1 3.72V6.5l3 3v1.78A1.993 1.993 0 0 0 5 15a1.993 1.993 0 0 0 1-3.72V9.5l3-3V4.72A1.993 1.993 0 0 0 8 1zM2 4.2C1.34 4.2.8 3.65.8 3c0-.65.55-1.2 1.2-1.2.65 0 1.2.55 1.2 1.2 0 .65-.55 1.2-1.2 1.2zm3 10c-.66 0-1.2-.55-1.2-1.2 0-.65.55-1.2 1.2-1.2.65 0 1.2.55 1.2 1.2 0 .65-.55 1.2-1.2 1.2zm3-10c-.66 0-1.2-.55-1.2-1.2 0-.65.55-1.2 1.2-1.2.65 0 1.2.55 1.2 1.2 0 .65-.55 1.2-1.2 1.2z"/></svg>
              Fork
            </button>
</form>
    <a href="/dchen71/datasciencecoursera/network" class="social-count"
       aria-label="11 users forked this repository">
      11
    </a>
  </li>
</ul>

        <h1 class="public ">
  <svg aria-hidden="true" class="octicon octicon-repo" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M4 9H3V8h1v1zm0-3H3v1h1V6zm0-2H3v1h1V4zm0-2H3v1h1V2zm8-1v12c0 .55-.45 1-1 1H6v2l-1.5-1.5L3 16v-2H1c-.55 0-1-.45-1-1V1c0-.55.45-1 1-1h10c.55 0 1 .45 1 1zm-1 10H1v2h2v-1h3v1h5v-2zm0-10H2v9h9V1z"/></svg>
  <span class="author" itemprop="author"><a href="/dchen71" class="url fn" rel="author">dchen71</a></span><!--
--><span class="path-divider">/</span><!--
--><strong itemprop="name"><a href="/dchen71/datasciencecoursera" data-pjax="#js-repo-pjax-container">datasciencecoursera</a></strong>

</h1>

      </div>
      <div class="container">
        
<nav class="reponav js-repo-nav js-sidenav-container-pjax"
     itemscope
     itemtype="http://schema.org/BreadcrumbList"
     role="navigation"
     data-pjax="#js-repo-pjax-container">

  <span itemscope itemtype="http://schema.org/ListItem" itemprop="itemListElement">
    <a href="/dchen71/datasciencecoursera" class="js-selected-navigation-item selected reponav-item" data-hotkey="g c" data-selected-links="repo_source repo_downloads repo_commits repo_releases repo_tags repo_branches /dchen71/datasciencecoursera" itemprop="url">
      <svg aria-hidden="true" class="octicon octicon-code" height="16" version="1.1" viewBox="0 0 14 16" width="14"><path fill-rule="evenodd" d="M9.5 3L8 4.5 11.5 8 8 11.5 9.5 13 14 8 9.5 3zm-5 0L0 8l4.5 5L6 11.5 2.5 8 6 4.5 4.5 3z"/></svg>
      <span itemprop="name">Code</span>
      <meta itemprop="position" content="1">
</a>  </span>

    <span itemscope itemtype="http://schema.org/ListItem" itemprop="itemListElement">
      <a href="/dchen71/datasciencecoursera/issues" class="js-selected-navigation-item reponav-item" data-hotkey="g i" data-selected-links="repo_issues repo_labels repo_milestones /dchen71/datasciencecoursera/issues" itemprop="url">
        <svg aria-hidden="true" class="octicon octicon-issue-opened" height="16" version="1.1" viewBox="0 0 14 16" width="14"><path fill-rule="evenodd" d="M7 2.3c3.14 0 5.7 2.56 5.7 5.7s-2.56 5.7-5.7 5.7A5.71 5.71 0 0 1 1.3 8c0-3.14 2.56-5.7 5.7-5.7zM7 1C3.14 1 0 4.14 0 8s3.14 7 7 7 7-3.14 7-7-3.14-7-7-7zm1 3H6v5h2V4zm0 6H6v2h2v-2z"/></svg>
        <span itemprop="name">Issues</span>
        <span class="Counter">0</span>
        <meta itemprop="position" content="2">
</a>    </span>

  <span itemscope itemtype="http://schema.org/ListItem" itemprop="itemListElement">
    <a href="/dchen71/datasciencecoursera/pulls" class="js-selected-navigation-item reponav-item" data-hotkey="g p" data-selected-links="repo_pulls /dchen71/datasciencecoursera/pulls" itemprop="url">
      <svg aria-hidden="true" class="octicon octicon-git-pull-request" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M11 11.28V5c-.03-.78-.34-1.47-.94-2.06C9.46 2.35 8.78 2.03 8 2H7V0L4 3l3 3V4h1c.27.02.48.11.69.31.21.2.3.42.31.69v6.28A1.993 1.993 0 0 0 10 15a1.993 1.993 0 0 0 1-3.72zm-1 2.92c-.66 0-1.2-.55-1.2-1.2 0-.65.55-1.2 1.2-1.2.65 0 1.2.55 1.2 1.2 0 .65-.55 1.2-1.2 1.2zM4 3c0-1.11-.89-2-2-2a1.993 1.993 0 0 0-1 3.72v6.56A1.993 1.993 0 0 0 2 15a1.993 1.993 0 0 0 1-3.72V4.72c.59-.34 1-.98 1-1.72zm-.8 10c0 .66-.55 1.2-1.2 1.2-.65 0-1.2-.55-1.2-1.2 0-.65.55-1.2 1.2-1.2.65 0 1.2.55 1.2 1.2zM2 4.2C1.34 4.2.8 3.65.8 3c0-.65.55-1.2 1.2-1.2.65 0 1.2.55 1.2 1.2 0 .65-.55 1.2-1.2 1.2z"/></svg>
      <span itemprop="name">Pull requests</span>
      <span class="Counter">0</span>
      <meta itemprop="position" content="3">
</a>  </span>

    <a href="/dchen71/datasciencecoursera/projects" class="js-selected-navigation-item reponav-item" data-selected-links="repo_projects new_repo_project repo_project /dchen71/datasciencecoursera/projects">
      <svg aria-hidden="true" class="octicon octicon-project" height="16" version="1.1" viewBox="0 0 15 16" width="15"><path fill-rule="evenodd" d="M10 12h3V2h-3v10zm-4-2h3V2H6v8zm-4 4h3V2H2v12zm-1 1h13V1H1v14zM14 0H1a1 1 0 0 0-1 1v14a1 1 0 0 0 1 1h13a1 1 0 0 0 1-1V1a1 1 0 0 0-1-1z"/></svg>
      Projects
      <span class="Counter" >0</span>
</a>
    <a href="/dchen71/datasciencecoursera/wiki" class="js-selected-navigation-item reponav-item" data-hotkey="g w" data-selected-links="repo_wiki /dchen71/datasciencecoursera/wiki">
      <svg aria-hidden="true" class="octicon octicon-book" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M3 5h4v1H3V5zm0 3h4V7H3v1zm0 2h4V9H3v1zm11-5h-4v1h4V5zm0 2h-4v1h4V7zm0 2h-4v1h4V9zm2-6v9c0 .55-.45 1-1 1H9.5l-1 1-1-1H2c-.55 0-1-.45-1-1V3c0-.55.45-1 1-1h5.5l1 1 1-1H15c.55 0 1 .45 1 1zm-8 .5L7.5 3H2v9h6V3.5zm7-.5H9.5l-.5.5V12h6V3z"/></svg>
      Wiki
</a>

    <div class="reponav-dropdown js-menu-container">
      <button type="button" class="btn-link reponav-item reponav-dropdown js-menu-target " data-no-toggle aria-expanded="false" aria-haspopup="true">
        Insights
        <svg aria-hidden="true" class="octicon octicon-triangle-down v-align-middle text-gray" height="11" version="1.1" viewBox="0 0 12 16" width="8"><path fill-rule="evenodd" d="M0 5l6 6 6-6z"/></svg>
      </button>
      <div class="dropdown-menu-content js-menu-content">
        <div class="dropdown-menu dropdown-menu-sw">
          <a class="dropdown-item" href="/dchen71/datasciencecoursera/pulse" data-skip-pjax>
            <svg aria-hidden="true" class="octicon octicon-pulse" height="16" version="1.1" viewBox="0 0 14 16" width="14"><path fill-rule="evenodd" d="M11.5 8L8.8 5.4 6.6 8.5 5.5 1.6 2.38 8H0v2h3.6l.9-1.8.9 5.4L9 8.5l1.6 1.5H14V8z"/></svg>
            Pulse
          </a>
          <a class="dropdown-item" href="/dchen71/datasciencecoursera/graphs" data-skip-pjax>
            <svg aria-hidden="true" class="octicon octicon-graph" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M16 14v1H0V0h1v14h15zM5 13H3V8h2v5zm4 0H7V3h2v10zm4 0h-2V6h2v7z"/></svg>
            Graphs
          </a>
        </div>
      </div>
    </div>
</nav>

      </div>
    </div>

<div class="container new-discussion-timeline experiment-repo-nav">
  <div class="repository-content">

    
  <a href="/dchen71/datasciencecoursera/blob/57a2cce507850965661ddbd2a61c7c64a989e5c6/Reproducible%20Research/Project%201/PA1_template.md" class="d-none js-permalink-shortcut" data-hotkey="y">Permalink</a>

  <!-- blob contrib key: blob_contributors:v21:6d5973fbcd841018394d518634932549 -->

  <div class="file-navigation js-zeroclipboard-container">
    
<div class="select-menu branch-select-menu js-menu-container js-select-menu float-left">
  <button class=" btn btn-sm select-menu-button js-menu-target css-truncate" data-hotkey="w"
    
    type="button" aria-label="Switch branches or tags" aria-expanded="false" aria-haspopup="true">
      <i>Branch:</i>
      <span class="js-select-button css-truncate-target">master</span>
  </button>

  <div class="select-menu-modal-holder js-menu-content js-navigation-container" data-pjax>

    <div class="select-menu-modal">
      <div class="select-menu-header">
        <svg aria-label="Close" class="octicon octicon-x js-menu-close" height="16" role="img" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M7.48 8l3.75 3.75-1.48 1.48L6 9.48l-3.75 3.75-1.48-1.48L4.52 8 .77 4.25l1.48-1.48L6 6.52l3.75-3.75 1.48 1.48z"/></svg>
        <span class="select-menu-title">Switch branches/tags</span>
      </div>

      <div class="select-menu-filters">
        <div class="select-menu-text-filter">
          <input type="text" aria-label="Filter branches/tags" id="context-commitish-filter-field" class="form-control js-filterable-field js-navigation-enable" placeholder="Filter branches/tags">
        </div>
        <div class="select-menu-tabs">
          <ul>
            <li class="select-menu-tab">
              <a href="#" data-tab-filter="branches" data-filter-placeholder="Filter branches/tags" class="js-select-menu-tab" role="tab">Branches</a>
            </li>
            <li class="select-menu-tab">
              <a href="#" data-tab-filter="tags" data-filter-placeholder="Find a tag…" class="js-select-menu-tab" role="tab">Tags</a>
            </li>
          </ul>
        </div>
      </div>

      <div class="select-menu-list select-menu-tab-bucket js-select-menu-tab-bucket" data-tab-filter="branches" role="menu">

        <div data-filterable-for="context-commitish-filter-field" data-filterable-type="substring">


            <a class="select-menu-item js-navigation-item js-navigation-open "
               href="/dchen71/datasciencecoursera/blob/gh-pages/Reproducible%20Research/Project%201/PA1_template.md"
               data-name="gh-pages"
               data-skip-pjax="true"
               rel="nofollow">
              <svg aria-hidden="true" class="octicon octicon-check select-menu-item-icon" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5z"/></svg>
              <span class="select-menu-item-text css-truncate-target js-select-menu-filter-text">
                gh-pages
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open selected"
               href="/dchen71/datasciencecoursera/blob/master/Reproducible%20Research/Project%201/PA1_template.md"
               data-name="master"
               data-skip-pjax="true"
               rel="nofollow">
              <svg aria-hidden="true" class="octicon octicon-check select-menu-item-icon" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5z"/></svg>
              <span class="select-menu-item-text css-truncate-target js-select-menu-filter-text">
                master
              </span>
            </a>
        </div>

          <div class="select-menu-no-results">Nothing to show</div>
      </div>

      <div class="select-menu-list select-menu-tab-bucket js-select-menu-tab-bucket" data-tab-filter="tags">
        <div data-filterable-for="context-commitish-filter-field" data-filterable-type="substring">


        </div>

        <div class="select-menu-no-results">Nothing to show</div>
      </div>

    </div>
  </div>
</div>

    <div class="BtnGroup float-right">
      <a href="/dchen71/datasciencecoursera/find/master"
            class="js-pjax-capture-input btn btn-sm BtnGroup-item"
            data-pjax
            data-hotkey="t">
        Find file
      </a>
      <button aria-label="Copy file path to clipboard" class="js-zeroclipboard btn btn-sm BtnGroup-item tooltipped tooltipped-s" data-copied-hint="Copied!" type="button">Copy path</button>
    </div>
    <div class="breadcrumb js-zeroclipboard-target">
      <span class="repo-root js-repo-root"><span class="js-path-segment"><a href="/dchen71/datasciencecoursera"><span>datasciencecoursera</span></a></span></span><span class="separator">/</span><span class="js-path-segment"><a href="/dchen71/datasciencecoursera/tree/master/Reproducible%20Research"><span>Reproducible Research</span></a></span><span class="separator">/</span><span class="js-path-segment"><a href="/dchen71/datasciencecoursera/tree/master/Reproducible%20Research/Project%201"><span>Project 1</span></a></span><span class="separator">/</span><strong class="final-path">PA1_template.md</strong>
    </div>
  </div>


  
  <div class="commit-tease">
      <span class="float-right">
        <a class="commit-tease-sha" href="/dchen71/datasciencecoursera/commit/8b52078fdc7fc630769c897d666bc67cbdbfa077" data-pjax>
          8b52078
        </a>
        <relative-time datetime="2015-06-17T00:13:10Z">Jun 17, 2015</relative-time>
      </span>
      <div>
        <img alt="@dchen71" class="avatar" height="20" src="https://avatars3.githubusercontent.com/u/4143686?v=4&amp;s=40" width="20" />
        <a href="/dchen71" class="user-mention" rel="author">dchen71</a>
          <a href="/dchen71/datasciencecoursera/commit/8b52078fdc7fc630769c897d666bc67cbdbfa077" class="message" data-pjax="true" title="changed directories">changed directories</a>
      </div>

    <div class="commit-tease-contributors">
      <button type="button" class="btn-link muted-link contributors-toggle" data-facebox="#blob_contributors_box">
        <strong>1</strong>
         contributor
      </button>
      
    </div>

    <div id="blob_contributors_box" style="display:none">
      <h2 class="facebox-header" data-facebox-id="facebox-header">Users who have contributed to this file</h2>
      <ul class="facebox-user-list" data-facebox-id="facebox-description">
          <li class="facebox-user-list-item">
            <img alt="@dchen71" height="24" src="https://avatars1.githubusercontent.com/u/4143686?v=4&amp;s=48" width="24" />
            <a href="/dchen71">dchen71</a>
          </li>
      </ul>
    </div>
  </div>


  <div class="file">
    <div class="file-header">
  <div class="file-actions">

    <div class="BtnGroup">
      <a href="/dchen71/datasciencecoursera/raw/master/Reproducible%20Research/Project%201/PA1_template.md" class="btn btn-sm BtnGroup-item" id="raw-url">Raw</a>
        <a href="/dchen71/datasciencecoursera/blame/master/Reproducible%20Research/Project%201/PA1_template.md" class="btn btn-sm js-update-url-with-hash BtnGroup-item" data-hotkey="b">Blame</a>
      <a href="/dchen71/datasciencecoursera/commits/master/Reproducible%20Research/Project%201/PA1_template.md" class="btn btn-sm BtnGroup-item" rel="nofollow">History</a>
    </div>

        <a class="btn-octicon tooltipped tooltipped-nw"
           href="github-windows://openRepo/https://github.com/dchen71/datasciencecoursera?branch=master&amp;filepath=Reproducible%20Research%2FProject%201%2FPA1_template.md"
           aria-label="Open this file in GitHub Desktop"
           data-ga-click="Repository, open with desktop, type:windows">
            <svg aria-hidden="true" class="octicon octicon-device-desktop" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M15 2H1c-.55 0-1 .45-1 1v9c0 .55.45 1 1 1h5.34c-.25.61-.86 1.39-2.34 2h8c-1.48-.61-2.09-1.39-2.34-2H15c.55 0 1-.45 1-1V3c0-.55-.45-1-1-1zm0 9H1V3h14v8z"/></svg>
        </a>

        <!-- '"` --><!-- </textarea></xmp> --></option></form><form accept-charset="UTF-8" action="/dchen71/datasciencecoursera/edit/master/Reproducible%20Research/Project%201/PA1_template.md" class="inline-form js-update-url-with-hash" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="slLBQJ1tTcHIiWw3Jhg4tDwEDz/KlLmQLtqb1c1OBhuwG7zok+97xewjwFENaMmvEvZeVEGO+LMJXMs2v457FA==" /></div>
          <button class="btn-octicon tooltipped tooltipped-nw" type="submit"
            aria-label="Fork this project and edit the file" data-hotkey="e" data-disable-with>
            <svg aria-hidden="true" class="octicon octicon-pencil" height="16" version="1.1" viewBox="0 0 14 16" width="14"><path fill-rule="evenodd" d="M0 12v3h3l8-8-3-3-8 8zm3 2H1v-2h1v1h1v1zm10.3-9.3L12 6 9 3l1.3-1.3a.996.996 0 0 1 1.41 0l1.59 1.59c.39.39.39 1.02 0 1.41z"/></svg>
          </button>
</form>        <!-- '"` --><!-- </textarea></xmp> --></option></form><form accept-charset="UTF-8" action="/dchen71/datasciencecoursera/delete/master/Reproducible%20Research/Project%201/PA1_template.md" class="inline-form" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="5177GYdMsgP4wCDW1kZtIG/MfXK45POr9MEmmySWDEhm93DORpH1nSlnJZyrEk1b5MNWiP43wVjjxPtnpEEOqA==" /></div>
          <button class="btn-octicon btn-octicon-danger tooltipped tooltipped-nw" type="submit"
            aria-label="Fork this project and delete the file" data-disable-with>
            <svg aria-hidden="true" class="octicon octicon-trashcan" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M11 2H9c0-.55-.45-1-1-1H5c-.55 0-1 .45-1 1H2c-.55 0-1 .45-1 1v1c0 .55.45 1 1 1v9c0 .55.45 1 1 1h7c.55 0 1-.45 1-1V5c.55 0 1-.45 1-1V3c0-.55-.45-1-1-1zm-1 12H3V5h1v8h1V5h1v8h1V5h1v8h1V5h1v9zm1-10H2V3h9v1z"/></svg>
          </button>
</form>  </div>

  <div class="file-info">
      259 lines (215 sloc)
      <span class="file-info-divider"></span>
    11 KB
  </div>
</div>

    
  <div id="readme" class="readme blob instapaper_body">
    <article class="markdown-body entry-content" itemprop="text"><table data-table-type="yaml-metadata">
  <thead>
  <tr>
  <th>title</th>

  <th>output</th>
  </tr>
  </thead>
  <tbody>
  <tr>
  <td><div>PA1_template</div></td>

  <td><div>html_document</div></td>
  </tr>
  </tbody>
</table>

<p>###Introduction</p>
<p>It is now possible to collect a large amount of data about personal movement using activity monitoring devices such as a Fitbit, Nike Fuelband, or Jawbone Up. These type of devices are part of the "quantified self" movement -- a group of enthusiasts who take measurements about themselves regularly to improve their health, to find patterns in their behavior, or because they are tech geeks. But these data remain under-utilized both because the raw data are hard to obtain and there is a lack of statistical methods and software for processing and interpreting the data.</p>
<p>This assignment makes use of data from a personal activity monitoring device. This device collects data at 5 minute intervals through out the day. The data consists of two months of data from an anonymous individual collected during the months of October and November, 2012 and include the number of steps taken in 5 minute intervals each day.</p>
<p>###Loading and preprocessing the data
This part of the code is necessary for the inital loading of the dataset</p>
<div class="highlight highlight-source-r"><pre>    <span class="pl-c"><span class="pl-c">#</span>Reads the data</span>
    <span class="pl-v">data</span> <span class="pl-k">=</span> read.csv(<span class="pl-s"><span class="pl-pds">'</span>activity.csv<span class="pl-pds">'</span></span>)
    <span class="pl-smi">data</span><span class="pl-k">$</span><span class="pl-v">date</span> <span class="pl-k">=</span> as.Date(<span class="pl-smi">data</span><span class="pl-k">$</span><span class="pl-smi">date</span>, <span class="pl-s"><span class="pl-pds">"</span>%Y-%m-%d<span class="pl-pds">"</span></span>)
    <span class="pl-c"><span class="pl-c">#</span>Splits the data per date</span>
    <span class="pl-v">splitDay</span> <span class="pl-k">=</span> split(<span class="pl-smi">data</span>, <span class="pl-smi">data</span><span class="pl-k">$</span><span class="pl-smi">date</span>)</pre></div>
<p>###What is mean total number of steps taken per day?</p>
<div class="highlight highlight-source-r"><pre>    <span class="pl-c"><span class="pl-c">#</span>Total number of steps/Median per day</span>
    <span class="pl-v">totalSteps</span> <span class="pl-k">=</span> sapply(<span class="pl-smi">splitDay</span>, <span class="pl-k">function</span>(<span class="pl-smi">x</span>) sum(<span class="pl-smi">x</span><span class="pl-k">$</span><span class="pl-smi">steps</span>))
    <span class="pl-v">medianSteps</span> <span class="pl-k">=</span> sapply(<span class="pl-smi">splitDay</span>, <span class="pl-k">function</span>(<span class="pl-smi">x</span>) median(<span class="pl-smi">x</span><span class="pl-k">$</span><span class="pl-smi">steps</span>))
    hist(<span class="pl-smi">totalSteps</span>,<span class="pl-v">main</span><span class="pl-k">=</span><span class="pl-s"><span class="pl-pds">"</span>Histogram of Frequency of TotalSteps/Day<span class="pl-pds">"</span></span>)</pre></div>
<p><a href="/dchen71/datasciencecoursera/blob/master/Reproducible%20Research/Project%201/figure/unnamed-chunk-2-1.png" target="_blank"><img src="/dchen71/datasciencecoursera/raw/master/Reproducible%20Research/Project%201/figure/unnamed-chunk-2-1.png" alt="plot of chunk unnamed-chunk-2" style="max-width:100%;"></a></p>
<p>Total number of steps/day</p>
<pre><code>## 2012-10-01 2012-10-02 2012-10-03 2012-10-04 2012-10-05 2012-10-06 
##         NA        126      11352      12116      13294      15420 
## 2012-10-07 2012-10-08 2012-10-09 2012-10-10 2012-10-11 2012-10-12 
##      11015         NA      12811       9900      10304      17382 
## 2012-10-13 2012-10-14 2012-10-15 2012-10-16 2012-10-17 2012-10-18 
##      12426      15098      10139      15084      13452      10056 
## 2012-10-19 2012-10-20 2012-10-21 2012-10-22 2012-10-23 2012-10-24 
##      11829      10395       8821      13460       8918       8355 
## 2012-10-25 2012-10-26 2012-10-27 2012-10-28 2012-10-29 2012-10-30 
##       2492       6778      10119      11458       5018       9819 
## 2012-10-31 2012-11-01 2012-11-02 2012-11-03 2012-11-04 2012-11-05 
##      15414         NA      10600      10571         NA      10439 
## 2012-11-06 2012-11-07 2012-11-08 2012-11-09 2012-11-10 2012-11-11 
##       8334      12883       3219         NA         NA      12608 
## 2012-11-12 2012-11-13 2012-11-14 2012-11-15 2012-11-16 2012-11-17 
##      10765       7336         NA         41       5441      14339 
## 2012-11-18 2012-11-19 2012-11-20 2012-11-21 2012-11-22 2012-11-23 
##      15110       8841       4472      12787      20427      21194 
## 2012-11-24 2012-11-25 2012-11-26 2012-11-27 2012-11-28 2012-11-29 
##      14478      11834      11162      13646      10183       7047 
## 2012-11-30 
##         NA
</code></pre>
<p>Median number of steps/day</p>
<pre><code>## 2012-10-01 2012-10-02 2012-10-03 2012-10-04 2012-10-05 2012-10-06 
##         NA          0          0          0          0          0 
## 2012-10-07 2012-10-08 2012-10-09 2012-10-10 2012-10-11 2012-10-12 
##          0         NA          0          0          0          0 
## 2012-10-13 2012-10-14 2012-10-15 2012-10-16 2012-10-17 2012-10-18 
##          0          0          0          0          0          0 
## 2012-10-19 2012-10-20 2012-10-21 2012-10-22 2012-10-23 2012-10-24 
##          0          0          0          0          0          0 
## 2012-10-25 2012-10-26 2012-10-27 2012-10-28 2012-10-29 2012-10-30 
##          0          0          0          0          0          0 
## 2012-10-31 2012-11-01 2012-11-02 2012-11-03 2012-11-04 2012-11-05 
##          0         NA          0          0         NA          0 
## 2012-11-06 2012-11-07 2012-11-08 2012-11-09 2012-11-10 2012-11-11 
##          0          0          0         NA         NA          0 
## 2012-11-12 2012-11-13 2012-11-14 2012-11-15 2012-11-16 2012-11-17 
##          0          0         NA          0          0          0 
## 2012-11-18 2012-11-19 2012-11-20 2012-11-21 2012-11-22 2012-11-23 
##          0          0          0          0          0          0 
## 2012-11-24 2012-11-25 2012-11-26 2012-11-27 2012-11-28 2012-11-29 
##          0          0          0          0          0          0 
## 2012-11-30 
##         NA
</code></pre>
<p>###What is the average daily activity pattern?
The code initializes the dataset and creates a plot to find the average steps vs time interval</p>
<div class="highlight highlight-source-r"><pre>    <span class="pl-c"><span class="pl-c">#</span>Preallocate vector</span>
    <span class="pl-v">interval</span> <span class="pl-k">=</span> seq(<span class="pl-c1">0</span>,<span class="pl-c1">2355</span>,<span class="pl-c1">5</span>)
    <span class="pl-v">steps</span> <span class="pl-k">=</span> <span class="pl-k">numeric</span>()
    <span class="pl-k">for</span>(<span class="pl-smi">i</span> <span class="pl-k">in</span> <span class="pl-c1">1</span><span class="pl-k">:</span><span class="pl-c1">472</span>) {
        <span class="pl-smi">steps</span>[<span class="pl-smi">i</span>] <span class="pl-k">=</span> <span class="pl-c1">0</span>
    }
    <span class="pl-v">avgSteps</span> <span class="pl-k">=</span> <span class="pl-k">data.frame</span>(<span class="pl-smi">interval</span>, <span class="pl-smi">steps</span>)
    names(<span class="pl-smi">avgSteps</span>) <span class="pl-k">=</span> c(<span class="pl-s"><span class="pl-pds">'</span>interval<span class="pl-pds">'</span></span>,<span class="pl-s"><span class="pl-pds">'</span>avgsteps<span class="pl-pds">'</span></span>)
    
    <span class="pl-c"><span class="pl-c">#</span>Adds the mean data in for the 5 minute interval</span>
    <span class="pl-k">for</span> (<span class="pl-smi">i</span> <span class="pl-k">in</span> <span class="pl-c1">1</span><span class="pl-k">:</span><span class="pl-c1">472</span>){
        <span class="pl-smi">avgSteps</span><span class="pl-k">$</span><span class="pl-smi">avgsteps</span>[<span class="pl-smi">i</span>] <span class="pl-k">=</span> mean(<span class="pl-smi">data</span><span class="pl-k">$</span><span class="pl-smi">steps</span>[<span class="pl-smi">data</span><span class="pl-k">$</span><span class="pl-smi">interval</span> <span class="pl-k">==</span> <span class="pl-smi">interval</span>[<span class="pl-smi">i</span>]], <span class="pl-v">na.rm</span><span class="pl-k">=</span><span class="pl-c1">TRUE</span>)
    }
    
    <span class="pl-c"><span class="pl-c">#</span>Plots the avgsteps vs time interval</span>
    plot(<span class="pl-smi">avgSteps</span>, <span class="pl-v">type</span><span class="pl-k">=</span><span class="pl-s"><span class="pl-pds">'</span>l<span class="pl-pds">'</span></span>, <span class="pl-v">main</span><span class="pl-k">=</span><span class="pl-s"><span class="pl-pds">'</span>Avg. Steps over 5 minute intervals<span class="pl-pds">'</span></span>,<span class="pl-v">xlab</span><span class="pl-k">=</span><span class="pl-s"><span class="pl-pds">'</span>Interval(minutes)<span class="pl-pds">'</span></span>,
         <span class="pl-v">ylab</span><span class="pl-k">=</span><span class="pl-s"><span class="pl-pds">'</span>Average Steps<span class="pl-pds">'</span></span>)</pre></div>
<p><a href="/dchen71/datasciencecoursera/blob/master/Reproducible%20Research/Project%201/figure/unnamed-chunk-5-1.png" target="_blank"><img src="/dchen71/datasciencecoursera/raw/master/Reproducible%20Research/Project%201/figure/unnamed-chunk-5-1.png" alt="plot of chunk unnamed-chunk-5" style="max-width:100%;"></a></p>
<div class="highlight highlight-source-r"><pre>    <span class="pl-c"><span class="pl-c">#</span>Finds the interval with the highest avg</span>
    <span class="pl-smi">avgSteps</span><span class="pl-k">$</span><span class="pl-smi">interval</span>[which.max(<span class="pl-smi">avgSteps</span><span class="pl-k">$</span><span class="pl-smi">avgsteps</span>)]</pre></div>
<pre><code>## [1] 835
</code></pre>
<p>The interval with the highest average is 835</p>
<p>##Imputing missing values</p>
<div class="highlight highlight-source-r"><pre>    <span class="pl-c"><span class="pl-c">#</span>Counts number of na values in steps</span>
    <span class="pl-v">numNa</span> <span class="pl-k">=</span> sum(is.na(<span class="pl-smi">data</span><span class="pl-k">$</span><span class="pl-smi">steps</span>))</pre></div>
<p>The number of NA values in the dataset is 2304</p>
<p>All NA values will be replaced with 0</p>
<div class="highlight highlight-source-r"><pre>    <span class="pl-c"><span class="pl-c">#</span>Replaces NA with 0</span>
    <span class="pl-v">noNa</span> <span class="pl-k">=</span> <span class="pl-smi">data</span>
    <span class="pl-smi">noNa</span>[is.na(<span class="pl-smi">noNa</span>)]<span class="pl-k">=</span><span class="pl-c1">0</span>
    <span class="pl-c"><span class="pl-c">#</span>Splits the data per date</span>
    <span class="pl-v">splitNa</span> <span class="pl-k">=</span> split(<span class="pl-smi">noNa</span>, <span class="pl-smi">noNa</span><span class="pl-k">$</span><span class="pl-smi">date</span>)
    <span class="pl-c"><span class="pl-c">#</span>Average steps/median</span>
    <span class="pl-v">totalNa</span> <span class="pl-k">=</span> sapply(<span class="pl-smi">splitNa</span>, <span class="pl-k">function</span>(<span class="pl-smi">x</span>) sum(<span class="pl-smi">x</span><span class="pl-k">$</span><span class="pl-smi">steps</span>))
    <span class="pl-c"><span class="pl-c">#</span>Plots histogram of the number of total steps per day</span>
    hist(<span class="pl-smi">totalNa</span>,<span class="pl-v">main</span><span class="pl-k">=</span><span class="pl-s"><span class="pl-pds">"</span>Histogram of Frequency of TotalSteps/Day<span class="pl-pds">"</span></span>, <span class="pl-v">xlab</span><span class="pl-k">=</span><span class="pl-s"><span class="pl-pds">"</span>Total number of Steps<span class="pl-pds">"</span></span>)</pre></div>
<p><a href="/dchen71/datasciencecoursera/blob/master/Reproducible%20Research/Project%201/figure/unnamed-chunk-7-1.png" target="_blank"><img src="/dchen71/datasciencecoursera/raw/master/Reproducible%20Research/Project%201/figure/unnamed-chunk-7-1.png" alt="plot of chunk unnamed-chunk-7" style="max-width:100%;"></a></p>
<div class="highlight highlight-source-r"><pre>    <span class="pl-c"><span class="pl-c">#</span>Average/mean across all values</span>
    <span class="pl-v">avgNa</span> <span class="pl-k">=</span> sapply(<span class="pl-smi">splitNa</span>, <span class="pl-k">function</span>(<span class="pl-smi">x</span>) mean(<span class="pl-smi">x</span><span class="pl-k">$</span><span class="pl-smi">steps</span>))
    <span class="pl-v">medNa</span> <span class="pl-k">=</span> sapply(<span class="pl-smi">splitNa</span>, <span class="pl-k">function</span>(<span class="pl-smi">x</span>) median(<span class="pl-smi">x</span><span class="pl-k">$</span><span class="pl-smi">steps</span>))</pre></div>
<p>The following is the adjusted average values after changing all NA values to 0</p>
<pre><code>## 2012-10-01 2012-10-02 2012-10-03 2012-10-04 2012-10-05 2012-10-06 
##  0.0000000  0.4375000 39.4166667 42.0694444 46.1597222 53.5416667 
## 2012-10-07 2012-10-08 2012-10-09 2012-10-10 2012-10-11 2012-10-12 
## 38.2465278  0.0000000 44.4826389 34.3750000 35.7777778 60.3541667 
## 2012-10-13 2012-10-14 2012-10-15 2012-10-16 2012-10-17 2012-10-18 
## 43.1458333 52.4236111 35.2048611 52.3750000 46.7083333 34.9166667 
## 2012-10-19 2012-10-20 2012-10-21 2012-10-22 2012-10-23 2012-10-24 
## 41.0729167 36.0937500 30.6284722 46.7361111 30.9652778 29.0104167 
## 2012-10-25 2012-10-26 2012-10-27 2012-10-28 2012-10-29 2012-10-30 
##  8.6527778 23.5347222 35.1354167 39.7847222 17.4236111 34.0937500 
## 2012-10-31 2012-11-01 2012-11-02 2012-11-03 2012-11-04 2012-11-05 
## 53.5208333  0.0000000 36.8055556 36.7048611  0.0000000 36.2465278 
## 2012-11-06 2012-11-07 2012-11-08 2012-11-09 2012-11-10 2012-11-11 
## 28.9375000 44.7326389 11.1770833  0.0000000  0.0000000 43.7777778 
## 2012-11-12 2012-11-13 2012-11-14 2012-11-15 2012-11-16 2012-11-17 
## 37.3784722 25.4722222  0.0000000  0.1423611 18.8923611 49.7881944 
## 2012-11-18 2012-11-19 2012-11-20 2012-11-21 2012-11-22 2012-11-23 
## 52.4652778 30.6979167 15.5277778 44.3993056 70.9270833 73.5902778 
## 2012-11-24 2012-11-25 2012-11-26 2012-11-27 2012-11-28 2012-11-29 
## 50.2708333 41.0902778 38.7569444 47.3819444 35.3576389 24.4687500 
## 2012-11-30 
##  0.0000000
</code></pre>
<p>The following is the adjusted median values after chaning all NA values to 0</p>
<pre><code>## 2012-10-01 2012-10-02 2012-10-03 2012-10-04 2012-10-05 2012-10-06 
##          0          0          0          0          0          0 
## 2012-10-07 2012-10-08 2012-10-09 2012-10-10 2012-10-11 2012-10-12 
##          0          0          0          0          0          0 
## 2012-10-13 2012-10-14 2012-10-15 2012-10-16 2012-10-17 2012-10-18 
##          0          0          0          0          0          0 
## 2012-10-19 2012-10-20 2012-10-21 2012-10-22 2012-10-23 2012-10-24 
##          0          0          0          0          0          0 
## 2012-10-25 2012-10-26 2012-10-27 2012-10-28 2012-10-29 2012-10-30 
##          0          0          0          0          0          0 
## 2012-10-31 2012-11-01 2012-11-02 2012-11-03 2012-11-04 2012-11-05 
##          0          0          0          0          0          0 
## 2012-11-06 2012-11-07 2012-11-08 2012-11-09 2012-11-10 2012-11-11 
##          0          0          0          0          0          0 
## 2012-11-12 2012-11-13 2012-11-14 2012-11-15 2012-11-16 2012-11-17 
##          0          0          0          0          0          0 
## 2012-11-18 2012-11-19 2012-11-20 2012-11-21 2012-11-22 2012-11-23 
##          0          0          0          0          0          0 
## 2012-11-24 2012-11-25 2012-11-26 2012-11-27 2012-11-28 2012-11-29 
##          0          0          0          0          0          0 
## 2012-11-30 
##          0
</code></pre>
<p>###Are there differences in activity patterns between weekdays and weekends?</p>
<p>The following creates subsets containing the weekday/weekend values of the dataset</p>
<div class="highlight highlight-source-r"><pre>    <span class="pl-c"><span class="pl-c">#</span>Shows data of weekday and weekend values</span>
    <span class="pl-v">weekData</span> <span class="pl-k">=</span> <span class="pl-smi">data</span>
    <span class="pl-smi">weekData</span>[is.na(<span class="pl-smi">weekData</span>)]<span class="pl-k">=</span><span class="pl-c1">0</span>    
    <span class="pl-smi">weekData</span><span class="pl-k">$</span><span class="pl-v">days</span> <span class="pl-k">=</span> weekdays(<span class="pl-smi">weekData</span><span class="pl-k">$</span><span class="pl-smi">date</span>)
    <span class="pl-smi">weekData</span><span class="pl-k">$</span><span class="pl-v">days</span> <span class="pl-k">=</span> as.factor(ifelse(weekdays(<span class="pl-smi">weekData</span><span class="pl-k">$</span><span class="pl-smi">date</span>) <span class="pl-k">%in%</span> c(<span class="pl-s"><span class="pl-pds">"</span>Saturday<span class="pl-pds">"</span></span>,<span class="pl-s"><span class="pl-pds">"</span>Sunday<span class="pl-pds">"</span></span>), 
                                      <span class="pl-s"><span class="pl-pds">"</span>Weekend<span class="pl-pds">"</span></span>, <span class="pl-s"><span class="pl-pds">"</span>Weekday<span class="pl-pds">"</span></span>)) 

    <span class="pl-v">avgEnd</span> <span class="pl-k">=</span> mean(<span class="pl-smi">weekData</span><span class="pl-k">$</span><span class="pl-smi">steps</span>[<span class="pl-smi">weekData</span><span class="pl-k">$</span><span class="pl-smi">days</span> <span class="pl-k">==</span> <span class="pl-s"><span class="pl-pds">'</span>Weekend<span class="pl-pds">'</span></span>])
    <span class="pl-v">avgDay</span> <span class="pl-k">=</span> mean(<span class="pl-smi">weekData</span><span class="pl-k">$</span><span class="pl-smi">steps</span>[<span class="pl-smi">weekData</span><span class="pl-k">$</span><span class="pl-smi">days</span> <span class="pl-k">==</span> <span class="pl-s"><span class="pl-pds">'</span>Weekday<span class="pl-pds">'</span></span>])

    <span class="pl-c"><span class="pl-c">#</span>Subset weekday and weekend values</span>
    <span class="pl-v">weekdays</span> <span class="pl-k">=</span> subset(<span class="pl-smi">weekData</span>, <span class="pl-smi">weekData</span><span class="pl-k">$</span><span class="pl-smi">days</span> <span class="pl-k">==</span> <span class="pl-s"><span class="pl-pds">'</span>Weekday<span class="pl-pds">'</span></span>)
    <span class="pl-v">weekends</span> <span class="pl-k">=</span> subset(<span class="pl-smi">weekData</span>, <span class="pl-smi">weekData</span><span class="pl-k">$</span><span class="pl-smi">days</span> <span class="pl-k">==</span> <span class="pl-s"><span class="pl-pds">'</span>Weekend<span class="pl-pds">'</span></span>)
    
    <span class="pl-c"><span class="pl-c">#</span>Preallocate vector</span>
    <span class="pl-v">weekend</span> <span class="pl-k">=</span> <span class="pl-k">numeric</span>()
    <span class="pl-v">weekday</span> <span class="pl-k">=</span> <span class="pl-k">numeric</span>()
    <span class="pl-k">for</span>(<span class="pl-smi">i</span> <span class="pl-k">in</span> <span class="pl-c1">1</span><span class="pl-k">:</span><span class="pl-c1">472</span>) {
        <span class="pl-smi">weekday</span>[<span class="pl-smi">i</span>] <span class="pl-k">=</span> <span class="pl-c1">0</span>
        <span class="pl-smi">weekend</span>[<span class="pl-smi">i</span>] <span class="pl-k">=</span> <span class="pl-c1">0</span>
    }
    <span class="pl-v">avgWeek</span> <span class="pl-k">=</span> <span class="pl-k">data.frame</span>(<span class="pl-smi">interval</span>, <span class="pl-smi">weekend</span>, <span class="pl-smi">weekday</span>)
    names(<span class="pl-smi">avgWeek</span>) <span class="pl-k">=</span> c(<span class="pl-s"><span class="pl-pds">'</span>interval<span class="pl-pds">'</span></span>,<span class="pl-s"><span class="pl-pds">'</span>avgsteps.weekend<span class="pl-pds">'</span></span>,<span class="pl-s"><span class="pl-pds">'</span>avgsteps.weekday<span class="pl-pds">'</span></span>)
    
    <span class="pl-c"><span class="pl-c">#</span>Adds the mean data in for the 5 minute interval</span>
    <span class="pl-k">for</span> (<span class="pl-smi">i</span> <span class="pl-k">in</span> <span class="pl-c1">1</span><span class="pl-k">:</span><span class="pl-c1">472</span>){
        <span class="pl-smi">avgWeek</span><span class="pl-k">$</span><span class="pl-smi">avgsteps.weekday</span>[<span class="pl-smi">i</span>] <span class="pl-k">=</span> mean(<span class="pl-smi">weekdays</span><span class="pl-k">$</span><span class="pl-smi">steps</span>[<span class="pl-smi">weekdays</span><span class="pl-k">$</span><span class="pl-smi">interval</span> <span class="pl-k">==</span> <span class="pl-smi">interval</span>[<span class="pl-smi">i</span>]], <span class="pl-v">na.rm</span><span class="pl-k">=</span><span class="pl-c1">TRUE</span>)
        <span class="pl-smi">avgWeek</span><span class="pl-k">$</span><span class="pl-smi">avgsteps.weekend</span>[<span class="pl-smi">i</span>] <span class="pl-k">=</span> mean(<span class="pl-smi">weekends</span><span class="pl-k">$</span><span class="pl-smi">steps</span>[<span class="pl-smi">weekends</span><span class="pl-k">$</span><span class="pl-smi">interval</span> <span class="pl-k">==</span> <span class="pl-smi">interval</span>[<span class="pl-smi">i</span>]], <span class="pl-v">na.rm</span><span class="pl-k">=</span><span class="pl-c1">TRUE</span>)
    }</pre></div>
<p>The plot is setup to show the differences in the average steps vs time period between weekends and weekdays</p>
<div class="highlight highlight-source-r"><pre>    <span class="pl-c"><span class="pl-c">#</span>Creates the plots</span>
    par(<span class="pl-v">mfrow</span><span class="pl-k">=</span>c(<span class="pl-c1">2</span>,<span class="pl-c1">1</span>))
    plot(<span class="pl-smi">avgWeek</span><span class="pl-k">$</span><span class="pl-smi">interval</span>, <span class="pl-smi">avgWeek</span><span class="pl-k">$</span><span class="pl-smi">avgsteps.weekend</span>, <span class="pl-v">type</span><span class="pl-k">=</span><span class="pl-s"><span class="pl-pds">'</span>l<span class="pl-pds">'</span></span>, <span class="pl-v">main</span> <span class="pl-k">=</span><span class="pl-s"><span class="pl-pds">"</span>Weekend vs Avg Steps<span class="pl-pds">"</span></span>,
         <span class="pl-v">xlab</span><span class="pl-k">=</span><span class="pl-s"><span class="pl-pds">"</span>Interval(steps)<span class="pl-pds">"</span></span>, <span class="pl-v">ylab</span><span class="pl-k">=</span><span class="pl-s"><span class="pl-pds">"</span>Average Steps<span class="pl-pds">"</span></span>)
    plot(<span class="pl-smi">avgWeek</span><span class="pl-k">$</span><span class="pl-smi">interval</span>, <span class="pl-smi">avgWeek</span><span class="pl-k">$</span><span class="pl-smi">avgsteps.weekday</span>, <span class="pl-v">main</span> <span class="pl-k">=</span><span class="pl-s"><span class="pl-pds">"</span>Weekday vs Avg Steps<span class="pl-pds">"</span></span>, 
         <span class="pl-v">xlab</span><span class="pl-k">=</span><span class="pl-s"><span class="pl-pds">"</span>Interval(steps)<span class="pl-pds">"</span></span>, <span class="pl-v">ylab</span><span class="pl-k">=</span><span class="pl-s"><span class="pl-pds">"</span>Average Steps<span class="pl-pds">"</span></span>, <span class="pl-v">type</span><span class="pl-k">=</span><span class="pl-s"><span class="pl-pds">'</span>l<span class="pl-pds">'</span></span>)</pre></div>
<p><a href="/dchen71/datasciencecoursera/blob/master/Reproducible%20Research/Project%201/figure/unnamed-chunk-11-1.png" target="_blank"><img src="/dchen71/datasciencecoursera/raw/master/Reproducible%20Research/Project%201/figure/unnamed-chunk-11-1.png" alt="plot of chunk unnamed-chunk-11" style="max-width:100%;"></a></p>
</article>
  </div>

  </div>

  <button type="button" data-facebox="#jump-to-line" data-facebox-class="linejump" data-hotkey="l" class="d-none">Jump to Line</button>
  <div id="jump-to-line" style="display:none">
    <!-- '"` --><!-- </textarea></xmp> --></option></form><form accept-charset="UTF-8" action="" class="js-jump-to-line-form" method="get"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /></div>
      <input class="form-control linejump-input js-jump-to-line-field" type="text" placeholder="Jump to line&hellip;" aria-label="Jump to line" autofocus>
      <button type="submit" class="btn">Go</button>
</form>  </div>

  </div>
  <div class="modal-backdrop js-touch-events"></div>
</div>

    </div>
  </div>

  </div>

      
<div class="footer container-lg px-3" role="contentinfo">
  <div class="position-relative d-flex flex-justify-between py-6 mt-6 f6 text-gray border-top border-gray-light ">
    <ul class="list-style-none d-flex flex-wrap ">
      <li class="mr-3">&copy; 2017 <span title="0.15075s from unicorn-989893024-wpwrr">GitHub</span>, Inc.</li>
        <li class="mr-3"><a href="https://github.com/site/terms" data-ga-click="Footer, go to terms, text:terms">Terms</a></li>
        <li class="mr-3"><a href="https://github.com/site/privacy" data-ga-click="Footer, go to privacy, text:privacy">Privacy</a></li>
        <li class="mr-3"><a href="https://github.com/security" data-ga-click="Footer, go to security, text:security">Security</a></li>
        <li class="mr-3"><a href="https://status.github.com/" data-ga-click="Footer, go to status, text:status">Status</a></li>
        <li><a href="https://help.github.com" data-ga-click="Footer, go to help, text:help">Help</a></li>
    </ul>

    <a href="https://github.com" aria-label="Homepage" class="footer-octicon" title="GitHub">
      <svg aria-hidden="true" class="octicon octicon-mark-github" height="24" version="1.1" viewBox="0 0 16 16" width="24"><path fill-rule="evenodd" d="M8 0C3.58 0 0 3.58 0 8c0 3.54 2.29 6.53 5.47 7.59.4.07.55-.17.55-.38 0-.19-.01-.82-.01-1.49-2.01.37-2.53-.49-2.69-.94-.09-.23-.48-.94-.82-1.13-.28-.15-.68-.52-.01-.53.63-.01 1.08.58 1.23.82.72 1.21 1.87.87 2.33.66.07-.52.28-.87.51-1.07-1.78-.2-3.64-.89-3.64-3.95 0-.87.31-1.59.82-2.15-.08-.2-.36-1.02.08-2.12 0 0 .67-.21 2.2.82.64-.18 1.32-.27 2-.27.68 0 1.36.09 2 .27 1.53-1.04 2.2-.82 2.2-.82.44 1.1.16 1.92.08 2.12.51.56.82 1.27.82 2.15 0 3.07-1.87 3.75-3.65 3.95.29.25.54.73.54 1.48 0 1.07-.01 1.93-.01 2.2 0 .21.15.46.55.38A8.013 8.013 0 0 0 16 8c0-4.42-3.58-8-8-8z"/></svg>
</a>
    <ul class="list-style-none d-flex flex-wrap ">
        <li class="mr-3"><a href="https://github.com/contact" data-ga-click="Footer, go to contact, text:contact">Contact GitHub</a></li>
      <li class="mr-3"><a href="https://developer.github.com" data-ga-click="Footer, go to api, text:api">API</a></li>
      <li class="mr-3"><a href="https://training.github.com" data-ga-click="Footer, go to training, text:training">Training</a></li>
      <li class="mr-3"><a href="https://shop.github.com" data-ga-click="Footer, go to shop, text:shop">Shop</a></li>
        <li class="mr-3"><a href="https://github.com/blog" data-ga-click="Footer, go to blog, text:blog">Blog</a></li>
        <li><a href="https://github.com/about" data-ga-click="Footer, go to about, text:about">About</a></li>

    </ul>
  </div>
</div>



  <div id="ajax-error-message" class="ajax-error-message flash flash-error">
    <svg aria-hidden="true" class="octicon octicon-alert" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M8.865 1.52c-.18-.31-.51-.5-.87-.5s-.69.19-.87.5L.275 13.5c-.18.31-.18.69 0 1 .19.31.52.5.87.5h13.7c.36 0 .69-.19.86-.5.17-.31.18-.69.01-1L8.865 1.52zM8.995 13h-2v-2h2v2zm0-3h-2V6h2v4z"/></svg>
    <button type="button" class="flash-close js-flash-close js-ajax-error-dismiss" aria-label="Dismiss error">
      <svg aria-hidden="true" class="octicon octicon-x" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M7.48 8l3.75 3.75-1.48 1.48L6 9.48l-3.75 3.75-1.48-1.48L4.52 8 .77 4.25l1.48-1.48L6 6.52l3.75-3.75 1.48 1.48z"/></svg>
    </button>
    You can't perform that action at this time.
  </div>


    
    <script crossorigin="anonymous" integrity="sha256-8q4ohCjL4ztV3ECDYeIe1e5DMasRlfxtng0fybFEsEI=" src="https://assets-cdn.github.com/assets/frameworks-f2ae288428cbe33b55dc408361e21ed5ee4331ab1195fc6d9e0d1fc9b144b042.js"></script>
    
    <script async="async" crossorigin="anonymous" integrity="sha256-z++Hm3crDoqeaDOimGQpPvMd0jo6K12WjBGLJ6Vx3Vw=" src="https://assets-cdn.github.com/assets/github-cfef879b772b0e8a9e6833a29864293ef31dd23a3a2b5d968c118b27a571dd5c.js"></script>
    
    
    
    
  <div class="js-stale-session-flash stale-session-flash flash flash-warn flash-banner d-none">
    <svg aria-hidden="true" class="octicon octicon-alert" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M8.865 1.52c-.18-.31-.51-.5-.87-.5s-.69.19-.87.5L.275 13.5c-.18.31-.18.69 0 1 .19.31.52.5.87.5h13.7c.36 0 .69-.19.86-.5.17-.31.18-.69.01-1L8.865 1.52zM8.995 13h-2v-2h2v2zm0-3h-2V6h2v4z"/></svg>
    <span class="signed-in-tab-flash">You signed in with another tab or window. <a href="">Reload</a> to refresh your session.</span>
    <span class="signed-out-tab-flash">You signed out in another tab or window. <a href="">Reload</a> to refresh your session.</span>
  </div>
  <div class="facebox" id="facebox" style="display:none;">
  <div class="facebox-popup">
    <div class="facebox-content" role="dialog" aria-labelledby="facebox-header" aria-describedby="facebox-description">
    </div>
    <button type="button" class="facebox-close js-facebox-close" aria-label="Close modal">
      <svg aria-hidden="true" class="octicon octicon-x" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M7.48 8l3.75 3.75-1.48 1.48L6 9.48l-3.75 3.75-1.48-1.48L4.52 8 .77 4.25l1.48-1.48L6 6.52l3.75-3.75 1.48 1.48z"/></svg>
    </button>
  </div>
</div>


  </body>
</html>

