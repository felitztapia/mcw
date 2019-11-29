





<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="utf-8">
  <link rel="dns-prefetch" href="https://github.githubassets.com">
  <link rel="dns-prefetch" href="https://avatars0.githubusercontent.com">
  <link rel="dns-prefetch" href="https://avatars1.githubusercontent.com">
  <link rel="dns-prefetch" href="https://avatars2.githubusercontent.com">
  <link rel="dns-prefetch" href="https://avatars3.githubusercontent.com">
  <link rel="dns-prefetch" href="https://github-cloud.s3.amazonaws.com">
  <link rel="dns-prefetch" href="https://user-images.githubusercontent.com/">



  <link crossorigin="anonymous" media="all" integrity="sha512-/YEVWs7BzxfKyUd6zVxjEQcXRWsLbcEjv045Rq8DSoipySmQblhVKxlXLva2GtNd5DhwCxHwW1RM0N9I7S2Vew==" rel="stylesheet" href="https://github.githubassets.com/assets/frameworks-481a47a96965f6706fb41bae0d14b09a.css" />
  
    <link crossorigin="anonymous" media="all" integrity="sha512-xlKdcTpXrrd+rLG1h8yYl5yt/S94zWLil75KS5529Mf0/RdApUbGTKcFbY0OZMotEz3l11k0GqfDAhasayWehw==" rel="stylesheet" href="https://github.githubassets.com/assets/github-eabfbaded2e91939e805d1a3af34018a.css" />
    
    
    
    


  <meta name="viewport" content="width=device-width">
  
  <title>MCW-Modern-cloud-apps/WDS trainer guide - Modern cloud apps.md at master · microsoft/MCW-Modern-cloud-apps</title>
    <meta name="description" content="MCW Modern cloud apps. Contribute to microsoft/MCW-Modern-cloud-apps development by creating an account on GitHub.">
    <link rel="search" type="application/opensearchdescription+xml" href="/opensearch.xml" title="GitHub">
  <link rel="fluid-icon" href="https://github.com/fluidicon.png" title="GitHub">
  <meta property="fb:app_id" content="1401488693436528">

    <meta name="twitter:image:src" content="https://avatars2.githubusercontent.com/u/6154722?s=400&amp;v=4" /><meta name="twitter:site" content="@github" /><meta name="twitter:card" content="summary" /><meta name="twitter:title" content="microsoft/MCW-Modern-cloud-apps" /><meta name="twitter:description" content="MCW Modern cloud apps. Contribute to microsoft/MCW-Modern-cloud-apps development by creating an account on GitHub." />
    <meta property="og:image" content="https://avatars2.githubusercontent.com/u/6154722?s=400&amp;v=4" /><meta property="og:site_name" content="GitHub" /><meta property="og:type" content="object" /><meta property="og:title" content="microsoft/MCW-Modern-cloud-apps" /><meta property="og:url" content="https://github.com/microsoft/MCW-Modern-cloud-apps" /><meta property="og:description" content="MCW Modern cloud apps. Contribute to microsoft/MCW-Modern-cloud-apps development by creating an account on GitHub." />

  <link rel="assets" href="https://github.githubassets.com/">
  <link rel="web-socket" href="wss://live.github.com/_sockets/VjI6NDQ5MDc4MDkzOmE1N2VmMmEyNjdlNjhhYTQ3NzI2NDNmZmZmNzUwNjg5MjU3MGMwOGU4ZDE3Y2RhYzIyY2E4MWEwYzliMjI2NGI=--ca3d1d314706b7d9d59903a3a0e4ad955bc15e17">
  <link rel="sudo-modal" href="/sessions/sudo_modal">

    <meta name="request-id" content="72E4:6BE8:790269:B95DD5:5DE09FE1" data-pjax-transient>


  

  <meta name="selected-link" value="repo_source" data-pjax-transient>

      <meta name="google-site-verification" content="KT5gs8h0wvaagLKAVWq8bbeNwnZZK1r1XQysX3xurLU">
    <meta name="google-site-verification" content="ZzhVyEFwb7w3e0-uOTltm8Jsck2F5StVihD0exw2fsA">
    <meta name="google-site-verification" content="GXs5KoUUkNCoaAZn7wPN-t01Pywp9M3sEjnt_3_ZWPc">

    <meta name="octolytics-host" content="collector.githubapp.com" /><meta name="octolytics-app-id" content="github" /><meta name="octolytics-event-url" content="https://collector.githubapp.com/github-external/browser_event" /><meta name="octolytics-dimension-request_id" content="72E4:6BE8:790269:B95DD5:5DE09FE1" /><meta name="octolytics-dimension-region_edge" content="ap-southeast-2" /><meta name="octolytics-dimension-region_render" content="iad" /><meta name="octolytics-dimension-ga_id" content="" class="js-octo-ga-id" /><meta name="octolytics-dimension-visitor_id" content="2579826198724970485" /><meta name="octolytics-actor-id" content="16497068" /><meta name="octolytics-actor-login" content="mxie220" /><meta name="octolytics-actor-hash" content="866f800d7c8bd992e283943374f11afda9df86cee3101a8fbc604932c42c3f51" />

<meta name="analytics-location" content="/&lt;user-name&gt;/&lt;repo-name&gt;/blob/show" data-pjax-transient="true" />




  <meta class="js-ga-set" name="userId" content="4e7ac9c8839135698898bfc5caf46f65">

<meta class="js-ga-set" name="dimension1" content="Logged In">



  

      <meta name="hostname" content="github.com">
    <meta name="user-login" content="mxie220">

      <meta name="expected-hostname" content="github.com">

      <meta name="js-proxy-site-detection-payload" content="YTIxNTdjOWZkMGMwMWE0MzVjMjEzOTVjNDQ2NWE4MmE1NWZlODM0YWU0Y2Q1MjIxYzhkNjg4ZDMxMzc1ZDhhZnx7InJlbW90ZV9hZGRyZXNzIjoiMTY3LjIyMC4yNDIuMTU3IiwicmVxdWVzdF9pZCI6IjcyRTQ6NkJFODo3OTAyNjk6Qjk1REQ1OjVERTA5RkUxIiwidGltZXN0YW1wIjoxNTc1MDAyMTEyLCJob3N0IjoiZ2l0aHViLmNvbSJ9">

    <meta name="enabled-features" content="LAUNCH_PROJECT,MARKETPLACE_FEATURED_BLOG_POSTS,MARKETPLACE_INVOICED_BILLING,MARKETPLACE_SOCIAL_PROOF_CUSTOMERS,MARKETPLACE_TRENDING_SOCIAL_PROOF,MARKETPLACE_RECOMMENDATIONS,MARKETPLACE_PENDING_INSTALLATIONS,NOTIFY_ON_BLOCK,RELATED_ISSUES,GHE_CLOUD_TRIAL">

    <meta name="html-safe-nonce" content="d43b74f65c394a5e5b3d626572fd563f8134afea">

  <meta http-equiv="x-pjax-version" content="5889f893dcaa7c2acb03cae96934b7a4">
  

      <link href="https://github.com/microsoft/MCW-Modern-cloud-apps/commits/master.atom" rel="alternate" title="Recent Commits to MCW-Modern-cloud-apps:master" type="application/atom+xml">

  <meta name="go-import" content="github.com/microsoft/MCW-Modern-cloud-apps git https://github.com/microsoft/MCW-Modern-cloud-apps.git">

  <meta name="octolytics-dimension-user_id" content="6154722" /><meta name="octolytics-dimension-user_login" content="microsoft" /><meta name="octolytics-dimension-repository_id" content="122681898" /><meta name="octolytics-dimension-repository_nwo" content="microsoft/MCW-Modern-cloud-apps" /><meta name="octolytics-dimension-repository_public" content="true" /><meta name="octolytics-dimension-repository_is_fork" content="false" /><meta name="octolytics-dimension-repository_network_root_id" content="122681898" /><meta name="octolytics-dimension-repository_network_root_nwo" content="microsoft/MCW-Modern-cloud-apps" /><meta name="octolytics-dimension-repository_explore_github_marketplace_ci_cta_shown" content="false" />


    <link rel="canonical" href="https://github.com/microsoft/MCW-Modern-cloud-apps/blob/master/Whiteboard%20design%20session/WDS%20trainer%20guide%20-%20Modern%20cloud%20apps.md" data-pjax-transient>


  <meta name="browser-stats-url" content="https://api.github.com/_private/browser/stats">

  <meta name="browser-errors-url" content="https://api.github.com/_private/browser/errors">

  <link rel="mask-icon" href="https://github.githubassets.com/pinned-octocat.svg" color="#000000">
  <link rel="icon" type="image/x-icon" class="js-site-favicon" href="https://github.githubassets.com/favicon.ico">

<meta name="theme-color" content="#1e2327">



  <meta name="webauthn-auth-enabled" content="true">

  <meta name="webauthn-registration-enabled" content="true">

  <link rel="manifest" href="/manifest.json" crossOrigin="use-credentials">

  </head>

  <body class="logged-in env-production page-responsive page-blob">
    

  <div class="position-relative js-header-wrapper ">
    <a href="#start-of-content" tabindex="1" class="p-3 bg-blue text-white show-on-focus js-skip-to-content">Skip to content</a>
    <span class="Progress progress-pjax-loader position-fixed width-full js-pjax-loader-bar">
      <span class="progress-pjax-loader-bar top-0 left-0" style="width: 0%;"></span>
    </span>

    
    
    


          <header class="Header js-details-container Details flex-wrap flex-lg-nowrap p-responsive" role="banner">

    <div class="Header-item d-none d-lg-flex">
      <a class="Header-link" href="https://github.com/" data-hotkey="g d" aria-label="Homepage" data-ga-click="Header, go to dashboard, icon:logo">
  <svg class="octicon octicon-mark-github v-align-middle" height="32" viewBox="0 0 16 16" version="1.1" width="32" aria-hidden="true"><path fill-rule="evenodd" d="M8 0C3.58 0 0 3.58 0 8c0 3.54 2.29 6.53 5.47 7.59.4.07.55-.17.55-.38 0-.19-.01-.82-.01-1.49-2.01.37-2.53-.49-2.69-.94-.09-.23-.48-.94-.82-1.13-.28-.15-.68-.52-.01-.53.63-.01 1.08.58 1.23.82.72 1.21 1.87.87 2.33.66.07-.52.28-.87.51-1.07-1.78-.2-3.64-.89-3.64-3.95 0-.87.31-1.59.82-2.15-.08-.2-.36-1.02.08-2.12 0 0 .67-.21 2.2.82.64-.18 1.32-.27 2-.27.68 0 1.36.09 2 .27 1.53-1.04 2.2-.82 2.2-.82.44 1.1.16 1.92.08 2.12.51.56.82 1.27.82 2.15 0 3.07-1.87 3.75-3.65 3.95.29.25.54.73.54 1.48 0 1.07-.01 1.93-.01 2.2 0 .21.15.46.55.38A8.013 8.013 0 0016 8c0-4.42-3.58-8-8-8z"/></svg>
</a>

    </div>

    <div class="Header-item d-lg-none">
      <button class="Header-link btn-link js-details-target" type="button" aria-label="Toggle navigation" aria-expanded="false">
        <svg height="24" class="octicon octicon-three-bars" viewBox="0 0 12 16" version="1.1" width="18" aria-hidden="true"><path fill-rule="evenodd" d="M11.41 9H.59C0 9 0 8.59 0 8c0-.59 0-1 .59-1H11.4c.59 0 .59.41.59 1 0 .59 0 1-.59 1h.01zm0-4H.59C0 5 0 4.59 0 4c0-.59 0-1 .59-1H11.4c.59 0 .59.41.59 1 0 .59 0 1-.59 1h.01zM.59 11H11.4c.59 0 .59.41.59 1 0 .59 0 1-.59 1H.59C0 13 0 12.59 0 12c0-.59 0-1 .59-1z"/></svg>
      </button>
    </div>

    <div class="Header-item Header-item--full flex-column flex-lg-row width-full flex-order-2 flex-lg-order-none mr-0 mr-lg-3 mt-3 mt-lg-0 Details-content--hidden">
        <div class="header-search flex-self-stretch flex-lg-self-auto mr-0 mr-lg-3 mb-3 mb-lg-0 scoped-search site-scoped-search js-site-search position-relative js-jump-to"
  role="combobox"
  aria-owns="jump-to-results"
  aria-label="Search or jump to"
  aria-haspopup="listbox"
  aria-expanded="false"
>
  <div class="position-relative">
    <!-- '"` --><!-- </textarea></xmp> --></option></form><form class="js-site-search-form" role="search" aria-label="Site" data-scope-type="Repository" data-scope-id="122681898" data-scoped-search-url="/microsoft/MCW-Modern-cloud-apps/search" data-unscoped-search-url="/search" action="/microsoft/MCW-Modern-cloud-apps/search" accept-charset="UTF-8" method="get"><input name="utf8" type="hidden" value="&#x2713;" />
      <label class="form-control input-sm header-search-wrapper p-0 header-search-wrapper-jump-to position-relative d-flex flex-justify-between flex-items-center js-chromeless-input-container">
        <input type="text"
          class="form-control input-sm header-search-input jump-to-field js-jump-to-field js-site-search-focus js-site-search-field is-clearable"
          data-hotkey="s,/"
          name="q"
          value=""
          placeholder="Search or jump to…"
          data-unscoped-placeholder="Search or jump to…"
          data-scoped-placeholder="Search or jump to…"
          autocapitalize="off"
          aria-autocomplete="list"
          aria-controls="jump-to-results"
          aria-label="Search or jump to…"
          data-jump-to-suggestions-path="/_graphql/GetSuggestedNavigationDestinations#csrf-token=l/Wu1Qs/6qYYrWmFrngcUVOIWOb+bSw+kcpYcLqhf+ab5eyxyJUB9SYniDmLVtvPgOc5wbFPhBJGU89HO2qrAA=="
          spellcheck="false"
          autocomplete="off"
          >
          <input type="hidden" class="js-site-search-type-field" name="type" >
            <img src="https://github.githubassets.com/images/search-key-slash.svg" alt="" class="mr-2 header-search-key-slash">

            <div class="Box position-absolute overflow-hidden d-none jump-to-suggestions js-jump-to-suggestions-container">
              
<ul class="d-none js-jump-to-suggestions-template-container">
  

<li class="d-flex flex-justify-start flex-items-center p-0 f5 navigation-item js-navigation-item js-jump-to-suggestion" role="option">
  <a tabindex="-1" class="no-underline d-flex flex-auto flex-items-center jump-to-suggestions-path js-jump-to-suggestion-path js-navigation-open p-2" href="">
    <div class="jump-to-octicon js-jump-to-octicon flex-shrink-0 mr-2 text-center d-none">
      <svg height="16" width="16" class="octicon octicon-repo flex-shrink-0 js-jump-to-octicon-repo d-none" title="Repository" aria-label="Repository" viewBox="0 0 12 16" version="1.1" role="img"><path fill-rule="evenodd" d="M4 9H3V8h1v1zm0-3H3v1h1V6zm0-2H3v1h1V4zm0-2H3v1h1V2zm8-1v12c0 .55-.45 1-1 1H6v2l-1.5-1.5L3 16v-2H1c-.55 0-1-.45-1-1V1c0-.55.45-1 1-1h10c.55 0 1 .45 1 1zm-1 10H1v2h2v-1h3v1h5v-2zm0-10H2v9h9V1z"/></svg>
      <svg height="16" width="16" class="octicon octicon-project flex-shrink-0 js-jump-to-octicon-project d-none" title="Project" aria-label="Project" viewBox="0 0 15 16" version="1.1" role="img"><path fill-rule="evenodd" d="M10 12h3V2h-3v10zm-4-2h3V2H6v8zm-4 4h3V2H2v12zm-1 1h13V1H1v14zM14 0H1a1 1 0 00-1 1v14a1 1 0 001 1h13a1 1 0 001-1V1a1 1 0 00-1-1z"/></svg>
      <svg height="16" width="16" class="octicon octicon-search flex-shrink-0 js-jump-to-octicon-search d-none" title="Search" aria-label="Search" viewBox="0 0 16 16" version="1.1" role="img"><path fill-rule="evenodd" d="M15.7 13.3l-3.81-3.83A5.93 5.93 0 0013 6c0-3.31-2.69-6-6-6S1 2.69 1 6s2.69 6 6 6c1.3 0 2.48-.41 3.47-1.11l3.83 3.81c.19.2.45.3.7.3.25 0 .52-.09.7-.3a.996.996 0 000-1.41v.01zM7 10.7c-2.59 0-4.7-2.11-4.7-4.7 0-2.59 2.11-4.7 4.7-4.7 2.59 0 4.7 2.11 4.7 4.7 0 2.59-2.11 4.7-4.7 4.7z"/></svg>
    </div>

    <img class="avatar mr-2 flex-shrink-0 js-jump-to-suggestion-avatar d-none" alt="" aria-label="Team" src="" width="28" height="28">

    <div class="jump-to-suggestion-name js-jump-to-suggestion-name flex-auto overflow-hidden text-left no-wrap css-truncate css-truncate-target">
    </div>

    <div class="border rounded-1 flex-shrink-0 bg-gray px-1 text-gray-light ml-1 f6 d-none js-jump-to-badge-search">
      <span class="js-jump-to-badge-search-text-default d-none" aria-label="in this repository">
        In this repository
      </span>
      <span class="js-jump-to-badge-search-text-global d-none" aria-label="in all of GitHub">
        All GitHub
      </span>
      <span aria-hidden="true" class="d-inline-block ml-1 v-align-middle">↵</span>
    </div>

    <div aria-hidden="true" class="border rounded-1 flex-shrink-0 bg-gray px-1 text-gray-light ml-1 f6 d-none d-on-nav-focus js-jump-to-badge-jump">
      Jump to
      <span class="d-inline-block ml-1 v-align-middle">↵</span>
    </div>
  </a>
</li>

</ul>

<ul class="d-none js-jump-to-no-results-template-container">
  <li class="d-flex flex-justify-center flex-items-center f5 d-none js-jump-to-suggestion p-2">
    <span class="text-gray">No suggested jump to results</span>
  </li>
</ul>

<ul id="jump-to-results" role="listbox" class="p-0 m-0 js-navigation-container jump-to-suggestions-results-container js-jump-to-suggestions-results-container">
  

<li class="d-flex flex-justify-start flex-items-center p-0 f5 navigation-item js-navigation-item js-jump-to-scoped-search d-none" role="option">
  <a tabindex="-1" class="no-underline d-flex flex-auto flex-items-center jump-to-suggestions-path js-jump-to-suggestion-path js-navigation-open p-2" href="">
    <div class="jump-to-octicon js-jump-to-octicon flex-shrink-0 mr-2 text-center d-none">
      <svg height="16" width="16" class="octicon octicon-repo flex-shrink-0 js-jump-to-octicon-repo d-none" title="Repository" aria-label="Repository" viewBox="0 0 12 16" version="1.1" role="img"><path fill-rule="evenodd" d="M4 9H3V8h1v1zm0-3H3v1h1V6zm0-2H3v1h1V4zm0-2H3v1h1V2zm8-1v12c0 .55-.45 1-1 1H6v2l-1.5-1.5L3 16v-2H1c-.55 0-1-.45-1-1V1c0-.55.45-1 1-1h10c.55 0 1 .45 1 1zm-1 10H1v2h2v-1h3v1h5v-2zm0-10H2v9h9V1z"/></svg>
      <svg height="16" width="16" class="octicon octicon-project flex-shrink-0 js-jump-to-octicon-project d-none" title="Project" aria-label="Project" viewBox="0 0 15 16" version="1.1" role="img"><path fill-rule="evenodd" d="M10 12h3V2h-3v10zm-4-2h3V2H6v8zm-4 4h3V2H2v12zm-1 1h13V1H1v14zM14 0H1a1 1 0 00-1 1v14a1 1 0 001 1h13a1 1 0 001-1V1a1 1 0 00-1-1z"/></svg>
      <svg height="16" width="16" class="octicon octicon-search flex-shrink-0 js-jump-to-octicon-search d-none" title="Search" aria-label="Search" viewBox="0 0 16 16" version="1.1" role="img"><path fill-rule="evenodd" d="M15.7 13.3l-3.81-3.83A5.93 5.93 0 0013 6c0-3.31-2.69-6-6-6S1 2.69 1 6s2.69 6 6 6c1.3 0 2.48-.41 3.47-1.11l3.83 3.81c.19.2.45.3.7.3.25 0 .52-.09.7-.3a.996.996 0 000-1.41v.01zM7 10.7c-2.59 0-4.7-2.11-4.7-4.7 0-2.59 2.11-4.7 4.7-4.7 2.59 0 4.7 2.11 4.7 4.7 0 2.59-2.11 4.7-4.7 4.7z"/></svg>
    </div>

    <img class="avatar mr-2 flex-shrink-0 js-jump-to-suggestion-avatar d-none" alt="" aria-label="Team" src="" width="28" height="28">

    <div class="jump-to-suggestion-name js-jump-to-suggestion-name flex-auto overflow-hidden text-left no-wrap css-truncate css-truncate-target">
    </div>

    <div class="border rounded-1 flex-shrink-0 bg-gray px-1 text-gray-light ml-1 f6 d-none js-jump-to-badge-search">
      <span class="js-jump-to-badge-search-text-default d-none" aria-label="in this repository">
        In this repository
      </span>
      <span class="js-jump-to-badge-search-text-global d-none" aria-label="in all of GitHub">
        All GitHub
      </span>
      <span aria-hidden="true" class="d-inline-block ml-1 v-align-middle">↵</span>
    </div>

    <div aria-hidden="true" class="border rounded-1 flex-shrink-0 bg-gray px-1 text-gray-light ml-1 f6 d-none d-on-nav-focus js-jump-to-badge-jump">
      Jump to
      <span class="d-inline-block ml-1 v-align-middle">↵</span>
    </div>
  </a>
</li>

  

<li class="d-flex flex-justify-start flex-items-center p-0 f5 navigation-item js-navigation-item js-jump-to-global-search d-none" role="option">
  <a tabindex="-1" class="no-underline d-flex flex-auto flex-items-center jump-to-suggestions-path js-jump-to-suggestion-path js-navigation-open p-2" href="">
    <div class="jump-to-octicon js-jump-to-octicon flex-shrink-0 mr-2 text-center d-none">
      <svg height="16" width="16" class="octicon octicon-repo flex-shrink-0 js-jump-to-octicon-repo d-none" title="Repository" aria-label="Repository" viewBox="0 0 12 16" version="1.1" role="img"><path fill-rule="evenodd" d="M4 9H3V8h1v1zm0-3H3v1h1V6zm0-2H3v1h1V4zm0-2H3v1h1V2zm8-1v12c0 .55-.45 1-1 1H6v2l-1.5-1.5L3 16v-2H1c-.55 0-1-.45-1-1V1c0-.55.45-1 1-1h10c.55 0 1 .45 1 1zm-1 10H1v2h2v-1h3v1h5v-2zm0-10H2v9h9V1z"/></svg>
      <svg height="16" width="16" class="octicon octicon-project flex-shrink-0 js-jump-to-octicon-project d-none" title="Project" aria-label="Project" viewBox="0 0 15 16" version="1.1" role="img"><path fill-rule="evenodd" d="M10 12h3V2h-3v10zm-4-2h3V2H6v8zm-4 4h3V2H2v12zm-1 1h13V1H1v14zM14 0H1a1 1 0 00-1 1v14a1 1 0 001 1h13a1 1 0 001-1V1a1 1 0 00-1-1z"/></svg>
      <svg height="16" width="16" class="octicon octicon-search flex-shrink-0 js-jump-to-octicon-search d-none" title="Search" aria-label="Search" viewBox="0 0 16 16" version="1.1" role="img"><path fill-rule="evenodd" d="M15.7 13.3l-3.81-3.83A5.93 5.93 0 0013 6c0-3.31-2.69-6-6-6S1 2.69 1 6s2.69 6 6 6c1.3 0 2.48-.41 3.47-1.11l3.83 3.81c.19.2.45.3.7.3.25 0 .52-.09.7-.3a.996.996 0 000-1.41v.01zM7 10.7c-2.59 0-4.7-2.11-4.7-4.7 0-2.59 2.11-4.7 4.7-4.7 2.59 0 4.7 2.11 4.7 4.7 0 2.59-2.11 4.7-4.7 4.7z"/></svg>
    </div>

    <img class="avatar mr-2 flex-shrink-0 js-jump-to-suggestion-avatar d-none" alt="" aria-label="Team" src="" width="28" height="28">

    <div class="jump-to-suggestion-name js-jump-to-suggestion-name flex-auto overflow-hidden text-left no-wrap css-truncate css-truncate-target">
    </div>

    <div class="border rounded-1 flex-shrink-0 bg-gray px-1 text-gray-light ml-1 f6 d-none js-jump-to-badge-search">
      <span class="js-jump-to-badge-search-text-default d-none" aria-label="in this repository">
        In this repository
      </span>
      <span class="js-jump-to-badge-search-text-global d-none" aria-label="in all of GitHub">
        All GitHub
      </span>
      <span aria-hidden="true" class="d-inline-block ml-1 v-align-middle">↵</span>
    </div>

    <div aria-hidden="true" class="border rounded-1 flex-shrink-0 bg-gray px-1 text-gray-light ml-1 f6 d-none d-on-nav-focus js-jump-to-badge-jump">
      Jump to
      <span class="d-inline-block ml-1 v-align-middle">↵</span>
    </div>
  </a>
</li>


    <li class="d-flex flex-justify-center flex-items-center p-0 f5 js-jump-to-suggestion">
      <img src="https://github.githubassets.com/images/spinners/octocat-spinner-128.gif" alt="Octocat Spinner Icon" class="m-2" width="28">
    </li>
</ul>

            </div>
      </label>
</form>  </div>
</div>


      <nav class="d-flex flex-column flex-lg-row flex-self-stretch flex-lg-self-auto" aria-label="Global">
    <a class="Header-link d-block d-lg-none py-2 py-lg-0 border-top border-lg-top-0 border-white-fade-15" data-ga-click="Header, click, Nav menu - item:dashboard:user" aria-label="Dashboard" href="/dashboard">
      Dashboard
</a>
  <a class="js-selected-navigation-item Header-link  mr-0 mr-lg-3 py-2 py-lg-0 border-top border-lg-top-0 border-white-fade-15" data-hotkey="g p" data-ga-click="Header, click, Nav menu - item:pulls context:user" aria-label="Pull requests you created" data-selected-links="/pulls /pulls/assigned /pulls/mentioned /pulls" href="/pulls">
    Pull requests
</a>
  <a class="js-selected-navigation-item Header-link  mr-0 mr-lg-3 py-2 py-lg-0 border-top border-lg-top-0 border-white-fade-15" data-hotkey="g i" data-ga-click="Header, click, Nav menu - item:issues context:user" aria-label="Issues you created" data-selected-links="/issues /issues/assigned /issues/mentioned /issues" href="/issues">
    Issues
</a>
    <div class="mr-0 mr-lg-3 py-2 py-lg-0 border-top border-lg-top-0 border-white-fade-15">
      <a class="js-selected-navigation-item Header-link" data-ga-click="Header, click, Nav menu - item:marketplace context:user" data-octo-click="marketplace_click" data-octo-dimensions="location:nav_bar" data-selected-links=" /marketplace" href="/marketplace">
        Marketplace
</a>      

    </div>

  <a class="js-selected-navigation-item Header-link  mr-0 mr-lg-3 py-2 py-lg-0 border-top border-lg-top-0 border-white-fade-15" data-ga-click="Header, click, Nav menu - item:explore" data-selected-links="/explore /trending /trending/developers /integrations /integrations/feature/code /integrations/feature/collaborate /integrations/feature/ship showcases showcases_search showcases_landing /explore" href="/explore">
    Explore
</a>


    <a class="Header-link d-block d-lg-none mr-0 mr-lg-3 py-2 py-lg-0 border-top border-lg-top-0 border-white-fade-15" href="https://github.com/mxie220">
      <img class="avatar" height="20" width="20" alt="@mxie220" src="https://avatars1.githubusercontent.com/u/16497068?s=60&amp;v=4" />
      mxie220
</a>
    <!-- '"` --><!-- </textarea></xmp> --></option></form><form action="/logout" accept-charset="UTF-8" method="post"><input name="utf8" type="hidden" value="&#x2713;" /><input type="hidden" name="authenticity_token" value="6BTteoRzjxc/MFik5yR2O9ytwnhNsE2F13d+Op6glWguKiew5VaEeL1/Xxp/UNBW9JBvt0BlfKmYdvWNMLF18Q==" />
      <button type="submit" class="Header-link mr-0 mr-lg-3 py-2 py-lg-0 border-top border-lg-top-0 border-white-fade-15 d-lg-none btn-link d-block width-full text-left" data-ga-click="Header, sign out, icon:logout" style="padding-left: 2px;">
        <svg class="octicon octicon-sign-out v-align-middle" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M12 9V7H8V5h4V3l4 3-4 3zm-2 3H6V3L2 1h8v3h1V1c0-.55-.45-1-1-1H1C.45 0 0 .45 0 1v11.38c0 .39.22.73.55.91L6 16.01V13h4c.55 0 1-.45 1-1V8h-1v4z"/></svg>
        Sign out
      </button>
</form></nav>

    </div>

    <div class="Header-item Header-item--full flex-justify-center d-lg-none position-relative">
      <div class="css-truncate css-truncate-target width-fit position-absolute left-0 right-0 text-center">
              <svg class="octicon octicon-repo" viewBox="0 0 12 16" version="1.1" width="12" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9H3V8h1v1zm0-3H3v1h1V6zm0-2H3v1h1V4zm0-2H3v1h1V2zm8-1v12c0 .55-.45 1-1 1H6v2l-1.5-1.5L3 16v-2H1c-.55 0-1-.45-1-1V1c0-.55.45-1 1-1h10c.55 0 1 .45 1 1zm-1 10H1v2h2v-1h3v1h5v-2zm0-10H2v9h9V1z"/></svg>
    <a class="Header-link" href="/microsoft">microsoft</a>
    /
    <a class="Header-link" href="/microsoft/MCW-Modern-cloud-apps">MCW-Modern-cloud-apps</a>

</div>
    </div>


    <div class="Header-item mr-0 mr-lg-3 flex-order-1 flex-lg-order-none">
      

    <a aria-label="You have no unread notifications" class="Header-link notification-indicator position-relative tooltipped tooltipped-sw js-socket-channel js-notification-indicator" data-hotkey="g n" data-ga-click="Header, go to notifications, icon:read" data-channel="notification-changed:16497068" href="/notifications">
        <span class="mail-status "></span>
        <svg class="octicon octicon-bell" viewBox="0 0 14 16" version="1.1" width="14" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M14 12v1H0v-1l.73-.58c.77-.77.81-2.55 1.19-4.42C2.69 3.23 6 2 6 2c0-.55.45-1 1-1s1 .45 1 1c0 0 3.39 1.23 4.16 5 .38 1.88.42 3.66 1.19 4.42l.66.58H14zm-7 4c1.11 0 2-.89 2-2H5c0 1.11.89 2 2 2z"/></svg>
</a>
    </div>


    <div class="Header-item position-relative d-none d-lg-flex">
      <details class="details-overlay details-reset">
  <summary class="Header-link"
      aria-label="Create new…"
      data-ga-click="Header, create new, icon:add">
    <svg class="octicon octicon-plus" viewBox="0 0 12 16" version="1.1" width="12" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M12 9H7v5H5V9H0V7h5V2h2v5h5v2z"/></svg> <span class="dropdown-caret"></span>
  </summary>
  <details-menu class="dropdown-menu dropdown-menu-sw">
    
<a role="menuitem" class="dropdown-item" href="/new" data-ga-click="Header, create new repository">
  New repository
</a>

  <a role="menuitem" class="dropdown-item" href="/new/import" data-ga-click="Header, import a repository">
    Import repository
  </a>

<a role="menuitem" class="dropdown-item" href="https://gist.github.com/" data-ga-click="Header, create new gist">
  New gist
</a>

  <a role="menuitem" class="dropdown-item" href="/organizations/new" data-ga-click="Header, create new organization">
    New organization
  </a>


  <div role="none" class="dropdown-divider"></div>
  <div class="dropdown-header">
    <span title="microsoft/MCW-Modern-cloud-apps">This repository</span>
  </div>
    <a role="menuitem" class="dropdown-item" href="/microsoft/MCW-Modern-cloud-apps/issues/new" data-ga-click="Header, create new issue" data-skip-pjax>
      New issue
    </a>


  </details-menu>
</details>

    </div>

    <div class="Header-item position-relative mr-0 d-none d-lg-flex">
      
  <details class="details-overlay details-reset js-feature-preview-indicator-container" data-feature-preview-indicator-src="/users/mxie220/feature_preview/indicator_check.json">

  <summary class="Header-link"
    aria-label="View profile and more"
    data-ga-click="Header, show menu, icon:avatar">
    <img alt="@mxie220" class="avatar" src="https://avatars2.githubusercontent.com/u/16497068?s=40&amp;v=4" height="20" width="20">
      <span class="feature-preview-indicator js-feature-preview-indicator" hidden></span>
    <span class="dropdown-caret"></span>
  </summary>
  <details-menu class="dropdown-menu dropdown-menu-sw mt-2" style="width: 180px">
    <div class="header-nav-current-user css-truncate"><a role="menuitem" class="no-underline user-profile-link px-3 pt-2 pb-2 mb-n2 mt-n1 d-block" href="/mxie220" data-ga-click="Header, go to profile, text:Signed in as">Signed in as <strong class="css-truncate-target">mxie220</strong></a></div>
    <div role="none" class="dropdown-divider"></div>

      <div class="pl-3 pr-3 f6 user-status-container js-user-status-context pb-1" data-url="/users/status?compact=1&amp;link_mentions=0&amp;truncate=1">
        
<div class="js-user-status-container
    user-status-compact rounded-1 px-2 py-1 mt-2
    border
  " data-team-hovercards-enabled>
  <details class="js-user-status-details details-reset details-overlay details-overlay-dark">
    <summary class="btn-link btn-block link-gray no-underline js-toggle-user-status-edit toggle-user-status-edit "
      role="menuitem" data-hydro-click="{&quot;event_type&quot;:&quot;user_profile.click&quot;,&quot;payload&quot;:{&quot;profile_user_id&quot;:6154722,&quot;target&quot;:&quot;EDIT_USER_STATUS&quot;,&quot;user_id&quot;:16497068,&quot;client_id&quot;:&quot;600662594.1564444661&quot;,&quot;originating_request_id&quot;:&quot;72E4:6BE8:790269:B95DD5:5DE09FE1&quot;,&quot;originating_url&quot;:&quot;https://github.com/microsoft/MCW-Modern-cloud-apps/blob/master/Whiteboard%20design%20session/WDS%20trainer%20guide%20-%20Modern%20cloud%20apps.md&quot;,&quot;referrer&quot;:&quot;https://github.com/microsoft/MCW-Modern-cloud-apps/tree/master/Whiteboard%20design%20session&quot;}}" data-hydro-click-hmac="87c525a8b05eb2b5f22072d2b64ad85cf1d55d6e71ee0d0068088f019e85a4c9">
      <div class="d-flex">
        <div class="f6 lh-condensed user-status-header
          d-inline-block v-align-middle
            user-status-emoji-only-header circle
            pr-2
"
            style="max-width: 29px"
          >
          <div class="user-status-emoji-container flex-shrink-0 mr-1 mt-1 lh-condensed-ultra v-align-bottom" style="">
            <svg class="octicon octicon-smiley" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M8 0C3.58 0 0 3.58 0 8s3.58 8 8 8 8-3.58 8-8-3.58-8-8-8zm4.81 12.81a6.72 6.72 0 01-2.17 1.45c-.83.36-1.72.53-2.64.53-.92 0-1.81-.17-2.64-.53-.81-.34-1.55-.83-2.17-1.45a6.773 6.773 0 01-1.45-2.17A6.59 6.59 0 011.21 8c0-.92.17-1.81.53-2.64.34-.81.83-1.55 1.45-2.17.62-.62 1.36-1.11 2.17-1.45A6.59 6.59 0 018 1.21c.92 0 1.81.17 2.64.53.81.34 1.55.83 2.17 1.45.62.62 1.11 1.36 1.45 2.17.36.83.53 1.72.53 2.64 0 .92-.17 1.81-.53 2.64-.34.81-.83 1.55-1.45 2.17zM4 6.8v-.59c0-.66.53-1.19 1.2-1.19h.59c.66 0 1.19.53 1.19 1.19v.59c0 .67-.53 1.2-1.19 1.2H5.2C4.53 8 4 7.47 4 6.8zm5 0v-.59c0-.66.53-1.19 1.2-1.19h.59c.66 0 1.19.53 1.19 1.19v.59c0 .67-.53 1.2-1.19 1.2h-.59C9.53 8 9 7.47 9 6.8zm4 3.2c-.72 1.88-2.91 3-5 3s-4.28-1.13-5-3c-.14-.39.23-1 .66-1h8.59c.41 0 .89.61.75 1z"/></svg>
          </div>
        </div>
        <div class="
          d-inline-block v-align-middle
          
          
           css-truncate css-truncate-target 
           user-status-message-wrapper f6"
           style="line-height: 20px;" >
          <div class="d-inline-block text-gray-dark v-align-text-top text-left">
              <span class="text-gray ml-2">Set status</span>
          </div>
        </div>
      </div>
    </summary>
    <details-dialog class="details-dialog rounded-1 anim-fade-in fast Box Box--overlay" role="dialog" tabindex="-1">
      <!-- '"` --><!-- </textarea></xmp> --></option></form><form class="position-relative flex-auto js-user-status-form" action="/users/status?compact=1&amp;link_mentions=0&amp;truncate=1" accept-charset="UTF-8" method="post"><input name="utf8" type="hidden" value="&#x2713;" /><input type="hidden" name="_method" value="put" /><input type="hidden" name="authenticity_token" value="F+zzNEUq5KyOPP90NvxQthcnQFATAPEwgi9pIZKVjT+XAHs/fEdAazBZ1dhIKKi6hsvbMBd7C3jbGdC0Y3wgxg==" />
        <div class="Box-header bg-gray border-bottom p-3">
          <button class="Box-btn-octicon js-toggle-user-status-edit btn-octicon float-right" type="reset" aria-label="Close dialog" data-close-dialog>
            <svg class="octicon octicon-x" viewBox="0 0 12 16" version="1.1" width="12" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.48 8l3.75 3.75-1.48 1.48L6 9.48l-3.75 3.75-1.48-1.48L4.52 8 .77 4.25l1.48-1.48L6 6.52l3.75-3.75 1.48 1.48L7.48 8z"/></svg>
          </button>
          <h3 class="Box-title f5 text-bold text-gray-dark">Edit status</h3>
        </div>
        <input type="hidden" name="emoji" class="js-user-status-emoji-field" value="">
        <input type="hidden" name="organization_id" class="js-user-status-org-id-field" value="">
        <div class="px-3 py-2 text-gray-dark">
          <div class="js-characters-remaining-container position-relative mt-2">
            <div class="input-group d-table form-group my-0 js-user-status-form-group">
              <span class="input-group-button d-table-cell v-align-middle" style="width: 1%">
                <button type="button" aria-label="Choose an emoji" class="btn-outline btn js-toggle-user-status-emoji-picker btn-open-emoji-picker p-0">
                  <span class="js-user-status-original-emoji" hidden></span>
                  <span class="js-user-status-custom-emoji"></span>
                  <span class="js-user-status-no-emoji-icon" >
                    <svg class="octicon octicon-smiley" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M8 0C3.58 0 0 3.58 0 8s3.58 8 8 8 8-3.58 8-8-3.58-8-8-8zm4.81 12.81a6.72 6.72 0 01-2.17 1.45c-.83.36-1.72.53-2.64.53-.92 0-1.81-.17-2.64-.53-.81-.34-1.55-.83-2.17-1.45a6.773 6.773 0 01-1.45-2.17A6.59 6.59 0 011.21 8c0-.92.17-1.81.53-2.64.34-.81.83-1.55 1.45-2.17.62-.62 1.36-1.11 2.17-1.45A6.59 6.59 0 018 1.21c.92 0 1.81.17 2.64.53.81.34 1.55.83 2.17 1.45.62.62 1.11 1.36 1.45 2.17.36.83.53 1.72.53 2.64 0 .92-.17 1.81-.53 2.64-.34.81-.83 1.55-1.45 2.17zM4 6.8v-.59c0-.66.53-1.19 1.2-1.19h.59c.66 0 1.19.53 1.19 1.19v.59c0 .67-.53 1.2-1.19 1.2H5.2C4.53 8 4 7.47 4 6.8zm5 0v-.59c0-.66.53-1.19 1.2-1.19h.59c.66 0 1.19.53 1.19 1.19v.59c0 .67-.53 1.2-1.19 1.2h-.59C9.53 8 9 7.47 9 6.8zm4 3.2c-.72 1.88-2.91 3-5 3s-4.28-1.13-5-3c-.14-.39.23-1 .66-1h8.59c.41 0 .89.61.75 1z"/></svg>
                  </span>
                </button>
              </span>
              <text-expander keys=": @" data-mention-url="/autocomplete/user-suggestions" data-emoji-url="/autocomplete/emoji">
                <input
                  type="text"
                  autocomplete="off"
                  data-no-org-url="/autocomplete/user-suggestions"
                  data-org-url="/suggestions?mention_suggester=1"
                  data-maxlength="80"
                  class="d-table-cell width-full form-control js-user-status-message-field js-characters-remaining-field"
                  placeholder="What's happening?"
                  name="message"
                  value=""
                  aria-label="What is your current status?">
              </text-expander>
              <div class="error">Could not update your status, please try again.</div>
            </div>
            <div style="margin-left: 53px" class="my-1 text-small label-characters-remaining js-characters-remaining" data-suffix="remaining" hidden>
              80 remaining
            </div>
          </div>
          <include-fragment class="js-user-status-emoji-picker" data-url="/users/status/emoji"></include-fragment>
          <div class="overflow-auto ml-n3 mr-n3 px-3 border-bottom" style="max-height: 33vh">
            <div class="user-status-suggestions js-user-status-suggestions collapsed overflow-hidden">
              <h4 class="f6 text-normal my-3">Suggestions:</h4>
              <div class="mx-3 mt-2 clearfix">
                  <div class="float-left col-6">
                      <button type="button" value=":palm_tree:" class="d-flex flex-items-baseline flex-items-stretch lh-condensed f6 btn-link link-gray no-underline js-predefined-user-status mb-1">
                        <div class="emoji-status-width mr-2 v-align-middle js-predefined-user-status-emoji">
                          <g-emoji alias="palm_tree" fallback-src="https://github.githubassets.com/images/icons/emoji/unicode/1f334.png">🌴</g-emoji>
                        </div>
                        <div class="d-flex flex-items-center no-underline js-predefined-user-status-message ws-normal text-left" style="border-left: 1px solid transparent">
                          On vacation
                        </div>
                      </button>
                      <button type="button" value=":face_with_thermometer:" class="d-flex flex-items-baseline flex-items-stretch lh-condensed f6 btn-link link-gray no-underline js-predefined-user-status mb-1">
                        <div class="emoji-status-width mr-2 v-align-middle js-predefined-user-status-emoji">
                          <g-emoji alias="face_with_thermometer" fallback-src="https://github.githubassets.com/images/icons/emoji/unicode/1f912.png">🤒</g-emoji>
                        </div>
                        <div class="d-flex flex-items-center no-underline js-predefined-user-status-message ws-normal text-left" style="border-left: 1px solid transparent">
                          Out sick
                        </div>
                      </button>
                  </div>
                  <div class="float-left col-6">
                      <button type="button" value=":house:" class="d-flex flex-items-baseline flex-items-stretch lh-condensed f6 btn-link link-gray no-underline js-predefined-user-status mb-1">
                        <div class="emoji-status-width mr-2 v-align-middle js-predefined-user-status-emoji">
                          <g-emoji alias="house" fallback-src="https://github.githubassets.com/images/icons/emoji/unicode/1f3e0.png">🏠</g-emoji>
                        </div>
                        <div class="d-flex flex-items-center no-underline js-predefined-user-status-message ws-normal text-left" style="border-left: 1px solid transparent">
                          Working from home
                        </div>
                      </button>
                      <button type="button" value=":dart:" class="d-flex flex-items-baseline flex-items-stretch lh-condensed f6 btn-link link-gray no-underline js-predefined-user-status mb-1">
                        <div class="emoji-status-width mr-2 v-align-middle js-predefined-user-status-emoji">
                          <g-emoji alias="dart" fallback-src="https://github.githubassets.com/images/icons/emoji/unicode/1f3af.png">🎯</g-emoji>
                        </div>
                        <div class="d-flex flex-items-center no-underline js-predefined-user-status-message ws-normal text-left" style="border-left: 1px solid transparent">
                          Focusing
                        </div>
                      </button>
                  </div>
              </div>
            </div>
            <div class="user-status-limited-availability-container">
              <div class="form-checkbox my-0">
                <input type="checkbox" name="limited_availability" value="1" class="js-user-status-limited-availability-checkbox" data-default-message="I may be slow to respond." aria-describedby="limited-availability-help-text-truncate-true-compact-true" id="limited-availability-truncate-true-compact-true">
                <label class="d-block f5 text-gray-dark mb-1" for="limited-availability-truncate-true-compact-true">
                  Busy
                </label>
                <p class="note" id="limited-availability-help-text-truncate-true-compact-true">
                  When others mention you, assign you, or request your review,
                  GitHub will let them know that you have limited availability.
                </p>
              </div>
            </div>
          </div>
            

<div class="d-inline-block f5 mr-2 pt-3 pb-2" >
  <div class="d-inline-block mr-1">
    Clear status
  </div>

  <details class="js-user-status-expire-drop-down f6 dropdown details-reset details-overlay d-inline-block mr-2">
    <summary class="f5 btn-link link-gray-dark border px-2 py-1 rounded-1" aria-haspopup="true">
      <div class="js-user-status-expiration-interval-selected d-inline-block v-align-baseline">
        Never
      </div>
      <div class="dropdown-caret"></div>
    </summary>

    <ul class="dropdown-menu dropdown-menu-se pl-0 overflow-auto" style="width: 220px; max-height: 15.5em">
      <li>
        <button type="button" class="btn-link dropdown-item js-user-status-expire-button ws-normal" title="Never">
          <span class="d-inline-block text-bold mb-1">Never</span>
          <div class="f6 lh-condensed">Keep this status until you clear your status or edit your status.</div>
        </button>
      </li>
      <li class="dropdown-divider" role="none"></li>
        <li>
          <button type="button" class="btn-link dropdown-item ws-normal js-user-status-expire-button" title="in 30 minutes" value="2019-11-29T16:05:12+11:00">
            in 30 minutes
          </button>
        </li>
        <li>
          <button type="button" class="btn-link dropdown-item ws-normal js-user-status-expire-button" title="in 1 hour" value="2019-11-29T16:35:12+11:00">
            in 1 hour
          </button>
        </li>
        <li>
          <button type="button" class="btn-link dropdown-item ws-normal js-user-status-expire-button" title="in 4 hours" value="2019-11-29T19:35:12+11:00">
            in 4 hours
          </button>
        </li>
        <li>
          <button type="button" class="btn-link dropdown-item ws-normal js-user-status-expire-button" title="today" value="2019-11-29T23:59:59+11:00">
            today
          </button>
        </li>
        <li>
          <button type="button" class="btn-link dropdown-item ws-normal js-user-status-expire-button" title="this week" value="2019-12-01T23:59:59+11:00">
            this week
          </button>
        </li>
    </ul>
  </details>
  <input class="js-user-status-expiration-date-input" type="hidden" name="expires_at" value="">
</div>

          <include-fragment class="js-user-status-org-picker" data-url="/users/status/organizations"></include-fragment>
        </div>
        <div class="d-flex flex-items-center flex-justify-between p-3 border-top">
          <button type="submit" disabled class="width-full btn btn-primary mr-2 js-user-status-submit">
            Set status
          </button>
          <button type="button" disabled class="width-full js-clear-user-status-button btn ml-2 ">
            Clear status
          </button>
        </div>
</form>    </details-dialog>
  </details>
</div>

      </div>
      <div role="none" class="dropdown-divider"></div>


    <a role="menuitem" class="dropdown-item" href="/mxie220" data-ga-click="Header, go to profile, text:your profile">Your profile</a>

    <a role="menuitem" class="dropdown-item" href="/mxie220?tab=repositories" data-ga-click="Header, go to repositories, text:your repositories">Your repositories</a>

    <a role="menuitem" class="dropdown-item" href="/mxie220?tab=projects" data-ga-click="Header, go to projects, text:your projects">Your projects</a>

    <a role="menuitem" class="dropdown-item" href="/mxie220?tab=stars" data-ga-click="Header, go to starred repos, text:your stars">Your stars</a>
      <a role="menuitem" class="dropdown-item" href="https://gist.github.com/mine" data-ga-click="Header, your gists, text:your gists">Your gists</a>





    <div role="none" class="dropdown-divider"></div>
      
<div id="feature-enrollment-toggle" class="hide-sm hide-md feature-preview-details position-relative">
  <button
    type="button"
    class="dropdown-item btn-link"
    role="menuitem"
    data-feature-preview-trigger-url="/users/mxie220/feature_previews"
    data-feature-preview-close-details="{&quot;event_type&quot;:&quot;feature_preview.clicks.close_modal&quot;,&quot;payload&quot;:{&quot;client_id&quot;:&quot;600662594.1564444661&quot;,&quot;originating_request_id&quot;:&quot;72E4:6BE8:790269:B95DD5:5DE09FE1&quot;,&quot;originating_url&quot;:&quot;https://github.com/microsoft/MCW-Modern-cloud-apps/blob/master/Whiteboard%20design%20session/WDS%20trainer%20guide%20-%20Modern%20cloud%20apps.md&quot;,&quot;referrer&quot;:&quot;https://github.com/microsoft/MCW-Modern-cloud-apps/tree/master/Whiteboard%20design%20session&quot;,&quot;user_id&quot;:16497068}}"
    data-feature-preview-close-hmac="5ef9d9fd123ec30f09e23434ae8de05d359f5a1694a99f28e5ec4377c91457a3"
    data-hydro-click="{&quot;event_type&quot;:&quot;feature_preview.clicks.open_modal&quot;,&quot;payload&quot;:{&quot;link_location&quot;:&quot;user_dropdown&quot;,&quot;client_id&quot;:&quot;600662594.1564444661&quot;,&quot;originating_request_id&quot;:&quot;72E4:6BE8:790269:B95DD5:5DE09FE1&quot;,&quot;originating_url&quot;:&quot;https://github.com/microsoft/MCW-Modern-cloud-apps/blob/master/Whiteboard%20design%20session/WDS%20trainer%20guide%20-%20Modern%20cloud%20apps.md&quot;,&quot;referrer&quot;:&quot;https://github.com/microsoft/MCW-Modern-cloud-apps/tree/master/Whiteboard%20design%20session&quot;,&quot;user_id&quot;:16497068}}"
    data-hydro-click-hmac="b58cdff0cdd692c5d03ec064e1f253b92a69cbe96046becb3fc95b7fdecb0dd4"
  >
    Feature preview
  </button>
    <span class="feature-preview-indicator js-feature-preview-indicator" hidden></span>
</div>

    <a role="menuitem" class="dropdown-item" href="https://help.github.com" data-ga-click="Header, go to help, text:help">Help</a>
    <a role="menuitem" class="dropdown-item" href="/settings/profile" data-ga-click="Header, go to settings, icon:settings">Settings</a>
    <!-- '"` --><!-- </textarea></xmp> --></option></form><form class="logout-form" action="/logout" accept-charset="UTF-8" method="post"><input name="utf8" type="hidden" value="&#x2713;" /><input type="hidden" name="authenticity_token" value="HxccouvFEConAJp6c2dXK6CroAgF29URKvhiG6JTUPXZKdZoiuAbRaVPncTrE/FGiJYNxwgO5D1l+emsDEKwbA==" />
      
      <button type="submit" class="dropdown-item dropdown-signout" data-ga-click="Header, sign out, icon:logout" role="menuitem">
        Sign out
      </button>
</form>  </details-menu>
</details>

    </div>

  </header>

      

  </div>

  <div id="start-of-content" class="show-on-focus"></div>


    <div id="js-flash-container">

</div>



  <div class="application-main " data-commit-hovercards-enabled>
        <div itemscope itemtype="http://schema.org/SoftwareSourceCode" class="">
    <main  >
      


  



  









  <div class=" pagehead repohead instapaper_ignore readability-menu experiment-repo-nav pt-0 pt-lg-4 ">
    <div class="repohead-details-container clearfix container-lg p-responsive d-none d-lg-block">

      <ul class="pagehead-actions">




  <li>
    
    <!-- '"` --><!-- </textarea></xmp> --></option></form><form data-remote="true" class="clearfix js-social-form js-social-container" action="/notifications/subscribe" accept-charset="UTF-8" method="post"><input name="utf8" type="hidden" value="&#x2713;" /><input type="hidden" name="authenticity_token" value="4+8ipT7AMKYPKEOPZiRti9pBaxscXBE3Lpm+fvDGRsy53d1KtwTpv0IeFjMxGZl59BB5T9zc4iRczc9O8KjsfA==" />      <input type="hidden" name="repository_id" value="122681898">

      <details class="details-reset details-overlay select-menu float-left">
        <summary class="select-menu-button float-left btn btn-sm btn-with-count" data-hydro-click="{&quot;event_type&quot;:&quot;repository.click&quot;,&quot;payload&quot;:{&quot;target&quot;:&quot;WATCH_BUTTON&quot;,&quot;repository_id&quot;:122681898,&quot;client_id&quot;:&quot;600662594.1564444661&quot;,&quot;originating_request_id&quot;:&quot;72E4:6BE8:790269:B95DD5:5DE09FE1&quot;,&quot;originating_url&quot;:&quot;https://github.com/microsoft/MCW-Modern-cloud-apps/blob/master/Whiteboard%20design%20session/WDS%20trainer%20guide%20-%20Modern%20cloud%20apps.md&quot;,&quot;referrer&quot;:&quot;https://github.com/microsoft/MCW-Modern-cloud-apps/tree/master/Whiteboard%20design%20session&quot;,&quot;user_id&quot;:16497068}}" data-hydro-click-hmac="471c31ff6b17d8e47c9676d2ac95fd12350ade94092ad685ed7018e43674f510" data-ga-click="Repository, click Watch settings, action:blob#show">          <span data-menu-button>
              <svg class="octicon octicon-eye v-align-text-bottom" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M8.06 2C3 2 0 8 0 8s3 6 8.06 6C13 14 16 8 16 8s-3-6-7.94-6zM8 12c-2.2 0-4-1.78-4-4 0-2.2 1.8-4 4-4 2.22 0 4 1.8 4 4 0 2.22-1.78 4-4 4zm2-4c0 1.11-.89 2-2 2-1.11 0-2-.89-2-2 0-1.11.89-2 2-2 1.11 0 2 .89 2 2z"/></svg>
              Watch
          </span>
</summary>        <details-menu
          class="select-menu-modal position-absolute mt-5"
          style="z-index: 99;">
          <div class="select-menu-header">
            <span class="select-menu-title">Notifications</span>
          </div>
          <div class="select-menu-list">
            <button type="submit" name="do" value="included" class="select-menu-item width-full" aria-checked="true" role="menuitemradio">
              <svg class="octicon octicon-check select-menu-item-icon" viewBox="0 0 12 16" version="1.1" width="12" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5L12 5z"/></svg>
              <div class="select-menu-item-text">
                <span class="select-menu-item-heading">Not watching</span>
                <span class="description">Be notified only when participating or @mentioned.</span>
                <span class="hidden-select-button-text" data-menu-button-contents>
                  <svg class="octicon octicon-eye v-align-text-bottom" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M8.06 2C3 2 0 8 0 8s3 6 8.06 6C13 14 16 8 16 8s-3-6-7.94-6zM8 12c-2.2 0-4-1.78-4-4 0-2.2 1.8-4 4-4 2.22 0 4 1.8 4 4 0 2.22-1.78 4-4 4zm2-4c0 1.11-.89 2-2 2-1.11 0-2-.89-2-2 0-1.11.89-2 2-2 1.11 0 2 .89 2 2z"/></svg>
                  Watch
                </span>
              </div>
            </button>

            <button type="submit" name="do" value="release_only" class="select-menu-item width-full" aria-checked="false" role="menuitemradio">
              <svg class="octicon octicon-check select-menu-item-icon" viewBox="0 0 12 16" version="1.1" width="12" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5L12 5z"/></svg>
              <div class="select-menu-item-text">
                <span class="select-menu-item-heading">Releases only</span>
                <span class="description">Be notified of new releases, and when participating or @mentioned.</span>
                <span class="hidden-select-button-text" data-menu-button-contents>
                  <svg class="octicon octicon-eye v-align-text-bottom" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M8.06 2C3 2 0 8 0 8s3 6 8.06 6C13 14 16 8 16 8s-3-6-7.94-6zM8 12c-2.2 0-4-1.78-4-4 0-2.2 1.8-4 4-4 2.22 0 4 1.8 4 4 0 2.22-1.78 4-4 4zm2-4c0 1.11-.89 2-2 2-1.11 0-2-.89-2-2 0-1.11.89-2 2-2 1.11 0 2 .89 2 2z"/></svg>
                  Unwatch releases
                </span>
              </div>
            </button>

            <button type="submit" name="do" value="subscribed" class="select-menu-item width-full" aria-checked="false" role="menuitemradio">
              <svg class="octicon octicon-check select-menu-item-icon" viewBox="0 0 12 16" version="1.1" width="12" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5L12 5z"/></svg>
              <div class="select-menu-item-text">
                <span class="select-menu-item-heading">Watching</span>
                <span class="description">Be notified of all conversations.</span>
                <span class="hidden-select-button-text" data-menu-button-contents>
                  <svg class="octicon octicon-eye v-align-text-bottom" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M8.06 2C3 2 0 8 0 8s3 6 8.06 6C13 14 16 8 16 8s-3-6-7.94-6zM8 12c-2.2 0-4-1.78-4-4 0-2.2 1.8-4 4-4 2.22 0 4 1.8 4 4 0 2.22-1.78 4-4 4zm2-4c0 1.11-.89 2-2 2-1.11 0-2-.89-2-2 0-1.11.89-2 2-2 1.11 0 2 .89 2 2z"/></svg>
                  Unwatch
                </span>
              </div>
            </button>

            <button type="submit" name="do" value="ignore" class="select-menu-item width-full" aria-checked="false" role="menuitemradio">
              <svg class="octicon octicon-check select-menu-item-icon" viewBox="0 0 12 16" version="1.1" width="12" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5L12 5z"/></svg>
              <div class="select-menu-item-text">
                <span class="select-menu-item-heading">Ignoring</span>
                <span class="description">Never be notified.</span>
                <span class="hidden-select-button-text" data-menu-button-contents>
                  <svg class="octicon octicon-mute v-align-text-bottom" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M8 2.81v10.38c0 .67-.81 1-1.28.53L3 10H1c-.55 0-1-.45-1-1V7c0-.55.45-1 1-1h2l3.72-3.72C7.19 1.81 8 2.14 8 2.81zm7.53 3.22l-1.06-1.06-1.97 1.97-1.97-1.97-1.06 1.06L11.44 8 9.47 9.97l1.06 1.06 1.97-1.97 1.97 1.97 1.06-1.06L13.56 8l1.97-1.97z"/></svg>
                  Stop ignoring
                </span>
              </div>
            </button>
          </div>
        </details-menu>
      </details>
        <a class="social-count js-social-count"
          href="/microsoft/MCW-Modern-cloud-apps/watchers"
          aria-label="79 users are watching this repository">
          79
        </a>
</form>
  </li>

  <li>
      <div class="js-toggler-container js-social-container starring-container ">
    <!-- '"` --><!-- </textarea></xmp> --></option></form><form class="starred js-social-form" action="/microsoft/MCW-Modern-cloud-apps/unstar" accept-charset="UTF-8" method="post"><input name="utf8" type="hidden" value="&#x2713;" /><input type="hidden" name="authenticity_token" value="rLaR9BJxWzgEOI66zjVvUH0aTXOwNMu+YLsURLHwFjkL4WnTeuMlSB7mSQqxGM3G0T7b19t4WoNV8bFiKjySuQ==" />
      <input type="hidden" name="context" value="repository"></input>
      <button type="submit" class="btn btn-sm btn-with-count js-toggler-target" aria-label="Unstar this repository" title="Unstar microsoft/MCW-Modern-cloud-apps" data-hydro-click="{&quot;event_type&quot;:&quot;repository.click&quot;,&quot;payload&quot;:{&quot;target&quot;:&quot;UNSTAR_BUTTON&quot;,&quot;repository_id&quot;:122681898,&quot;client_id&quot;:&quot;600662594.1564444661&quot;,&quot;originating_request_id&quot;:&quot;72E4:6BE8:790269:B95DD5:5DE09FE1&quot;,&quot;originating_url&quot;:&quot;https://github.com/microsoft/MCW-Modern-cloud-apps/blob/master/Whiteboard%20design%20session/WDS%20trainer%20guide%20-%20Modern%20cloud%20apps.md&quot;,&quot;referrer&quot;:&quot;https://github.com/microsoft/MCW-Modern-cloud-apps/tree/master/Whiteboard%20design%20session&quot;,&quot;user_id&quot;:16497068}}" data-hydro-click-hmac="85b8b6f966f5b5dd45eb1b2f6cd77349cbfe4f7938d948afebc55d2c51e2b20e" data-ga-click="Repository, click unstar button, action:blob#show; text:Unstar">        <svg class="octicon octicon-star v-align-text-bottom" viewBox="0 0 14 16" version="1.1" width="14" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M14 6l-4.9-.64L7 1 4.9 5.36 0 6l3.6 3.26L2.67 14 7 11.67 11.33 14l-.93-4.74L14 6z"/></svg>
        Unstar
</button>        <a class="social-count js-social-count" href="/microsoft/MCW-Modern-cloud-apps/stargazers"
           aria-label="33 users starred this repository">
           33
        </a>
</form>
    <!-- '"` --><!-- </textarea></xmp> --></option></form><form class="unstarred js-social-form" action="/microsoft/MCW-Modern-cloud-apps/star" accept-charset="UTF-8" method="post"><input name="utf8" type="hidden" value="&#x2713;" /><input type="hidden" name="authenticity_token" value="1HHGeEFpty1WU/XdJrfXOoLB03bA6IXYI7Ax/ZPFpIG2XYpxJU5F9Zt/x6+tSI5Zz22ryTDCDb6yOlG8CDdUlQ==" />
      <input type="hidden" name="context" value="repository"></input>
      <button type="submit" class="btn btn-sm btn-with-count js-toggler-target" aria-label="Unstar this repository" title="Star microsoft/MCW-Modern-cloud-apps" data-hydro-click="{&quot;event_type&quot;:&quot;repository.click&quot;,&quot;payload&quot;:{&quot;target&quot;:&quot;STAR_BUTTON&quot;,&quot;repository_id&quot;:122681898,&quot;client_id&quot;:&quot;600662594.1564444661&quot;,&quot;originating_request_id&quot;:&quot;72E4:6BE8:790269:B95DD5:5DE09FE1&quot;,&quot;originating_url&quot;:&quot;https://github.com/microsoft/MCW-Modern-cloud-apps/blob/master/Whiteboard%20design%20session/WDS%20trainer%20guide%20-%20Modern%20cloud%20apps.md&quot;,&quot;referrer&quot;:&quot;https://github.com/microsoft/MCW-Modern-cloud-apps/tree/master/Whiteboard%20design%20session&quot;,&quot;user_id&quot;:16497068}}" data-hydro-click-hmac="37ad546ee008345591e17ac4b5f893f18208ab028399ddc8a96affc7d42bc375" data-ga-click="Repository, click star button, action:blob#show; text:Star">        <svg class="octicon octicon-star v-align-text-bottom" viewBox="0 0 14 16" version="1.1" width="14" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M14 6l-4.9-.64L7 1 4.9 5.36 0 6l3.6 3.26L2.67 14 7 11.67 11.33 14l-.93-4.74L14 6z"/></svg>
        Star
</button>        <a class="social-count js-social-count" href="/microsoft/MCW-Modern-cloud-apps/stargazers"
           aria-label="33 users starred this repository">
          33
        </a>
</form>  </div>

  </li>

  <li>
          <details class="details-reset details-overlay details-overlay-dark d-inline-block float-left">
            <summary class="btn btn-sm btn-with-count" data-hydro-click="{&quot;event_type&quot;:&quot;repository.click&quot;,&quot;payload&quot;:{&quot;target&quot;:&quot;FORK_BUTTON&quot;,&quot;repository_id&quot;:122681898,&quot;client_id&quot;:&quot;600662594.1564444661&quot;,&quot;originating_request_id&quot;:&quot;72E4:6BE8:790269:B95DD5:5DE09FE1&quot;,&quot;originating_url&quot;:&quot;https://github.com/microsoft/MCW-Modern-cloud-apps/blob/master/Whiteboard%20design%20session/WDS%20trainer%20guide%20-%20Modern%20cloud%20apps.md&quot;,&quot;referrer&quot;:&quot;https://github.com/microsoft/MCW-Modern-cloud-apps/tree/master/Whiteboard%20design%20session&quot;,&quot;user_id&quot;:16497068}}" data-hydro-click-hmac="b76e94c6664973eb19bafe73a75680bdfd069476e49a0f7347d8869a4e23ff67" data-ga-click="Repository, show fork modal, action:blob#show; text:Fork" title="Fork your own copy of microsoft/MCW-Modern-cloud-apps to your account">              <svg class="octicon octicon-repo-forked v-align-text-bottom" viewBox="0 0 10 16" version="1.1" width="10" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M8 1a1.993 1.993 0 00-1 3.72V6L5 8 3 6V4.72A1.993 1.993 0 002 1a1.993 1.993 0 00-1 3.72V6.5l3 3v1.78A1.993 1.993 0 005 15a1.993 1.993 0 001-3.72V9.5l3-3V4.72A1.993 1.993 0 008 1zM2 4.2C1.34 4.2.8 3.65.8 3c0-.65.55-1.2 1.2-1.2.65 0 1.2.55 1.2 1.2 0 .65-.55 1.2-1.2 1.2zm3 10c-.66 0-1.2-.55-1.2-1.2 0-.65.55-1.2 1.2-1.2.65 0 1.2.55 1.2 1.2 0 .65-.55 1.2-1.2 1.2zm3-10c-.66 0-1.2-.55-1.2-1.2 0-.65.55-1.2 1.2-1.2.65 0 1.2.55 1.2 1.2 0 .65-.55 1.2-1.2 1.2z"/></svg>
              Fork
</summary>            <details-dialog
              class="anim-fade-in fast Box Box--overlay d-flex flex-column"
              src="/microsoft/MCW-Modern-cloud-apps/fork?fragment=1"
              preload>
              <div class="Box-header">
                <button class="Box-btn-octicon btn-octicon float-right" type="button" aria-label="Close dialog" data-close-dialog>
                  <svg class="octicon octicon-x" viewBox="0 0 12 16" version="1.1" width="12" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.48 8l3.75 3.75-1.48 1.48L6 9.48l-3.75 3.75-1.48-1.48L4.52 8 .77 4.25l1.48-1.48L6 6.52l3.75-3.75 1.48 1.48L7.48 8z"/></svg>
                </button>
                <h3 class="Box-title">Fork MCW-Modern-cloud-apps</h3>
              </div>
              <div class="overflow-auto text-center">
                <include-fragment>
                  <div class="octocat-spinner my-3" aria-label="Loading..."></div>
                  <p class="f5 text-gray">If this dialog fails to load, you can visit <a href="/microsoft/MCW-Modern-cloud-apps/fork">the fork page</a> directly.</p>
                </include-fragment>
              </div>
            </details-dialog>
          </details>

    <a href="/microsoft/MCW-Modern-cloud-apps/network/members" class="social-count"
       aria-label="43 users forked this repository">
      43
    </a>
  </li>
</ul>

      <h1 class="public ">
    <svg class="octicon octicon-repo" viewBox="0 0 12 16" version="1.1" width="12" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9H3V8h1v1zm0-3H3v1h1V6zm0-2H3v1h1V4zm0-2H3v1h1V2zm8-1v12c0 .55-.45 1-1 1H6v2l-1.5-1.5L3 16v-2H1c-.55 0-1-.45-1-1V1c0-.55.45-1 1-1h10c.55 0 1 .45 1 1zm-1 10H1v2h2v-1h3v1h5v-2zm0-10H2v9h9V1z"/></svg>
  <span class="author" itemprop="author"><a class="url fn" rel="author" data-hovercard-type="organization" data-hovercard-url="/orgs/microsoft/hovercard" href="/microsoft">microsoft</a></span><!--
--><span class="path-divider">/</span><!--
--><strong itemprop="name"><a data-pjax="#js-repo-pjax-container" href="/microsoft/MCW-Modern-cloud-apps">MCW-Modern-cloud-apps</a></strong>
  

</h1>

    </div>
    
<nav class="hx_reponav reponav js-repo-nav js-sidenav-container-pjax container-lg p-responsive d-none d-lg-block"
     itemscope
     itemtype="http://schema.org/BreadcrumbList"
    aria-label="Repository"
     data-pjax="#js-repo-pjax-container">

  <span itemscope itemtype="http://schema.org/ListItem" itemprop="itemListElement">
    <a class="js-selected-navigation-item selected reponav-item" itemprop="url" data-hotkey="g c" aria-current="page" data-selected-links="repo_source repo_downloads repo_commits repo_releases repo_tags repo_branches repo_packages /microsoft/MCW-Modern-cloud-apps" href="/microsoft/MCW-Modern-cloud-apps">
      <svg class="octicon octicon-code" viewBox="0 0 14 16" version="1.1" width="14" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M9.5 3L8 4.5 11.5 8 8 11.5 9.5 13 14 8 9.5 3zm-5 0L0 8l4.5 5L6 11.5 2.5 8 6 4.5 4.5 3z"/></svg>
      <span itemprop="name">Code</span>
      <meta itemprop="position" content="1">
</a>  </span>

    <span itemscope itemtype="http://schema.org/ListItem" itemprop="itemListElement">
      <a itemprop="url" data-hotkey="g i" class="js-selected-navigation-item reponav-item" data-selected-links="repo_issues repo_labels repo_milestones /microsoft/MCW-Modern-cloud-apps/issues" href="/microsoft/MCW-Modern-cloud-apps/issues">
        <svg class="octicon octicon-issue-opened" viewBox="0 0 14 16" version="1.1" width="14" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7 2.3c3.14 0 5.7 2.56 5.7 5.7s-2.56 5.7-5.7 5.7A5.71 5.71 0 011.3 8c0-3.14 2.56-5.7 5.7-5.7zM7 1C3.14 1 0 4.14 0 8s3.14 7 7 7 7-3.14 7-7-3.14-7-7-7zm1 3H6v5h2V4zm0 6H6v2h2v-2z"/></svg>
        <span itemprop="name">Issues</span>
        <span class="Counter">1</span>
        <meta itemprop="position" content="2">
</a>    </span>

  <span itemscope itemtype="http://schema.org/ListItem" itemprop="itemListElement">
    <a data-hotkey="g p" data-skip-pjax="true" itemprop="url" class="js-selected-navigation-item reponav-item" data-selected-links="repo_pulls checks /microsoft/MCW-Modern-cloud-apps/pulls" href="/microsoft/MCW-Modern-cloud-apps/pulls">
      <svg class="octicon octicon-git-pull-request" viewBox="0 0 12 16" version="1.1" width="12" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M11 11.28V5c-.03-.78-.34-1.47-.94-2.06C9.46 2.35 8.78 2.03 8 2H7V0L4 3l3 3V4h1c.27.02.48.11.69.31.21.2.3.42.31.69v6.28A1.993 1.993 0 0010 15a1.993 1.993 0 001-3.72zm-1 2.92c-.66 0-1.2-.55-1.2-1.2 0-.65.55-1.2 1.2-1.2.65 0 1.2.55 1.2 1.2 0 .65-.55 1.2-1.2 1.2zM4 3c0-1.11-.89-2-2-2a1.993 1.993 0 00-1 3.72v6.56A1.993 1.993 0 002 15a1.993 1.993 0 001-3.72V4.72c.59-.34 1-.98 1-1.72zm-.8 10c0 .66-.55 1.2-1.2 1.2-.65 0-1.2-.55-1.2-1.2 0-.65.55-1.2 1.2-1.2.65 0 1.2.55 1.2 1.2zM2 4.2C1.34 4.2.8 3.65.8 3c0-.65.55-1.2 1.2-1.2.65 0 1.2.55 1.2 1.2 0 .65-.55 1.2-1.2 1.2z"/></svg>
      <span itemprop="name">Pull requests</span>
      <span class="Counter">1</span>
      <meta itemprop="position" content="3">
</a>  </span>

    <span itemscope itemtype="http://schema.org/ListItem" itemprop="itemListElement" class="position-relative float-left">
      <a data-hotkey="g w" data-skip-pjax="true" class="js-selected-navigation-item reponav-item" data-selected-links="repo_actions /microsoft/MCW-Modern-cloud-apps/actions" href="/microsoft/MCW-Modern-cloud-apps/actions">
        <svg class="octicon octicon-play" viewBox="0 0 14 16" version="1.1" width="14" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M14 8A7 7 0 110 8a7 7 0 0114 0zm-8.223 3.482l4.599-3.066a.5.5 0 000-.832L5.777 4.518A.5.5 0 005 4.934v6.132a.5.5 0 00.777.416z"/></svg>
        Actions
</a>
    </span>

    <a data-hotkey="g b" class="js-selected-navigation-item reponav-item" data-selected-links="repo_projects new_repo_project repo_project /microsoft/MCW-Modern-cloud-apps/projects" href="/microsoft/MCW-Modern-cloud-apps/projects">
      <svg class="octicon octicon-project" viewBox="0 0 15 16" version="1.1" width="15" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M10 12h3V2h-3v10zm-4-2h3V2H6v8zm-4 4h3V2H2v12zm-1 1h13V1H1v14zM14 0H1a1 1 0 00-1 1v14a1 1 0 001 1h13a1 1 0 001-1V1a1 1 0 00-1-1z"/></svg>
      Projects
      <span class="Counter" >0</span>
</a>

    <a class="js-selected-navigation-item reponav-item" data-hotkey="g w" data-selected-links="repo_wiki /microsoft/MCW-Modern-cloud-apps/wiki" href="/microsoft/MCW-Modern-cloud-apps/wiki">
      <svg class="octicon octicon-book" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M3 5h4v1H3V5zm0 3h4V7H3v1zm0 2h4V9H3v1zm11-5h-4v1h4V5zm0 2h-4v1h4V7zm0 2h-4v1h4V9zm2-6v9c0 .55-.45 1-1 1H9.5l-1 1-1-1H2c-.55 0-1-.45-1-1V3c0-.55.45-1 1-1h5.5l1 1 1-1H15c.55 0 1 .45 1 1zm-8 .5L7.5 3H2v9h6V3.5zm7-.5H9.5l-.5.5V12h6V3z"/></svg>
      Wiki
</a>
    <a data-skip-pjax="true" class="js-selected-navigation-item reponav-item" data-selected-links="security alerts policy code_scanning /microsoft/MCW-Modern-cloud-apps/security/advisories" href="/microsoft/MCW-Modern-cloud-apps/security/advisories">
      <svg class="octicon octicon-shield" viewBox="0 0 14 16" version="1.1" width="14" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M0 2l7-2 7 2v6.02C14 12.69 8.69 16 7 16c-1.69 0-7-3.31-7-7.98V2zm1 .75L7 1l6 1.75v5.268C13 12.104 8.449 15 7 15c-1.449 0-6-2.896-6-6.982V2.75zm1 .75L7 2v12c-1.207 0-5-2.482-5-5.985V3.5z"/></svg>
      Security
</a>
    <a class="js-selected-navigation-item reponav-item" data-selected-links="repo_graphs repo_contributors dependency_graph pulse people /microsoft/MCW-Modern-cloud-apps/pulse" href="/microsoft/MCW-Modern-cloud-apps/pulse">
      <svg class="octicon octicon-graph" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M16 14v1H0V0h1v14h15zM5 13H3V8h2v5zm4 0H7V3h2v10zm4 0h-2V6h2v7z"/></svg>
      Insights
</a>

</nav>

  <div class="reponav-wrapper reponav-small d-lg-none">
  <nav class="reponav js-reponav text-center no-wrap"
       itemscope
       itemtype="http://schema.org/BreadcrumbList">

    <span itemscope itemtype="http://schema.org/ListItem" itemprop="itemListElement">
      <a class="js-selected-navigation-item selected reponav-item" itemprop="url" aria-current="page" data-selected-links="repo_source repo_downloads repo_commits repo_releases repo_tags repo_branches repo_packages /microsoft/MCW-Modern-cloud-apps" href="/microsoft/MCW-Modern-cloud-apps">
        <span itemprop="name">Code</span>
        <meta itemprop="position" content="1">
</a>    </span>

      <span itemscope itemtype="http://schema.org/ListItem" itemprop="itemListElement">
        <a itemprop="url" class="js-selected-navigation-item reponav-item" data-selected-links="repo_issues repo_labels repo_milestones /microsoft/MCW-Modern-cloud-apps/issues" href="/microsoft/MCW-Modern-cloud-apps/issues">
          <span itemprop="name">Issues</span>
          <span class="Counter">1</span>
          <meta itemprop="position" content="2">
</a>      </span>

    <span itemscope itemtype="http://schema.org/ListItem" itemprop="itemListElement">
      <a itemprop="url" class="js-selected-navigation-item reponav-item" data-selected-links="repo_pulls checks /microsoft/MCW-Modern-cloud-apps/pulls" href="/microsoft/MCW-Modern-cloud-apps/pulls">
        <span itemprop="name">Pull requests</span>
        <span class="Counter">1</span>
        <meta itemprop="position" content="3">
</a>    </span>

      <span itemscope itemtype="http://schema.org/ListItem" itemprop="itemListElement">
        <a itemprop="url" class="js-selected-navigation-item reponav-item" data-selected-links="repo_projects new_repo_project repo_project /microsoft/MCW-Modern-cloud-apps/projects" href="/microsoft/MCW-Modern-cloud-apps/projects">
          <span itemprop="name">Projects</span>
          <span class="Counter">0</span>
          <meta itemprop="position" content="4">
</a>      </span>

      <span itemscope itemtype="http://schema.org/ListItem" itemprop="itemListElement">
        <a itemprop="url" class="js-selected-navigation-item reponav-item" data-selected-links="repo_wiki /microsoft/MCW-Modern-cloud-apps/wiki" href="/microsoft/MCW-Modern-cloud-apps/wiki">
          <span itemprop="name">Wiki</span>
          <meta itemprop="position" content="5">
</a>      </span>

      <a itemprop="url" class="js-selected-navigation-item reponav-item" data-selected-links="security alerts policy code_scanning /microsoft/MCW-Modern-cloud-apps/security/advisories" href="/microsoft/MCW-Modern-cloud-apps/security/advisories">
        <span itemprop="name">Security</span>
        <meta itemprop="position" content="6">
</a>
      <a class="js-selected-navigation-item reponav-item" data-selected-links="pulse /microsoft/MCW-Modern-cloud-apps/pulse" href="/microsoft/MCW-Modern-cloud-apps/pulse">
        Pulse
</a>
      <span itemscope itemtype="http://schema.org/ListItem" itemprop="itemListElement">
        <a itemprop="url" class="js-selected-navigation-item reponav-item" data-selected-links="community /microsoft/MCW-Modern-cloud-apps/community" href="/microsoft/MCW-Modern-cloud-apps/community">
          Community
</a>      </span>

  </nav>
</div>


  </div>
<div class="container-lg clearfix new-discussion-timeline experiment-repo-nav  p-responsive">
  <div class="repository-content ">

    
    


  


    <a class="d-none js-permalink-shortcut" data-hotkey="y" href="/microsoft/MCW-Modern-cloud-apps/blob/d4d0ad70c8eec2f816654fd98f8cbe5b7ec26d1b/Whiteboard%20design%20session/WDS%20trainer%20guide%20-%20Modern%20cloud%20apps.md">Permalink</a>

    <!-- blob contrib key: blob_contributors:v21:43f33ba2600c32d27882a17d32027427 -->
      

    <div class="d-flex flex-items-start flex-shrink-0 pb-3 flex-column flex-md-row">
      <span class="d-flex flex-justify-between width-full width-md-auto">
        
<details class="details-reset details-overlay select-menu branch-select-menu  hx_rsm" id="branch-select-menu">
  <summary class="btn btn-sm select-menu-button css-truncate"
           data-hotkey="w"
           title="Switch branches or tags">
    <i>Branch:</i>
    <span class="css-truncate-target" data-menu-button>master</span>
  </summary>

  <details-menu class="select-menu-modal hx_rsm-modal position-absolute" style="z-index: 99;" src="/microsoft/MCW-Modern-cloud-apps/ref-list/master/Whiteboard%20design%20session/WDS%20trainer%20guide%20-%20Modern%20cloud%20apps.md?source_action=show&amp;source_controller=blob" preload>
    <include-fragment class="select-menu-loading-overlay anim-pulse">
      <svg height="32" class="octicon octicon-octoface" viewBox="0 0 16 16" version="1.1" width="32" aria-hidden="true"><path fill-rule="evenodd" d="M14.7 5.34c.13-.32.55-1.59-.13-3.31 0 0-1.05-.33-3.44 1.3-1-.28-2.07-.32-3.13-.32s-2.13.04-3.13.32c-2.39-1.64-3.44-1.3-3.44-1.3-.68 1.72-.26 2.99-.13 3.31C.49 6.21 0 7.33 0 8.69 0 13.84 3.33 15 7.98 15S16 13.84 16 8.69c0-1.36-.49-2.48-1.3-3.35zM8 14.02c-3.3 0-5.98-.15-5.98-3.35 0-.76.38-1.48 1.02-2.07 1.07-.98 2.9-.46 4.96-.46 2.07 0 3.88-.52 4.96.46.65.59 1.02 1.3 1.02 2.07 0 3.19-2.68 3.35-5.98 3.35zM5.49 9.01c-.66 0-1.2.8-1.2 1.78s.54 1.79 1.2 1.79c.66 0 1.2-.8 1.2-1.79s-.54-1.78-1.2-1.78zm5.02 0c-.66 0-1.2.79-1.2 1.78s.54 1.79 1.2 1.79c.66 0 1.2-.8 1.2-1.79s-.53-1.78-1.2-1.78z"/></svg>
    </include-fragment>
  </details-menu>
</details>

        <div class="BtnGroup flex-shrink-0 d-md-none">
          <a href="/microsoft/MCW-Modern-cloud-apps/find/master"
                class="js-pjax-capture-input btn btn-sm BtnGroup-item"
                data-pjax
                data-hotkey="t">
            Find file
          </a>
          <clipboard-copy value="Whiteboard design session/WDS trainer guide - Modern cloud apps.md" class="btn btn-sm BtnGroup-item">
            Copy path
          </clipboard-copy>
        </div>
      </span>
      <h2 id="blob-path" class="breadcrumb flex-auto min-width-0 text-normal flex-md-self-center ml-md-2 mr-md-3 my-2 my-md-0">
        <span class="js-repo-root text-bold"><span class="js-path-segment"><a data-pjax="true" href="/microsoft/MCW-Modern-cloud-apps"><span>MCW-Modern-cloud-apps</span></a></span></span><span class="separator">/</span><span class="js-path-segment"><a data-pjax="true" href="/microsoft/MCW-Modern-cloud-apps/tree/master/Whiteboard%20design%20session"><span>Whiteboard design session</span></a></span><span class="separator">/</span><strong class="final-path">WDS trainer guide - Modern cloud apps.md</strong>
      </h2>

      <div class="BtnGroup flex-shrink-0 d-none d-md-inline-block">
        <a href="/microsoft/MCW-Modern-cloud-apps/find/master"
              class="js-pjax-capture-input btn btn-sm BtnGroup-item"
              data-pjax
              data-hotkey="t">
          Find file
        </a>
        <clipboard-copy value="Whiteboard design session/WDS trainer guide - Modern cloud apps.md" class="btn btn-sm BtnGroup-item">
          Copy path
        </clipboard-copy>
      </div>
    </div>

    



    
  <div class="Box Box--condensed d-flex flex-column flex-shrink-0">
      <div class="Box-body d-flex flex-justify-between bg-blue-light flex-column flex-md-row flex-items-start flex-md-items-center">
        <span class="pr-md-4 f6">
          <a rel="contributor" data-skip-pjax="true" data-hovercard-type="user" data-hovercard-url="/users/DawnmarieDesJardins/hovercard" data-octo-click="hovercard-link-click" data-octo-dimensions="link_type:self" href="/DawnmarieDesJardins"><img class="avatar" src="https://avatars3.githubusercontent.com/u/39317565?s=40&amp;v=4" width="20" height="20" alt="@DawnmarieDesJardins" /></a>
          <a class="text-bold link-gray-dark lh-default v-align-middle" rel="contributor" data-hovercard-type="user" data-hovercard-url="/users/DawnmarieDesJardins/hovercard" data-octo-click="hovercard-link-click" data-octo-dimensions="link_type:self" href="/DawnmarieDesJardins">DawnmarieDesJardins</a>
            <span class="lh-default v-align-middle">
              <a data-pjax="true" title="Update WDS trainer guide - Modern cloud apps.md

July test/fix QC." class="link-gray" href="/microsoft/MCW-Modern-cloud-apps/commit/6adb1f8272a1e848187943d7f1c6c4d20e904b8c">Update WDS trainer guide - Modern cloud apps.md</a>
            </span>
        </span>
        <span class="d-inline-block flex-shrink-0 v-align-bottom f6 mt-2 mt-md-0">
          <a class="pr-2 text-mono link-gray" href="/microsoft/MCW-Modern-cloud-apps/commit/6adb1f8272a1e848187943d7f1c6c4d20e904b8c" data-pjax>6adb1f8</a>
          <relative-time datetime="2019-09-11T00:32:34Z" class="no-wrap">Sep 11, 2019</relative-time>
        </span>
      </div>

    <div class="Box-body d-flex flex-items-center flex-auto f6 border-bottom-0 flex-wrap" >
      <details class="details-reset details-overlay details-overlay-dark lh-default text-gray-dark float-left mr-2" id="blob_contributors_box">
        <summary class="btn-link">
          <span><strong>6</strong> contributors</span>
        </summary>
        <details-dialog
          class="Box Box--overlay d-flex flex-column anim-fade-in fast"
          aria-label="Users who have contributed to this file"
          src="/microsoft/MCW-Modern-cloud-apps/contributors-list/master/Whiteboard%20design%20session/WDS%20trainer%20guide%20-%20Modern%20cloud%20apps.md" preload>
          <div class="Box-header">
            <button class="Box-btn-octicon btn-octicon float-right" type="button" aria-label="Close dialog" data-close-dialog>
              <svg class="octicon octicon-x" viewBox="0 0 12 16" version="1.1" width="12" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.48 8l3.75 3.75-1.48 1.48L6 9.48l-3.75 3.75-1.48-1.48L4.52 8 .77 4.25l1.48-1.48L6 6.52l3.75-3.75 1.48 1.48L7.48 8z"/></svg>
            </button>
            <h3 class="Box-title">
              Users who have contributed to this file
            </h3>
          </div>
          <include-fragment class="octocat-spinner my-3" aria-label="Loading..."></include-fragment>
        </details-dialog>
      </details>
        <span class="">
    <a class="avatar-link" data-hovercard-type="user" data-hovercard-url="/users/DawnmarieDesJardins/hovercard" data-octo-click="hovercard-link-click" data-octo-dimensions="link_type:self" href="/microsoft/MCW-Modern-cloud-apps/commits/master/Whiteboard%20design%20session/WDS%20trainer%20guide%20-%20Modern%20cloud%20apps.md?author=DawnmarieDesJardins">
      <img class="avatar mr-1" src="https://avatars3.githubusercontent.com/u/39317565?s=40&amp;v=4" width="20" height="20" alt="@DawnmarieDesJardins" /> 
</a>    <a class="avatar-link" data-hovercard-type="user" data-hovercard-url="/users/joelhulen/hovercard" data-octo-click="hovercard-link-click" data-octo-dimensions="link_type:self" href="/microsoft/MCW-Modern-cloud-apps/commits/master/Whiteboard%20design%20session/WDS%20trainer%20guide%20-%20Modern%20cloud%20apps.md?author=joelhulen">
      <img class="avatar mr-1" src="https://avatars2.githubusercontent.com/u/5950304?s=40&amp;v=4" width="20" height="20" alt="@joelhulen" /> 
</a>    <a class="avatar-link" data-hovercard-type="user" data-hovercard-url="/users/crpietschmann/hovercard" data-octo-click="hovercard-link-click" data-octo-dimensions="link_type:self" href="/microsoft/MCW-Modern-cloud-apps/commits/master/Whiteboard%20design%20session/WDS%20trainer%20guide%20-%20Modern%20cloud%20apps.md?author=crpietschmann">
      <img class="avatar mr-1" src="https://avatars2.githubusercontent.com/u/392297?s=40&amp;v=4" width="20" height="20" alt="@crpietschmann" /> 
</a>    <a class="avatar-link" data-hovercard-type="user" data-hovercard-url="/users/timahenning/hovercard" data-octo-click="hovercard-link-click" data-octo-dimensions="link_type:self" href="/microsoft/MCW-Modern-cloud-apps/commits/master/Whiteboard%20design%20session/WDS%20trainer%20guide%20-%20Modern%20cloud%20apps.md?author=timahenning">
      <img class="avatar mr-1" src="https://avatars2.githubusercontent.com/u/48766586?s=40&amp;v=4" width="20" height="20" alt="@timahenning" /> 
</a>    <a class="avatar-link" data-hovercard-type="user" data-hovercard-url="/users/kylebunting/hovercard" data-octo-click="hovercard-link-click" data-octo-dimensions="link_type:self" href="/microsoft/MCW-Modern-cloud-apps/commits/master/Whiteboard%20design%20session/WDS%20trainer%20guide%20-%20Modern%20cloud%20apps.md?author=kylebunting">
      <img class="avatar mr-1" src="https://avatars3.githubusercontent.com/u/5960229?s=40&amp;v=4" width="20" height="20" alt="@kylebunting" /> 
</a>    <a class="avatar-link" data-hovercard-type="user" data-hovercard-url="/users/deltadan/hovercard" data-octo-click="hovercard-link-click" data-octo-dimensions="link_type:self" href="/microsoft/MCW-Modern-cloud-apps/commits/master/Whiteboard%20design%20session/WDS%20trainer%20guide%20-%20Modern%20cloud%20apps.md?author=deltadan">
      <img class="avatar mr-1" src="https://avatars3.githubusercontent.com/u/13724412?s=40&amp;v=4" width="20" height="20" alt="@deltadan" /> 
</a>
</span>

    </div>
  </div>





    <div class="Box mt-3 position-relative">
      
<div class="Box-header py-2 d-flex flex-column flex-shrink-0 flex-md-row flex-md-items-center">
  <div class="text-mono f6 flex-auto pr-3 flex-order-2 flex-md-order-1 mt-2 mt-md-0">

      671 lines (358 sloc)
      <span class="file-info-divider"></span>
    55.7 KB
  </div>

  <div class="d-flex py-1 py-md-0 flex-auto flex-order-1 flex-md-order-2 flex-sm-grow-0 flex-justify-between">

    <div class="BtnGroup">
      <a id="raw-url" class="btn btn-sm BtnGroup-item" href="/microsoft/MCW-Modern-cloud-apps/raw/master/Whiteboard%20design%20session/WDS%20trainer%20guide%20-%20Modern%20cloud%20apps.md">Raw</a>
        <a class="btn btn-sm js-update-url-with-hash BtnGroup-item" data-hotkey="b" href="/microsoft/MCW-Modern-cloud-apps/blame/master/Whiteboard%20design%20session/WDS%20trainer%20guide%20-%20Modern%20cloud%20apps.md">Blame</a>
      <a rel="nofollow" class="btn btn-sm BtnGroup-item" href="/microsoft/MCW-Modern-cloud-apps/commits/master/Whiteboard%20design%20session/WDS%20trainer%20guide%20-%20Modern%20cloud%20apps.md">History</a>
    </div>


    <div>
            <a class="btn-octicon tooltipped tooltipped-nw hide-sm"
               href="x-github-client://openRepo/https://github.com/microsoft/MCW-Modern-cloud-apps?branch=master&amp;filepath=Whiteboard%20design%20session%2FWDS%20trainer%20guide%20-%20Modern%20cloud%20apps.md"
               aria-label="Open this file in GitHub Desktop"
               data-ga-click="Repository, open with desktop, type:windows">
                <svg class="octicon octicon-device-desktop" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M15 2H1c-.55 0-1 .45-1 1v9c0 .55.45 1 1 1h5.34c-.25.61-.86 1.39-2.34 2h8c-1.48-.61-2.09-1.39-2.34-2H15c.55 0 1-.45 1-1V3c0-.55-.45-1-1-1zm0 9H1V3h14v8z"/></svg>
            </a>

            <!-- '"` --><!-- </textarea></xmp> --></option></form><form class="inline-form js-update-url-with-hash" action="/microsoft/MCW-Modern-cloud-apps/edit/master/Whiteboard%20design%20session/WDS%20trainer%20guide%20-%20Modern%20cloud%20apps.md" accept-charset="UTF-8" method="post"><input name="utf8" type="hidden" value="&#x2713;" /><input type="hidden" name="authenticity_token" value="mY9cdZE8nMOiFG2x601gFjQf5Pab/nvaY/eylRsBA62+43lrqMBSyZS9UZUSrHunuk7kg1wuCkkrUa4LRtLCyg==" />
              <button class="btn-octicon tooltipped tooltipped-nw" type="submit"
                aria-label="Edit the file in your fork of this project" data-hotkey="e" data-disable-with>
                <svg class="octicon octicon-pencil" viewBox="0 0 14 16" version="1.1" width="14" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M0 12v3h3l8-8-3-3-8 8zm3 2H1v-2h1v1h1v1zm10.3-9.3L12 6 9 3l1.3-1.3a.996.996 0 011.41 0l1.59 1.59c.39.39.39 1.02 0 1.41z"/></svg>
              </button>
</form>
          <!-- '"` --><!-- </textarea></xmp> --></option></form><form class="inline-form" action="/microsoft/MCW-Modern-cloud-apps/delete/master/Whiteboard%20design%20session/WDS%20trainer%20guide%20-%20Modern%20cloud%20apps.md" accept-charset="UTF-8" method="post"><input name="utf8" type="hidden" value="&#x2713;" /><input type="hidden" name="authenticity_token" value="qH+WJoM45qwFZCA/x8MOI5Usxnh3WJ4G57XVbq2Yrw7PA3vF6wPtyXTYMWHMg2vqMLrPF4CalpQmS0xOerd+cQ==" />
            <button class="btn-octicon btn-octicon-danger tooltipped tooltipped-nw" type="submit"
              aria-label="Delete the file in your fork of this project" data-disable-with>
              <svg class="octicon octicon-trashcan" viewBox="0 0 12 16" version="1.1" width="12" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M11 2H9c0-.55-.45-1-1-1H5c-.55 0-1 .45-1 1H2c-.55 0-1 .45-1 1v1c0 .55.45 1 1 1v9c0 .55.45 1 1 1h7c.55 0 1-.45 1-1V5c.55 0 1-.45 1-1V3c0-.55-.45-1-1-1zm-1 12H3V5h1v8h1V5h1v8h1V5h1v8h1V5h1v9zm1-10H2V3h9v1z"/></svg>
            </button>
</form>    </div>
  </div>
</div>




      
  <div id="readme" class="Box-body readme blob instapaper_body js-code-block-container">
    <article class="markdown-body entry-content p-3 p-md-6" itemprop="text"><p><a target="_blank" rel="noopener noreferrer" href="https://github.com/Microsoft/MCW-Template-Cloud-Workshop/raw/master/Media/ms-cloud-workshop.png"><img src="https://github.com/Microsoft/MCW-Template-Cloud-Workshop/raw/master/Media/ms-cloud-workshop.png" alt="Microsoft Cloud Workshops" title="Microsoft Cloud Workshops" style="max-width:100%;"></a></p>
<div>
Modern cloud apps
</div>
<div>
 Whiteboard design session trainer guide
</div>
<div>
September 2019
</div>
<p>Information in this document, including URL and other Internet Web site references, is subject to change without notice. Unless otherwise noted, the example companies, organizations, products, domain names, e-mail addresses, logos, people, places, and events depicted herein are fictitious, and no association with any real company, organization, product, domain name, e-mail address, logo, person, place or event is intended or should be inferred. Complying with all applicable copyright laws is the responsibility of the user. Without limiting the rights under copyright, no part of this document may be reproduced, stored in or introduced into a retrieval system, or transmitted in any form or by any means (electronic, mechanical, photocopying, recording, or otherwise), or for any purpose, without the express written permission of Microsoft Corporation.</p>
<p>Microsoft may have patents, patent applications, trademarks, copyrights, or other intellectual property rights covering subject matter in this document. Except as expressly provided in any written license agreement from Microsoft, the furnishing of this document does not give you any license to these patents, trademarks, copyrights, or other intellectual property.</p>
<p>The names of manufacturers, products, or URLs are provided for informational purposes only and Microsoft makes no representations and warranties, either expressed, implied, or statutory, regarding these manufacturers or the use of the products with any Microsoft technologies. The inclusion of a manufacturer or product does not imply endorsement of Microsoft of the manufacturer or product. Links may be provided to third party sites. Such sites are not under the control of Microsoft and Microsoft is not responsible for the contents of any linked site or any link contained in a linked site, or any changes or updates to such sites. Microsoft is not responsible for webcasting or any other form of transmission received from any linked site. Microsoft is providing these links to you only as a convenience, and the inclusion of any link does not imply endorsement of Microsoft of the site or the products contained therein.</p>
<p>© 2019 Microsoft Corporation. All rights reserved.</p>
<p>Microsoft and the trademarks listed at <a href="https://www.microsoft.com/en-us/legal/intellectualproperty/Trademarks/Usage/General.aspx" rel="nofollow">https://www.microsoft.com/en-us/legal/intellectualproperty/Trademarks/Usage/General.aspx</a> are trademarks of the Microsoft group of companies. All other trademarks are property of their respective owners.</p>
<h1><a id="user-content-modern-cloud-apps-whiteboard-design-session-trainer-guide" class="anchor" aria-hidden="true" href="#modern-cloud-apps-whiteboard-design-session-trainer-guide"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Modern cloud apps whiteboard design session trainer guide</h1>
<p><strong>Contents</strong></p>

<ul>
<li><a href="#modern-cloud-apps-whiteboard-design-session-trainer-guide">Modern cloud apps whiteboard design session trainer guide</a></li>
<li><a href="#trainer-information">Trainer information</a>
<ul>
<li><a href="#role-of-the-trainer">Role of the trainer</a></li>
<li><a href="#whiteboard-design-session-flow">Whiteboard design session flow</a></li>
<li><a href="#before-the-whiteboard-design-session-how-to-prepare">Before the whiteboard design session: How to prepare</a></li>
<li><a href="#during-the-whiteboard-design-session-tips-for-an-effective-whiteboard-design-session">During the whiteboard design session: Tips for an effective whiteboard design session</a></li>
</ul>
</li>
<li><a href="#modern-cloud-apps-whiteboard-design-session-student-guide">Modern cloud apps whiteboard design session student guide</a>
<ul>
<li><a href="#abstract-and-learning-objectives">Abstract and learning objectives</a></li>
<li><a href="#step-1-review-the-customer-case-study">Step 1: Review the customer case study</a>
<ul>
<li><a href="#customer-situation">Customer situation</a></li>
<li><a href="#customer-needs">Customer needs</a></li>
<li><a href="#customer-objections">Customer objections</a></li>
<li><a href="#infographic-for-common-scenarios">Infographic for common scenarios</a></li>
</ul>
</li>
<li><a href="#step-2-design-a-proof-of-concept-solution">Step 2: Design a proof of concept solution</a></li>
<li><a href="#step-3-present-the-solution">Step 3: Present the solution</a></li>
<li><a href="#wrap-up">Wrap-up</a></li>
<li><a href="#additional-references">Additional references</a></li>
</ul>
</li>
<li><a href="#modern-cloud-apps-whiteboard-design-session-trainer-guide-1">Modern cloud apps whiteboard design session trainer guide</a>
<ul>
<li><a href="#step-1-review-the-customer-case-study-1">Step 1: Review the customer case study</a></li>
<li><a href="#step-2-design-a-proof-of-concept-solution-1">Step 2: Design a proof of concept solution</a></li>
<li><a href="#step-3-present-the-solution-1">Step 3: Present the solution</a></li>
<li><a href="#wrap-up-1">Wrap-up</a></li>
<li><a href="#preferred-target-audience">Preferred target audience</a></li>
<li><a href="#preferred-solution">Preferred solution</a></li>
<li><a href="#checklist-of-preferred-objection-handling">Checklist of preferred objection handling</a></li>
<li><a href="#customer-quote-to-be-read-back-to-the-attendees-at-the-end">Customer quote (to be read back to the attendees at the end)</a></li>
</ul>
</li>
</ul>

<h1><a id="user-content-trainer-information" class="anchor" aria-hidden="true" href="#trainer-information"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Trainer information</h1>
<p>Thank you for taking time to support the whiteboard design sessions as a trainer!</p>
<h2><a id="user-content-role-of-the-trainer" class="anchor" aria-hidden="true" href="#role-of-the-trainer"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Role of the trainer</h2>
<p>An amazing trainer:</p>
<ul>
<li>
<p>Creates a safe environment in which learning can take place.</p>
</li>
<li>
<p>Stimulates the participant's thinking.</p>
</li>
<li>
<p>Involves the participant in the learning process.</p>
</li>
<li>
<p>Manages the learning process (on time, on topic, and adjusting to benefit participants).</p>
</li>
<li>
<p>Ensures individual participant accountability.</p>
</li>
<li>
<p>Ties it all together for the participant.</p>
</li>
<li>
<p>Provides insight and experience to the learning process.</p>
</li>
<li>
<p>Effectively leads the whiteboard design session discussion.</p>
</li>
<li>
<p>Monitors quality and appropriateness of participant deliverables.</p>
</li>
<li>
<p>Effectively leads the feedback process.</p>
</li>
</ul>
<h2><a id="user-content-whiteboard-design-session-flow" class="anchor" aria-hidden="true" href="#whiteboard-design-session-flow"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Whiteboard design session flow</h2>
<p>Each whiteboard design session uses the following flow:</p>
<p><strong>Step 1: Review the customer case study (15 minutes)</strong></p>
<p><strong>Outcome</strong></p>
<p>Analyze your customer's needs.</p>
<ul>
<li>
<p>Customer's background, situation, needs and technical requirements</p>
</li>
<li>
<p>Current customer infrastructure and architecture</p>
</li>
<li>
<p>Potential issues, objectives and blockers</p>
</li>
</ul>
<p><strong>Step 2: Design a proof of concept solution (60 minutes)</strong></p>
<p><strong>Outcome</strong></p>
<p>Design a solution and prepare to present the solution to the target customer audience in a 15-minute chalk-talk format.</p>
<ul>
<li>
<p>Determine your target customer audience.</p>
</li>
<li>
<p>Determine customer's business needs to address your solution.</p>
</li>
<li>
<p>Design and diagram your solution.</p>
</li>
<li>
<p>Prepare to present your solution.</p>
</li>
</ul>
<p><strong>Step 3: Present the solution (30 minutes)</strong></p>
<p><strong>Outcome</strong></p>
<p>Present solution to your customer:</p>
<ul>
<li>
<p>Present solution</p>
</li>
<li>
<p>Respond to customer objections</p>
</li>
<li>
<p>Receive feedback</p>
</li>
</ul>
<p><strong>Wrap-up (15 minutes)</strong></p>
<ul>
<li>Review preferred solution</li>
</ul>
<h2><a id="user-content-before-the-whiteboard-design-session-how-to-prepare" class="anchor" aria-hidden="true" href="#before-the-whiteboard-design-session-how-to-prepare"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Before the whiteboard design session: How to prepare</h2>
<p>Before conducting your first whiteboard design session:</p>
<ul>
<li>
<p>Read the Student guide (including the case study) and Trainer guide.</p>
</li>
<li>
<p>Become familiar with all key points and activities.</p>
</li>
<li>
<p>Plan the point you want to stress, which questions you want to drive, transitions, and be ready to answer questions.</p>
</li>
<li>
<p>Prior to the whiteboard design session, discuss the case study to pick up more ideas.</p>
</li>
<li>
<p>Make notes for later.</p>
</li>
</ul>
<h2><a id="user-content-during-the-whiteboard-design-session-tips-for-an-effective-whiteboard-design-session" class="anchor" aria-hidden="true" href="#during-the-whiteboard-design-session-tips-for-an-effective-whiteboard-design-session"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>During the whiteboard design session: Tips for an effective whiteboard design session</h2>
<p><strong>Refer to the Trainer guide</strong> to stay on track and observe the timings.</p>
<p><strong>Do not expect to memorize every detail</strong> of the whiteboard design session.</p>
<p>When participants are doing activities, you can <strong>look ahead to refresh your memory</strong>.</p>
<ul>
<li>
<p><strong>Adjust activity and whiteboard design session pace</strong> as needed to allow time for presenting, feedback, and sharing.</p>
</li>
<li>
<p><strong>Add examples, points, and stories</strong> from your own experience. Think about stories you can share that help you make your points clearly and effectively.</p>
</li>
<li>
<p><strong>Consider creating a "parking lot"</strong> to record issues or questions raised that are outside the scope of the whiteboard design session or can be answered later. Decide how you will address these issues, so you can acknowledge them without being derailed by them.</p>
</li>
</ul>
<p><em><strong>Have fun</strong>! Encourage participants to have fun and share!</em></p>
<p><strong>Involve your participants.</strong> Talk and share your knowledge but always involve your participants, even while you are the one speaking.</p>
<p><strong>Ask questions</strong> and get them to share to fully involve your group in the learning process.</p>
<p><strong>Ask first</strong>, whenever possible. Before launching into a topic, learn your audience's opinions about it and experiences with it. Asking first enables you to assess their level of knowledge and experience, and leaves them more open to what you are presenting.</p>
<p><strong>Wait for responses</strong>. If you ask a question such as, "What's your experience with (fill in the blank)?" then wait. Do not be afraid of a little silence. If you leap into the silence, your participants will feel you are not serious about involving them and will become passive. Give participants a chance to think, and if no one answers, patiently ask again. You will usually get a response.</p>
<h1><a id="user-content-modern-cloud-apps-whiteboard-design-session-student-guide" class="anchor" aria-hidden="true" href="#modern-cloud-apps-whiteboard-design-session-student-guide"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Modern cloud apps whiteboard design session student guide</h1>
<h2><a id="user-content-abstract-and-learning-objectives" class="anchor" aria-hidden="true" href="#abstract-and-learning-objectives"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Abstract and learning objectives</h2>
<p>In this whiteboard design session, you will work with a group to design a solution to modernize CSLA's e-commerce and back-end services, while maintaining existing PCI compliance. To ensure compliance, you will ensure data privacy and protection across all aspects of the system, in transit and at rest. The goal is to use Azure PaaS services for the public-facing and back-end websites, while providing a way for the on-premises components to securely communicate with these services. You will also design fault-tolerance and a regional failover plan of the Azure components.</p>
<p>By the end of this whiteboard design session, you will have a better understanding of how to modernize a legacy web app by retargeting it for the cloud, taking advantage of the many services Azure provides to enhance functionality and secure your solution's components by following best practices for PCI compliance and security.</p>
<h2><a id="user-content-step-1-review-the-customer-case-study" class="anchor" aria-hidden="true" href="#step-1-review-the-customer-case-study"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Step 1: Review the customer case study</h2>
<p><strong>Outcome</strong></p>
<p>Analyze your customer's needs.</p>
<p>Timeframe: 15 minutes</p>
<p>Directions: With all participants in the session, the facilitator/SME presents an overview of the customer case study along with technical tips.</p>
<ol>
<li>
<p>Meet your table participants and trainer.</p>
</li>
<li>
<p>Read all of the directions for steps 1-3 in the student guide.</p>
</li>
<li>
<p>As a table team, review the following customer case study.</p>
</li>
</ol>
<h3><a id="user-content-customer-situation" class="anchor" aria-hidden="true" href="#customer-situation"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Customer situation</h3>
<p>The Contoso Sports League Association (CSLA) is one of the largest sports franchises. They have over 100 championships in their history and a huge, passionate fan base. They run a highly successful e-commerce website that sells merchandise to their legions of sports fans. The website is built using ASP.NET and currently hosted in a co-location.</p>
<p>They accept payment by credit card and owing to their high annual volume (in the tens of millions, processing about 50K per day) of transactions, need to ensure that they are Payment Card Industry Data Security Standards (PCI DSS) Level 1 compliant. Their website hosts the shopping cart and checkout process, but they defer the credit card authorization and capture responsibilities of the credit card processing to a third-party payment gateway. This payment gateway provides a web application programming interface (API) that is invoked over Transport Layer Security (TLS) from Contoso server-side logic. The call includes the credit card holder data (name, number, and so on) and returns a status indicating a success or failure in authorizing and capturing payment against the credit card. It is called after the customer clicks checkout, as a part of processing the order. They currently store their customer and profile data in SQL Server 2014.</p>
<p>In addition to the public facing e-commerce website, they have a backend website that supports their call center. Call center employees use this admin website to view customer orders. Customers can call in to the call center to place orders and pay for orders with their credit cards by phone.</p>
<p>CSLA manages the order fulfillment process. When an order arrives, they store the order details in their SQL database, and send a message for each order to their inventory management system running the warehouse. CSLA experiences a roughly 12-hour window that spans east to west coast business hours, during which they get most of their orders. The warehouse receives the message (which simply contains the order ID from the database), pulls up the order details identified in the message (by a lookup against the database), and then for each item in the order queues up a separate process to locate the item in inventory or place an order for it with their supplier. Once this initial status for each item in the order is collected, the inventory status is updated in the database and a confirmation email is sent to the customer indicating the estimated delivery date of their completed order (and if any items are in backorder). This inventory lookup rarely takes more than a few hours and never more than a day.</p>
<p>They have reached a point where managing their server infrastructure is becoming a real challenge.  Contoso wants to understand more about platform as a service (PaaS) solutions. They wonder if PaaS could help them focus their efforts more on the core business value rather than infrastructure. They have observed that Azure has received PCI compliance certification and are interested in moving their solution to Azure. "We're finding that with every upgrade, we're spending more and more engineering time on infrastructure and less on the experience that matters most to our fan base," says Miles Strom, Chief Executive Officer (CEO) of Contoso Sports League Association, "we need to rebalance those efforts."</p>
<p>One example is in how they manage the usernames and passwords for call center operators and support staff, as applied to the call center admin website. Today they have a homegrown solution that stores usernames and passwords in the same database used for storing merchandise information. They have experimented with other third-party solutions in the past, and their employees found it jarring to see another company's logo displayed when logging into their own call center website. In creating their identity solution, they want to ensure they can brand the login screens with their own logo. Additionally, Contoso is concerned about hackers from foreign countries/regions gaining access to the administrator site. Before they choose an identity solution, they would like to see how it indicates such attempts.</p>
<p>There is one architectural enhancement Contoso would like to make in the transition to a PaaS solution. When a visitor loads the home page, it gets the list of featured products on offer (consisting of the product image, title, and URL) from the Offers service. The home page does it using a client-side GET request against an ASP.NET Web API 2 service that is executed as the page loads in the browser. Contoso anticipates growing the functionality of this service and would like to scale it independently of the website.</p>
<p>Contoso is also looking to augment their data analytics story by introducing a data warehouse to enable them to analyze their historical data over time, particularly as their number of transactions soars in the cloud. They would like to plan for a solution that moves the data from their OLTP database into their data warehouse on a nightly basis, ideally with the minimum amount of infrastructure or development effort.</p>
<h3><a id="user-content-customer-needs" class="anchor" aria-hidden="true" href="#customer-needs"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Customer needs</h3>
<ol>
<li>
<p>Make architectural decisions that help to minimize engineering around infrastructure in favor of those that deliver core business value. Contoso is interested in understanding more about PaaS solutions.</p>
</li>
<li>
<p>Maintain existing PCI compliance.</p>
</li>
<li>
<p>Ensure data privacy and protection across all aspects of the system, in transit and at rest.</p>
</li>
<li>
<p>They want to be able to scale their offers' API independently of the website.</p>
</li>
<li>
<p>Ensure that they retain their core functionality, even if the way it is accomplished under the covers might change.</p>
</li>
<li>
<p>Provide a better solution for the management of usernames and passwords.</p>
</li>
<li>
<p>Provide a regional database failover plan that will enable the customer to initiate the failover to another region, allowing their various web applications and other hosted services to roll over to a synchronized database at minimal cost.</p>
</li>
<li>
<p>A data warehouse for analyzing their transaction history.</p>
</li>
</ol>
<h3><a id="user-content-customer-objections" class="anchor" aria-hidden="true" href="#customer-objections"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Customer objections</h3>
<ol>
<li>
<p>It is not clear to us from the Azure Trust Center just how Azure helps our solution become PCI compliant.</p>
</li>
<li>
<p>Can we provide a solution that scales to meet our public demand, but is also secure for use by our call center and warehouse?</p>
</li>
<li>
<p>Our PCI compliance requires us to have a quarterly audit and to conduct occasional penetration tests. Is it supported by Azure?</p>
</li>
<li>
<p>Can we audit the Azure data center?</p>
</li>
<li>
<p>In the past, we have relied on SOASTA CloudTest to design and execute our web load tests at scale. In moving to Azure, are we still take advantage of CloudTest?</p>
</li>
<li>
<p>Our previous infrastructure did not have great performance monitoring of our websites. What options would you recommend we investigate that would work with our web apps in Azure?</p>
</li>
<li>
<p>We have heard that Azure's data warehouse can be paused? Does that mean we have to store all our data in Azure Storage first before we can pause the instances and risk losing our data?</p>
</li>
<li>
<p>We know it's possible to use Azure SQL Database as our data warehouse. What should we consider when deciding between this and Azure SQL Data Warehouse?</p>
</li>
</ol>
<h3><a id="user-content-infographic-for-common-scenarios" class="anchor" aria-hidden="true" href="#infographic-for-common-scenarios"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Infographic for common scenarios</h3>
<p><a target="_blank" rel="noopener noreferrer" href="/microsoft/MCW-Modern-cloud-apps/blob/master/Whiteboard%20design%20session/media/image2.png"><img src="/microsoft/MCW-Modern-cloud-apps/raw/master/Whiteboard%20design%20session/media/image2.png" alt="This diagram is of a Common scenario for an E-Commerce Website. The diagram begins with an end user, includes a services tier, internet tier, and data tier, and ends at an Enterprise. The diagram also includes Microsoft Azure, and Azure Virtual Network." title="Common scenario for an E-Commerce Website" style="max-width:100%;"></a></p>
<h2><a id="user-content-step-2-design-a-proof-of-concept-solution" class="anchor" aria-hidden="true" href="#step-2-design-a-proof-of-concept-solution"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Step 2: Design a proof of concept solution</h2>
<p><strong>Outcome</strong></p>
<p>Design a solution and prepare to present the solution to the target customer audience in a 15-minute chalk-talk format.</p>
<p>Timeframe: 60 minutes</p>
<p><strong>Business needs</strong></p>
<p>Directions:  With all participants at your table, answer the following questions and list the answers on a flip chart:</p>
<ol>
<li>
<p>Who should you present this solution to? Who is your target customer audience? Who are the decision makers?</p>
</li>
<li>
<p>What customer business needs do you need to address with your solution?</p>
</li>
</ol>
<p><strong>Design</strong></p>
<p>Directions: With all participants at your table, respond to the following questions on a flip chart:</p>
<p><em>High-level architecture</em></p>
<ol>
<li>Without getting into the details, the following sections will address the details, diagram your initial vision for handling the top-level requirements for the e-commerce website, call center website, and inventory lookup process. You will refine this diagram as you proceed.</li>
</ol>
<p><em>Order fulfillment</em></p>
<ol>
<li>How would you recommend CSLA manage the inventory lookup queues? How would you help CSLA decide between Azure Queues and Service Bus? Be sure to consider details implied by CSLA's requirements such as volume, message lifetime, and sizing. Explain the details of any computations you make.</li>
</ol>
<p><em>Notifications</em></p>
<ol>
<li>How would you recommend CSLA manage notifying customers as their order in the CSLA orders database is processed? Are there specific Azure services that can be used? Include details on how this would be implemented and integrated into the proposed solution for CSLA.</li>
</ol>
<p><em>Offers service</em></p>
<ol>
<li>
<p>Would you propose Contoso use the Azure App Service API app to meet their requirements for the Offers service?</p>
</li>
<li>
<p>If so, what specific configurations would you need to make to support your proposed topology? Specifically, how would you implement the changes and configurations required to allow for inter-app communication between the e-commerce application and the Offers service?</p>
</li>
</ol>
<p><em>Geo-resiliency</em></p>
<ol>
<li>
<p>How would you implement high availability for the orders database to guard against regional data center outages? Be specific on how you would configure SQL Database and Azure Storage.</p>
</li>
<li>
<p>What process would you recommend to the customer to failover in the event of an outage, ensuring their web applications and associated Azure services change over to a secondary region?</p>
</li>
<li>
<p>How long would a failover take and how much data could be lost, in terms of time?</p>
</li>
</ol>
<p><em>Access control</em></p>
<ol>
<li>With respect to managing access to the call center website, explain how you would recommend Contoso implement a solution that meets their requirements. Be specific about both the implementation and the process you would use to gain Contoso's acceptance of the proposed solution.</li>
</ol>
<p><em>Enabling PCI compliance</em></p>
<ol>
<li>
<p>Keeping only the e-commerce website and handling of cardholder data in scope for PCI, consider the following in your design:</p>
<p>a. Are web apps deployed in Azure App Service Environments an option?</p>
<p>b. Explain how using Azure App Service Environments could address the PCI requirements.</p>
<p>c. Keeping in mind the best choice for securing inbound and outbound traffic for an App Service Environment, detail all inbound and outbound traffic for this solution that allows it to be PCI compliant and allows it to operate within Azure. It should include traffic into and out of the solution, outbound for the e-commerce website, and any other traffic between the apps within the solution.</p>
<p>d. Make sure to describe in detail the network topology you are using.</p>
<p>e. For any inbound and outbound application communications you are securing, please detail the specific mechanisms you will use to do so.</p>
<p>f. If your approach includes configuration scripts, please provide an example of the scripts.</p>
</li>
<li>
<p>Would you recommend they use Azure virtual machines? Why or why not?</p>
</li>
</ol>
<p><em>Data warehouse</em></p>
<ol>
<li>
<p>How would you recommend Contoso implement their data warehouse?</p>
</li>
<li>
<p>How would Contoso schedule nightly data transfers from their OLTP database to their data warehouse?</p>
</li>
</ol>
<p><strong>Prepare</strong></p>
<p>Directions: With all participants at your table:</p>
<ol>
<li>
<p>Identify any customer needs that are not addressed with the proposed solution.</p>
</li>
<li>
<p>Identify the benefits of your solution.</p>
</li>
<li>
<p>Determine how you will respond to the customer's objections.</p>
</li>
</ol>
<p>Prepare a 15-minute chalk-talk style presentation to the customer.</p>
<h2><a id="user-content-step-3-present-the-solution" class="anchor" aria-hidden="true" href="#step-3-present-the-solution"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Step 3: Present the solution</h2>
<p><strong>Outcome</strong></p>
<p>Present a solution to the target customer audience in a 15-minute chalk-talk format.</p>
<p>Timeframe: 30 minutes</p>
<p><strong>Presentation</strong></p>
<p>Directions:</p>
<ol>
<li>
<p>Pair with another table.</p>
</li>
<li>
<p>One table is the Microsoft team and the other table is the customer.</p>
</li>
<li>
<p>The Microsoft team presents their proposed solution to the customer.</p>
</li>
<li>
<p>The customer makes one of the objections from the list of objections.</p>
</li>
<li>
<p>The Microsoft team responds to the objection.</p>
</li>
<li>
<p>The customer team gives feedback to the Microsoft team.</p>
</li>
<li>
<p>Tables switch roles and repeat Steps 2-6.</p>
</li>
</ol>
<h2><a id="user-content-wrap-up" class="anchor" aria-hidden="true" href="#wrap-up"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Wrap-up</h2>
<p>Timeframe: 15 minutes</p>
<p>Directions: Tables reconvene with the larger group to hear the facilitator/SME share the preferred solution for the case study.</p>
<h2><a id="user-content-additional-references" class="anchor" aria-hidden="true" href="#additional-references"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Additional references</h2>
<table>
<thead>
<tr>
<th></th>
<th align="left"></th>
</tr>
</thead>
<tbody>
<tr>
<td><strong>Description</strong></td>
<td align="left"><strong>Links</strong></td>
</tr>
<tr>
<td>Compliance Commitments</td>
<td align="left"><a href="http://azure.microsoft.com/en-us/support/trust-center/services/" rel="nofollow">http://azure.microsoft.com/en-us/support/trust-center/services/</a></td>
</tr>
<tr>
<td>Azure App Services</td>
<td align="left"><a href="https://azure.microsoft.com/en-us/documentation/articles/app-service-value-prop-what-is/" rel="nofollow">https://azure.microsoft.com/en-us/documentation/articles/app-service-value-prop-what-is/</a></td>
</tr>
<tr>
<td>Azure Service Environment (ASE)</td>
<td align="left"><a href="https://azure.microsoft.com/en-us/documentation/articles/app-service-app-service-environment-intro/" rel="nofollow">https://azure.microsoft.com/en-us/documentation/articles/app-service-app-service-environment-intro/</a></td>
</tr>
<tr>
<td>Integrate ILB ASE with Azure Application Gateway</td>
<td align="left"><a href="https://docs.microsoft.com/en-us/azure/app-service/environment/integrate-with-application-gateway" rel="nofollow">https://docs.microsoft.com/en-us/azure/app-service/environment/integrate-with-application-gateway</a></td>
</tr>
<tr>
<td>Configuring ASE Network Security Groups</td>
<td align="left"><a href="https://docs.microsoft.com/en-us/azure/app-service/environment/network-info#network-security-groups" rel="nofollow">https://docs.microsoft.com/en-us/azure/app-service/environment/network-info#network-security-groups</a></td>
</tr>
<tr>
<td>Geo Distributed Scale with ASE</td>
<td align="left"><a href="https://docs.microsoft.com/en-us/azure/app-service/environment/app-service-app-service-environment-geo-distributed-scale" rel="nofollow">https://docs.microsoft.com/en-us/azure/app-service/environment/app-service-app-service-environment-geo-distributed-scale</a></td>
</tr>
<tr>
<td>Azure Trust Center</td>
<td align="left"><a href="http://azure.microsoft.com/en-us/support/trust-center/" rel="nofollow">http://azure.microsoft.com/en-us/support/trust-center/</a></td>
</tr>
<tr>
<td>Azure PCI Attestation of Compliance</td>
<td align="left"><a href="http://download.microsoft.com/download/7/1/E/71E02A19-D1A4-448F-8CEA-D6A19398ABDA/Azure%20PCI%20AOC%20Feb%202015.pdf" rel="nofollow">http://download.microsoft.com/download/7/1/E/71E02A19-D1A4-448F-8CEA-D6A19398ABDA/Azure%20PCI%20AOC%20Feb%202015.pdf</a></td>
</tr>
<tr>
<td>PCI DSS v3.0</td>
<td align="left"><a href="https://www.pcisecuritystandards.org/documents/PCI_DSS_v3.pdf" rel="nofollow">https://www.pcisecuritystandards.org/documents/PCI_DSS_v3.pdf</a></td>
</tr>
<tr>
<td>Azure Data Factory</td>
<td align="left"><a href="https://azure.microsoft.com/en-us/documentation/articles/data-factory-data-movement-activities/#data-factory-copy-wizard/" rel="nofollow">https://azure.microsoft.com/en-us/documentation/articles/data-factory-data-movement-activities/#data-factory-copy-wizard/</a></td>
</tr>
<tr>
<td>Azure SQL Database</td>
<td align="left"><a href="https://docs.microsoft.com/en-us/azure/sql-database/sql-database-geo-replication-overview/" rel="nofollow">https://docs.microsoft.com/en-us/azure/sql-database/sql-database-geo-replication-overview/</a></td>
</tr>
<tr>
<td>Designing highly available services using Azure SQL Database</td>
<td align="left"><a href="https://docs.microsoft.com/en-us/azure/sql-database/sql-database-designing-cloud-solutions-for-disaster-recovery" rel="nofollow">https://docs.microsoft.com/en-us/azure/sql-database/sql-database-designing-cloud-solutions-for-disaster-recovery</a></td>
</tr>
</tbody>
</table>
<h1><a id="user-content-modern-cloud-apps-whiteboard-design-session-trainer-guide-1" class="anchor" aria-hidden="true" href="#modern-cloud-apps-whiteboard-design-session-trainer-guide-1"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Modern cloud apps whiteboard design session trainer guide</h1>
<h2><a id="user-content-step-1-review-the-customer-case-study-1" class="anchor" aria-hidden="true" href="#step-1-review-the-customer-case-study-1"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Step 1: Review the customer case study</h2>
<ul>
<li>
<p>Check in with your table participants to introduce yourself as the trainer.</p>
</li>
<li>
<p>Ask, "What questions do you have about the customer case study?"</p>
</li>
<li>
<p>Briefly review the steps and timeframes of the whiteboard design session.</p>
</li>
<li>
<p>Ready, set, go! Let the table participants begin.</p>
</li>
</ul>
<h2><a id="user-content-step-2-design-a-proof-of-concept-solution-1" class="anchor" aria-hidden="true" href="#step-2-design-a-proof-of-concept-solution-1"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Step 2: Design a proof of concept solution</h2>
<ul>
<li>
<p>Check in with your tables to ensure that they are transitioning from step to step on time.</p>
</li>
<li>
<p>Provide some feedback on their responses to the business needs and design.</p>
<ul>
<li>Try asking questions first that will lead the participants to discover the answers on their own.</li>
</ul>
</li>
<li>
<p>Provide feedback for their responses to the customer's objections.</p>
<ul>
<li>Try asking questions first that will lead the participants to discover the answers on their own.</li>
</ul>
</li>
</ul>
<h2><a id="user-content-step-3-present-the-solution-1" class="anchor" aria-hidden="true" href="#step-3-present-the-solution-1"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Step 3: Present the solution</h2>
<ul>
<li>
<p>Determine which table will be paired with your table before Step 3 begins.</p>
</li>
<li>
<p>For the first round, assign one table as the presenting team and the other table as the customer.</p>
</li>
<li>
<p>Have the presenting team present their solution to the customer team.</p>
<ul>
<li>
<p>Have the customer team provide one objection for the presenting team to respond to.</p>
</li>
<li>
<p>The presentation, objections, and feedback should take no longer than 15 minutes.</p>
</li>
<li>
<p>If needed, the trainer may also provide feedback.</p>
</li>
</ul>
</li>
</ul>
<h2><a id="user-content-wrap-up-1" class="anchor" aria-hidden="true" href="#wrap-up-1"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Wrap-up</h2>
<ul>
<li>Have the table participants reconvene with the larger session group to hear the facilitator/SME share the following preferred solution.</li>
</ul>
<h2><a id="user-content-preferred-target-audience" class="anchor" aria-hidden="true" href="#preferred-target-audience"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Preferred target audience</h2>
<p>Miles Strom, CEO of Contoso Sports League Association</p>
<p>The primary audience are the business decision makers and technology decision makers. Usually we talk to the infrastructure managers who report to the chief information offer (CIO), or to application sponsors (like a vice president [VP] line of business [LOB], or chief marketing officer [CMO]), or to those that represent the business unit IT or developers that report to application sponsors.</p>
<h2><a id="user-content-preferred-solution" class="anchor" aria-hidden="true" href="#preferred-solution"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Preferred solution</h2>
<p><em>High-level architecture</em></p>
<ol>
<li>
<p>Without getting into the details, (the following sections will address the details), diagram your initial vision for handling the top-level requirements for the e-commerce website, call center website, and inventory lookup process. You will refine this diagram as you proceed.</p>
<p>The Contoso Sports League Association (CSLA) was motivated to move its solution to Azure. After analyzing their requirements across the e-commerce, inventory, and customer support apps, they built their solution from the following high-level designs.</p>
<p>They decided on a solution that at a high level appears as follows:</p>
<p><a target="_blank" rel="noopener noreferrer" href="/microsoft/MCW-Modern-cloud-apps/blob/master/Whiteboard%20design%20session/media/preferred-solution.png"><img src="/microsoft/MCW-Modern-cloud-apps/raw/master/Whiteboard%20design%20session/media/preferred-solution.png" alt="Diagram of the preferred solution. From a high-level, web apps hosting the e-commerce and call center websites access APIs hosted in API Apps, all hosted within an App Service Environment to enable secure communication. Access to call center website available through VPN connection only." title="Preferred solution diagram" style="max-width:100%;"></a></p>
<p>From a high-level, they have Web Apps hosting the e-commerce and call center websites, API Apps hosting web services and Logic Apps hosting integration with SMS. Azure Traffic Manager is used for routing to the appropriate region for high availability. The Web and API Apps can be hosted within an Internal Load Balanced (ILB) App Service Environment (ASE) that enables them to take advantage of Network Security Groups to lock down inbound and outbound communication to the App Services it hosts. A Web Application Firewall (WAF) provided by an Azure App Gateway is hosted in its own subnet and NSGs. Internet traffic flows through the WAF to the e-commerce website (hosted within the ASE), which only allows inbound traffic from the WAF. When customers visit the website, they are presented orders whose data comes from the Offers Service REST API hosted within an API App. Orders come in from customers via the publicly accessible endpoint of the e-commerce website. The credit card is validated as a part of the checkout process by making a call to a third-party payment gateway. Once authorized and payment is captured, the order data is stored in the orders database on SQL DB and the inventory lookup message is sent to the Inventory Lookup queue. An Azure Function hosts the process for creating the PDF receipts for customer purchases. Customers are notified via SMS as their order is processed. This process involves a process running in a Logic App that integrates the SQL DB with a third-party solution for sending SMS text messages.</p>
<p>Inventory lookup requests are queued from the e-commerce website to the queue in Azure Storage queues. The on-premises inventory app reads from this queue to kick off its internal lookup processes and writes the status back to the orders database.</p>
<p>Call center operators access the call center website which, owing to the NSGs configured, is only available across the virtual private network (VPN) connection.</p>
</li>
</ol>
<blockquote>
<p><strong>Note</strong>: The preferred solution is only one of many possible, viable approaches.</p>
</blockquote>
<p><em>Order fulfillment</em></p>
<ol>
<li>
<p>How would you recommend CSLA manage the inventory lookup queues? How would you help CSLA decide between Azure Queues and Service Bus? Be sure to consider details implied by CSLA's requirements such a volume, message lifetime, and sizing. Explain the details of any computations you make.</p>
<p>Given that CSLA did not provide specific requirements that imply a need for the more advanced queuing features that Service Bus offers (such as topics, larger message sizes, longer message lifetime, and so on), CSLA should consider using Azure Queues because it meets their requirements and is the most cost effective.</p>
<p>Their volume is fairly low, at 50K transactions per day, it translates to 50K messages per day. Their actual load per unit of time depends on their actual peak order times that is implied to be akin to 9 a.m.to 9 p.m. EST. Assuming a fairly consistent load during business hours, that equates to about 4,000 messages per hour, which is well below what Azure Queues can support (2,000 messages per second or approximately 120,000 messages per hour for messages sized below 1 kilobyte [KB]).</p>
<p>The case study states that rarely does an inventory lookup message take longer than a few hours and never more than a day. It means that they will never encounter the 7-day lifetime limit required by messages in Azure Queues.</p>
<p>As for the individual message size, since it is just the order ID from the database, it is unlikely to be a field larger than 64 KB (the maximum message size supported by Azure Queues), or even 1 KB (the size at which Azure Queues can handle 2,000 messages per second).</p>
</li>
</ol>
<p><em>Notifications</em></p>
<ol>
<li>
<p>How would you recommend CSLA manage notifying customers as their order in the CSLA orders database is processed? Are there specific Azure services that can be used? Include details on how this would be implemented and integrated into the proposed solution for CSLA?</p>
<p>Contoso can implement a logic app to notify customers of their order status.</p>
<p>The logic app would include a frequency trigger to execute a stored procedure at an interval that will identify orders that should receive SMS notifications and update them as they are processed.</p>
<p>A Twilio connector could act as the action to perform that sends the SMS message when the frequency trigger executes the stored procedure. CSLA would sign up for a free Twilio trial to get an API key. Then they would provision a Twilio connector within the logic app, and add the credentials. Then CSLA would select a Send Message action using data provided in the result set from the stored procedure, specifically the customer's phone number and their first name to include in the message, "Hello Satya, your order has shipped!"</p>
<blockquote>
<p><strong>Note</strong>: It currently involves extending the Logic App code for the Twilio connector.</p>
</blockquote>
</li>
</ol>
<p><em>Offers service</em></p>
<ol>
<li>
<p>Would you propose Contoso use the Azure App Service API app to meet their requirements for the Offers service?</p>
<p>Contoso could meet their requirement of scaling the Offers API independently from the main website by separating it out from the website project into its own Web API project and deploying that project to an Azure App Service API App.</p>
</li>
<li>
<p>If so, what specific configurations would you need to make to support your proposed topology? Specifically, how would you implement the changes and configurations required to allow for inter-app communication between the e-commerce application and the Offers service?</p>
<p>In order for the home page to be able to successfully retrieve the data from the now separate Web API (for example, it is located in another origin), cross origin resource sharing (CORS) would need to be configured.</p>
<p>The API app would need to be enabled for CORS, and the domains used to access the website in the list of allowed origins would need to be listed.</p>
<p>Second, the Web API code would need to be updated to include the System.Web.Http.Cors package, where CORS would need to be enabled in the WebApiConfig.cs file, and the EnableCors attribute would need to be applied to the controllers or actions of the Offers service allowing the aforementioned origins and allow the GET method.</p>
<p>If Contoso chooses to open access of the Offers service for integration by partners they should also consider implementing API management in front of their API App hosted Web API. This would enable them to lock down access by requiring a key, apply policy (such as rate limiting requests), and monitor usage by API customers.</p>
</li>
</ol>
<p><em>Geo-resiliency</em></p>
<ol>
<li>
<p>How would you implement high availability for the orders database to guard against regional data center outages? Be specific on how you would configure SQL Database and Azure Storage_</p>
<p>Azure SQL Database auto-failover groups (in-preview) is a SQL Database feature designed to automatically manage geo-replication relationship, connectivity, and failover at scale. With it, the customers gain the ability to automatically recover multiple related databases in the secondary region after catastrophic regional failures or other unplanned events that result in full or partial loss of the SQL Database service's availability in the primary region. Additionally, they can use the readable secondary databases to offload read-only workloads. Because auto-failover groups involve multiple databases, they must be configured on the primary server. Both primary and secondary servers must be in the same subscription. Auto-failover groups support replication of all databases in the group to only one secondary server in a different region. Active geo-replication, without auto-failover groups, allows up to four secondaries in any region.</p>
<p>Provision the Azure Storage Account with RA-GRS redundancy with a primary and secondary geographic location matching those of the SQL databases, so that in the event of an outage all backup regions have copies of the data. It may affect your choice of SQL database secondary regions because the primary/secondary regions pairs for storage are predefined and not user selectable (e.g., West US primary will use East US as secondary). The replication between the primary storage account region and secondary storage account region is asynchronous to it does not impact the latency of requests made against the primary region, albeit some data loss might be possible if it has not replicated to the secondary region in the event of a disaster.</p>
<p>Finally, deploy copies of the App Services to the backup regions.  You will have to consider a process of how you update these instances when the primary region gets updates. These can initially be deployed to resources with minimal scale out instance sizes, and increased when failover event occurs.</p>
</li>
<li>
<p>What process would you recommend to the customer to failover in the event of an outage, ensuring their web applications and associated Azure services change over to a secondary region?</p>
<p>When using auto-failover groups (in-preview) to manage database recovery and any outage that impacts one or several of the databases in the group results in automatic failover. You can configure the auto-failover policy that best meets your application needs, or you can opt out and use manual activation. Whether you use manual or automatic failover activation, failover switches all secondary databases in the group to primary. After the database failover is completed, the DNS record is automatically updated to redirect the end-points to the new region.</p>
<p>Azure Traffic Manager can be used along with health probes to monitor the App Services hosted within each region. Traffic Manager routes all internet traffic to the Application Gateway WAF, which in turn securely connects into the ILB App Service Environment to the e-commerce website. If the health probes indicate a certain number of failures within a region, it automatically starts routing traffic to the secondary region. This topology can also be used for horizontally scaling out apps located within the geo-distributed ASEs, enabling extreme load handling. For geographic redundancy, the application's resources are deployed to Region 1 and 2.</p>
<p><a target="_blank" rel="noopener noreferrer" href="/microsoft/MCW-Modern-cloud-apps/blob/master/Whiteboard%20design%20session/media/traffic-manager-region-failover.png"><img src="/microsoft/MCW-Modern-cloud-apps/raw/master/Whiteboard%20design%20session/media/traffic-manager-region-failover.png" alt="All internet traffic is routed through Traffic Manager, which will send traffic to a secondary region if the primary region is out" title="Regional failover of app services with Traffic Manager" style="max-width:100%;"></a></p>
<p>Understand that for Azure Storage, the geo-failover process is controlled by Azure. in the event of a major disaster that affects the primary location, Azure will first try to restore the data in the primary location. Failing that, affected customers will be notified via their subscription contact information. As part of the failover, the customer's "account.&lt;service&gt;.core.windows.net" DNS entry would be updated to point from the primary location to the secondary location. In other words, the connection information to Azure Storage does not need to be changed in the application configuration.</p>
</li>
<li>
<p>How long would a failover take and how much data could be lost, in terms of time?</p>
<p>The amount of time a failover takes is the Recovery Time Objective (RTO) and the amount of data loss that might transpire due to any replication latency is the Recovery Point Objective (RPO).</p>
<p>For SQL Database on the Premium Tier, the RTO is less than 30 seconds and the RPO is less than 5 seconds.</p>
<p>For Azure Storage, the RTO is about 24 hours and the RPO is typically less than 15 minutes, although this has no explicit SLA. Given the potentially long RTO and RPO for Azure Storage, Contoso might consider using RA-GRS storage and when a failover happens use the RA-GRS for read and a separate storage account for the writing of new files.</p>
</li>
</ol>
<p><em>Access control</em></p>
<ol>
<li>
<p>With respect to managing access to the call center website, explain how you would recommend Contoso implement a solution that meets their requirements. Be specific about both the implementation and the process you would use to gain Contoso's acceptance of the proposed solution_</p>
<p>Contoso could capitalize on Azure Active Directory to manage the user accounts for the call center staff. They would need to provision an Azure Active Directory tenant in the Premium Tier to provide the branding. Once they have the tenant, they can create login screen branding by using the management portal.</p>
<p><a target="_blank" rel="noopener noreferrer" href="/microsoft/MCW-Modern-cloud-apps/blob/master/Whiteboard%20design%20session/media/image4.png"><img src="/microsoft/MCW-Modern-cloud-apps/raw/master/Whiteboard%20design%20session/media/image4.png" alt="Use the Azure Active Directory Status section to configure custom branding for your company." title="Status section" style="max-width:100%;"></a></p>
<p>From there they specify images for the banner logo, a tile logo, and large illustration, and provide some custom text.</p>
<p><a target="_blank" rel="noopener noreferrer" href="/microsoft/MCW-Modern-cloud-apps/blob/master/Whiteboard%20design%20session/media/image5.png"><img src="/microsoft/MCW-Modern-cloud-apps/raw/master/Whiteboard%20design%20session/media/image5.png" alt="In the Configure company branding blade, select a file to use as the large image that displays to the left of the custom login form." title="Configure company branding blade" style="max-width:100%;"></a></p>
<p>It would result in something like the following for Contoso:</p>
<p><a target="_blank" rel="noopener noreferrer" href="/microsoft/MCW-Modern-cloud-apps/blob/master/Whiteboard%20design%20session/media/image6.png"><img src="/microsoft/MCW-Modern-cloud-apps/raw/master/Whiteboard%20design%20session/media/image6.png" alt="Screenshot of the Contoso sign-in webpage." title="Contoso sign-in webpage" style="max-width:100%;"></a></p>
<p>With respect to addressing Contoso's concerns over foreign hackers, Azure Active Directory can help by identifying logins from multiple geographic locations by using the report "Sign ins from multiple geographies." To demonstrate the function of it to Contoso, one approach to accomplish a login from a foreign IP is to spin up a virtual machine in Azure in a foreign geography, remote desktop into it, open the browser, and navigate to the Contoso admin site and log in. Then log in from a local machine at the same time. Within an hour or two the suspicious login would be listed in the report.</p>
<p>Provided that the call center administrator website is deployed to a web app and that currently anyone listed as a user in Azure Active Directory is a user who should have access to the call center website, since the case study does not stipulate any other more granular requirements, the setup for integrating Azure Active Directory access control requires no code on the part of Contoso, just configuration. This configuration is accomplished using the Azure portal (at <a href="https://portal.azure.com" rel="nofollow">https://portal.azure.com</a>), navigating to the web app, and on the Settings blade selecting Authentication/Authorization. Then in the Authentication/Authorization blade, choose Login with Azure Active Directory, and then configure the Azure Active Directory authentication provider to create a new application in AAD or to use an existing application.</p>
<p><a target="_blank" rel="noopener noreferrer" href="/microsoft/MCW-Modern-cloud-apps/blob/master/Whiteboard%20design%20session/media/image7.png"><img src="/microsoft/MCW-Modern-cloud-apps/raw/master/Whiteboard%20design%20session/media/image7.png" alt="On the Azure Portal, Authentication/Authorization blade, App Service Authorization is set to On, Users must Log in with Azure Active Directory when their request is not authenticated, and Authentication Provider is Azure Active Directory." title="Azure Portal, Authentication/Authorization blade" style="max-width:100%;"></a></p>
<p>Once applied, any access to the call center admin website will automatically be redirected to first log in through Azure Active Directory, and users would need to be created in Azure Active Directory in order to acquire access.</p>
</li>
</ol>
<p><em>Enabling PCI compliance</em></p>
<ol>
<li>
<p>Keeping only the e-commerce website and handling of cardholder data in scope for PCI, consider the following in your design:</p>
<ul>
<li>
<p>Are web apps deployed in Azure App Service Environments an option?</p>
</li>
<li>
<p>Explain how using Azure App Service Environments could address the PCI requirements.</p>
</li>
<li>
<p>Keeping in mind the best choice for securing inbound and outbound traffic for an App Service Environment, detail all inbound and outbound traffic for this solution that allows it to be PCI compliant and allows it to operate within Azure. It should include traffic into and out of the solution, outbound for the e-commerce website, and any other traffic between the apps within the solution.</p>
</li>
<li>
<p>Make sure to describe in detail the network topology you are using.</p>
</li>
<li>
<p>For any inbound and outbound application communications you are securing, please detail the specific mechanisms you will use to do so.</p>
</li>
<li>
<p>If your approach includes configuration scripts, please provide an example of the scripts.</p>
</li>
</ul>
<p>While web apps are certified as PCI compliant, they are not immediately PCI compliant when used by the customer. The PCI requirements 1.2.1, 1.3.3, and 1.3.5 require restricting outbound access to only that which is necessary for the cardholder environment. In the case of CSLA, it means that the only outbound communication allowed should be to Azure (for monitoring) and to the payment gateway. Web apps in the Standard Tier have no mechanism for restricting the outbound traffic.</p>
<p>To remedy this, the web and API App Services should be hosted within an App Service Environment (ASE), using Isolated Tiers. ASE v2 is an App Service feature that provides a fully isolated and dedicated environment for securely running App Service apps at high scale. The ASE itself provides a hosting infrastructure that is deployed within a subnet of a Virtual Network (VNET). The ASE exposes only an Internal Load Balancer (ILB) endpoint for access to the App Service instances it hosts. Then, an Application Gateway of the Web Application Firewall (WAF) SKU should be deployed between the public IP address used by Internet clients to access the website and the ILB ASE endpoint. The ASE and the Application Gateway are deployed to two different subnets. Network Security Groups (NSG) are configured so that the subnet that contains the ASE only allows access from the subnet which contains the Application Gateway.</p>
<p>If restricting the <em>inbound</em> communication (for example limiting by IP, port, protocol) to a web app from the Internet, then you need to:</p>
<ul>
<li>
<p>Provision an ILB ASE, which will create an Azure Virtual Network.</p>
</li>
<li>
<p>Provision the app hosting plan from the ASE pool of resources, in an Isolated Tier.</p>
</li>
<li>
<p>Provision a web app in that App Service plan (no need to create a point-to-site VPN connection for the web app).</p>
</li>
<li>
<p>Provide an internet routable domain name to be used with the app in the ILB App Service Environment.</p>
</li>
<li>
<p>Provide a public DNS name that is used later to point to the Application Gateway.</p>
</li>
<li>
<p>Create a separate subnet from the one the ILB App Service Environment uses. This new subnet will be used for the Azure Application Gateway.</p>
</li>
<li>
<p>Create an Application Gateway inside the separate subnet, and configure it to point to the public web app within the ILB ASE. You must select the WAF tier during creation.</p>
</li>
<li>
<p>Configure the web app to honor the custom domain name and edit the public DNS host name that points to the Application Gateway.</p>
</li>
<li>
<p>Create an NSG and apply it to the virtual network subnet in which the ASE runs (by default the rules included will prevent access from the Internet).</p>
</li>
<li>
<p>The NSG contains a default rule that enables the IPs in the VNet to talk to the ASE subnet. Another default rule enables the load balancer, also known as the public VIP, to communicate with the ASE.</p>
</li>
<li>
<p>Add a rule to the NSG allowing Internet access to the ports 454-455. To see the ports, select App Service Environment &gt; IP addresses.</p>
</li>
</ul>
<p>If you are interested in restricting the <em>outbound</em> communication from a web app to a particular service on the Internet, then you need to:</p>
<ul>
<li>
<p>Configure the ASE, virtual network, Azure Application Gateway, App Service plan, and web app as above.</p>
</li>
<li>
<p>Add two outbound rules to the NSG: one that allows access to permitted service and another that denies all outbound Internet.</p>
</li>
<li>
<p>Configure your outbound security rules to enable network access to the ASE dependencies. If you block any of them, your ASE stops working. Reference: <a href="https://docs.microsoft.com/en-us/azure/app-service/environment/network-info#network-security-groups" rel="nofollow">https://docs.microsoft.com/en-us/azure/app-service/environment/network-info#network-security-groups</a></p>
</li>
</ul>
<p>For CSLA's situation, inbound access to the e-commerce web app does not need to be restricted, but the outbound communication to the payment gateway does need to be restricted.</p>
<p>To meet the antivirus requirement, you need only deploy to Azure since that requirement is itself met by Azure and managed against the virtual machines running your web app on your behalf.</p>
<p>By structuring the web app so all it does it handle the e-commerce transaction, you would meet the server specialization requirement. By capitalizing on web apps, you are inherently addressing the patching requirement since Azure handles that for you (with the exception of any custom code or libraries your application may use).</p>
<p>There is no need to store cardholder data in this scenario, so by having SSL the requirement for protection of data in transit and at rest is also met.</p>
</li>
<li>
<p>Would you recommend they use Azure virtual machines? Why or why not?</p>
<p>While virtual machines could certainly be used to enable a PCI compliant solution, they would not meet the customer requirement for minimizing infrastructure efforts.</p>
</li>
</ol>
<p><em>Data warehouse</em></p>
<ol>
<li>
<p>How would you recommend Contoso implement their data warehouse?</p>
<p>They could use Azure SQL Data Warehouse.</p>
</li>
<li>
<p>How would Contoso schedule nightly data transfers from their OLTP database to their data warehouse?</p>
<p>They would need to provision an instance of Azure Data Factory, and then utilize the Azure Data Factory Copy Wizard to setup a recurring copy from their SQL Database instance to existing tables in their SQL Data Warehouse. They could enable PolyBase in the Copy Wizard to speed up the copying process.</p>
</li>
</ol>
<h2><a id="user-content-checklist-of-preferred-objection-handling" class="anchor" aria-hidden="true" href="#checklist-of-preferred-objection-handling"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Checklist of preferred objection handling</h2>
<ol>
<li>
<p>It is not clear to us from the Azure Trust Center just how Azure helps our solution become PCI compliant.</p>
<p>The Azure Trust Center helps you understand what Azure services have been certified for PCI compliance. For example, the services with which you could build a PCI compliant solution, but it does not describe how you build a PCI compliant solution on Azure. To fully accomplish a PCI compliant solution, you must address the requirements of PCI according to how you are handling cardholder data and the scope of your services. In many cases, Azure's PCI compliance attestations will be enough to satisfy aspects of PCI compliance for your solution, but there are at minimum some items which you must handle as a part of building your application, it is up to you to define and enforce secure password policies.</p>
</li>
<li>
<p>Can we provide a solution that scales to meet our public demand, but is also secure for use by our call center and warehouse?</p>
<p>Yes. Azure can provide a solution that is both scalable and secure.</p>
</li>
<li>
<p>Our PCI compliance requires us to have a quarterly audit and to conduct occasional penetration tests. Is this supported by Azure?</p>
<p>Although prior approval is not required, you may still formally document upcoming penetration testing engagements against Azure by filling out the Azure Service Penetration Testing Notification Form (<a href="https://portal.msrc.microsoft.com/en-us/engage/pentest" rel="nofollow">https://portal.msrc.microsoft.com/en-us/engage/pentest</a>).</p>
<ul>
<li>
<p>Penetration testing must be conducted in accordance with our terms and conditions and comply with the Microsoft Cloud Unified Penetration Testing Rules of Engagement (<a href="https://technet.microsoft.com/mt784683" rel="nofollow">https://technet.microsoft.com/mt784683</a>).</p>
</li>
<li>
<p>Tests that would cause a Denial of Service (DoS) are prohibited.</p>
</li>
</ul>
</li>
<li>
<p>Can we audit the Azure data center?</p>
<p>No. Our independent audits and certifications are shared with customers in lieu of individual customer audits. These certifications and attestations accurately represent how we obtain and meet our security and compliance objectives, and serve as a practical mechanism to validate our promises for all customers. Allowing potentially thousands of customers to audit our services would not be a scalable practice and might compromise security and privacy. Our independent third-party validation program includes audits that are conducted on an annual basis to provide verification of Azure security controls.</p>
</li>
<li>
<p>In the past, we have relied on SOASTA CloudTest to design and execute our web load tests at scale. In moving to Azure, are we still able to capitalize on CloudTest?</p>
<p>Yes. Azure is a supported cloud provider for CloudTest, and your applications hosted in Azure can have load and performance tests conducted against them from SOASTA's global network of cloud resources, while monitoring results in their big-data, real-time streaming analytics platform.</p>
</li>
<li>
<p>Our previous infrastructure did not have great performance monitoring of our websites. What options would you recommend we investigate that would work with our web apps in Azure?</p>
<p>Web apps in Azure include first-class support for both Microsoft Application Insights and NewRelic Application Performance Monitoring, both of which enable you to collect performance telemetry from your web apps as they are running. You can view and analyze traces from both server-side and browser-side telemetry, diagnose errors, and set alerts from within the Azure Portal. Contoso can also capitalize on Log Analytics, a feature of Microsoft Operations Management Suite, by having the Application Insights logs or the Web App Diagnostic logs pushed to a Storage Account and then picked up and made searchable using the Custom Log. Alternately, they can also push their New Relic logs into Log Analytics, as well giving them a single pane of glass to do all of their monitoring through Operations Management Suite.</p>
</li>
<li>
<p>We have heard that Azure's data warehouse can be paused? Does that mean we have to store all our data in Azure Storage first before we can pause the instances and risk losing our data?</p>
<p>SQL Data Warehouse uses storage in two ways, and both enable the data to exist even while the SQL DW instance is paused. For data that is managed by SQL Data Warehouse (e.g., it is inserted directly into relational or columnar tables), it is stored in Azure Premium Storage. For data supporting external tables in SQL DW, this data resides in Azure Standard Storage and is referenced via PolyBase, a component of SQL Data Warehouse.</p>
</li>
<li>
<p>We know it's possible to use Azure SQL Database as our data warehouse. What should we consider when deciding between this and Azure SQL Data Warehouse?</p>
<p>It is true that Azure SQL Database can be used as a data warehouse. This is considered an SMP-based warehouse, or symmetric multiprocessing. Azure SQL Data Warehouse is classified as an MPP-based warehouse, or massively parallel processing. As a general rule, SMP-based warehouses are best suited for small to medium data sets (up to 4-100 TB), while MPP is often used for big data. The delineation between small/medium and big data partly has to do with your organization's definition and supporting infrastructure.</p>
<p>Beyond data sizes, the type of workload pattern is likely to be a greater determining factor. For example, complex queries may be too slow for an SMP solution, and require an MPP solution instead. MPP-based systems are likely to impose a performance penalty with small data sizes, due to the way jobs are distributed and consolidated across nodes. If your data sizes already exceed 1 TB and are expected to continually grow, consider selecting an MPP solution. However, if your data sizes are less than this, but your workloads are exceeding the available resources of your SMP solution, then MPP may be your best option as well. Given this, consider Azure SQL Data Warehouse for small and medium datasets, where the workload is compute and memory intensive.</p>
<p>Azure SQL Data Warehouse provides CSLA with a datastore that contains pre-aggregated data using column names that make sense to business users and analysts, a restructured schema to simplify data relationships, and consolidated tables. It also keeps historical data separate from the source transaction systems for performance reasons.</p>
</li>
</ol>
<h2><a id="user-content-customer-quote-to-be-read-back-to-the-attendees-at-the-end" class="anchor" aria-hidden="true" href="#customer-quote-to-be-read-back-to-the-attendees-at-the-end"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Customer quote (to be read back to the attendees at the end)</h2>
<p>"I can sleep better at night knowing that our e-commerce solution is scalable to handle our biggest days, doesn't sacrifice our required PCI compliance, and actually lowers our infrastructure burden."</p>
<p>Miles Strom, CEO of Contoso Sports League Association</p>
</article>
  </div>

    </div>

  

  <details class="details-reset details-overlay details-overlay-dark">
    <summary data-hotkey="l" aria-label="Jump to line"></summary>
    <details-dialog class="Box Box--overlay d-flex flex-column anim-fade-in fast linejump" aria-label="Jump to line">
      <!-- '"` --><!-- </textarea></xmp> --></option></form><form class="js-jump-to-line-form Box-body d-flex" action="" accept-charset="UTF-8" method="get"><input name="utf8" type="hidden" value="&#x2713;" />
        <input class="form-control flex-auto mr-3 linejump-input js-jump-to-line-field" type="text" placeholder="Jump to line&hellip;" aria-label="Jump to line" autofocus>
        <button type="submit" class="btn" data-close-dialog>Go</button>
</form>    </details-dialog>
  </details>



  </div>
</div>

    </main>
  </div>
  

  </div>

        
<div class="footer container-lg width-full p-responsive" role="contentinfo">
  <div class="position-relative d-flex flex-row-reverse flex-lg-row flex-wrap flex-lg-nowrap flex-justify-center flex-lg-justify-between pt-6 pb-2 mt-6 f6 text-gray border-top border-gray-light ">
    <ul class="list-style-none d-flex flex-wrap col-12 col-lg-5 flex-justify-center flex-lg-justify-between mb-2 mb-lg-0">
      <li class="mr-3 mr-lg-0">&copy; 2019 GitHub, Inc.</li>
        <li class="mr-3 mr-lg-0"><a data-ga-click="Footer, go to terms, text:terms" href="https://github.com/site/terms">Terms</a></li>
        <li class="mr-3 mr-lg-0"><a data-ga-click="Footer, go to privacy, text:privacy" href="https://github.com/site/privacy">Privacy</a></li>
        <li class="mr-3 mr-lg-0"><a data-ga-click="Footer, go to security, text:security" href="https://github.com/security">Security</a></li>
        <li class="mr-3 mr-lg-0"><a href="https://githubstatus.com/" data-ga-click="Footer, go to status, text:status">Status</a></li>
        <li><a data-ga-click="Footer, go to help, text:help" href="https://help.github.com">Help</a></li>
    </ul>

    <a aria-label="Homepage" title="GitHub" class="footer-octicon d-none d-lg-block mx-lg-4" href="https://github.com">
      <svg height="24" class="octicon octicon-mark-github" viewBox="0 0 16 16" version="1.1" width="24" aria-hidden="true"><path fill-rule="evenodd" d="M8 0C3.58 0 0 3.58 0 8c0 3.54 2.29 6.53 5.47 7.59.4.07.55-.17.55-.38 0-.19-.01-.82-.01-1.49-2.01.37-2.53-.49-2.69-.94-.09-.23-.48-.94-.82-1.13-.28-.15-.68-.52-.01-.53.63-.01 1.08.58 1.23.82.72 1.21 1.87.87 2.33.66.07-.52.28-.87.51-1.07-1.78-.2-3.64-.89-3.64-3.95 0-.87.31-1.59.82-2.15-.08-.2-.36-1.02.08-2.12 0 0 .67-.21 2.2.82.64-.18 1.32-.27 2-.27.68 0 1.36.09 2 .27 1.53-1.04 2.2-.82 2.2-.82.44 1.1.16 1.92.08 2.12.51.56.82 1.27.82 2.15 0 3.07-1.87 3.75-3.65 3.95.29.25.54.73.54 1.48 0 1.07-.01 1.93-.01 2.2 0 .21.15.46.55.38A8.013 8.013 0 0016 8c0-4.42-3.58-8-8-8z"/></svg>
</a>
   <ul class="list-style-none d-flex flex-wrap col-12 col-lg-5 flex-justify-center flex-lg-justify-between mb-2 mb-lg-0">
        <li class="mr-3 mr-lg-0"><a data-ga-click="Footer, go to contact, text:contact" href="https://github.com/contact">Contact GitHub</a></li>
        <li class="mr-3 mr-lg-0"><a href="https://github.com/pricing" data-ga-click="Footer, go to Pricing, text:Pricing">Pricing</a></li>
      <li class="mr-3 mr-lg-0"><a href="https://developer.github.com" data-ga-click="Footer, go to api, text:api">API</a></li>
      <li class="mr-3 mr-lg-0"><a href="https://training.github.com" data-ga-click="Footer, go to training, text:training">Training</a></li>
        <li class="mr-3 mr-lg-0"><a href="https://github.blog" data-ga-click="Footer, go to blog, text:blog">Blog</a></li>
        <li><a data-ga-click="Footer, go to about, text:about" href="https://github.com/about">About</a></li>

    </ul>
  </div>
  <div class="d-flex flex-justify-center pb-6">
    <span class="f6 text-gray-light"></span>
  </div>
</div>



  <div id="ajax-error-message" class="ajax-error-message flash flash-error">
    <svg class="octicon octicon-alert" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M8.893 1.5c-.183-.31-.52-.5-.887-.5s-.703.19-.886.5L.138 13.499a.98.98 0 000 1.001c.193.31.53.501.886.501h13.964c.367 0 .704-.19.877-.5a1.03 1.03 0 00.01-1.002L8.893 1.5zm.133 11.497H6.987v-2.003h2.039v2.003zm0-3.004H6.987V5.987h2.039v4.006z"/></svg>
    <button type="button" class="flash-close js-ajax-error-dismiss" aria-label="Dismiss error">
      <svg class="octicon octicon-x" viewBox="0 0 12 16" version="1.1" width="12" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.48 8l3.75 3.75-1.48 1.48L6 9.48l-3.75 3.75-1.48-1.48L4.52 8 .77 4.25l1.48-1.48L6 6.52l3.75-3.75 1.48 1.48L7.48 8z"/></svg>
    </button>
    You can’t perform that action at this time.
  </div>


    
    <script crossorigin="anonymous" integrity="sha512-5KoX4P/b8KhUNxooQhWIxRhCSnSw7EES28pOUYsNnqBMWDDUp6W7cPBV1MTAudwSwofIkpGapbXCgVTgn563Lg==" type="application/javascript" src="https://github.githubassets.com/assets/frameworks-e4aa17e0.js"></script>
    
    <script crossorigin="anonymous" async="async" integrity="sha512-0Igj5XKVaZAYxfH8dn/Vb0uoHCOGYqxJh2pXL3DHrgVOMa1ETDHd6ZMm4C+U4fKv8TiaHP7htak2hJOHwYGDoA==" type="application/javascript" src="https://github.githubassets.com/assets/github-bootstrap-d08823e5.js"></script>
    
    
    
  <div class="js-stale-session-flash flash flash-warn flash-banner" hidden
    >
    <svg class="octicon octicon-alert" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M8.893 1.5c-.183-.31-.52-.5-.887-.5s-.703.19-.886.5L.138 13.499a.98.98 0 000 1.001c.193.31.53.501.886.501h13.964c.367 0 .704-.19.877-.5a1.03 1.03 0 00.01-1.002L8.893 1.5zm.133 11.497H6.987v-2.003h2.039v2.003zm0-3.004H6.987V5.987h2.039v4.006z"/></svg>
    <span class="js-stale-session-flash-signed-in" hidden>You signed in with another tab or window. <a href="">Reload</a> to refresh your session.</span>
    <span class="js-stale-session-flash-signed-out" hidden>You signed out in another tab or window. <a href="">Reload</a> to refresh your session.</span>
  </div>
  <template id="site-details-dialog">
  <details class="details-reset details-overlay details-overlay-dark lh-default text-gray-dark hx_rsm" open>
    <summary role="button" aria-label="Close dialog"></summary>
    <details-dialog class="Box Box--overlay d-flex flex-column anim-fade-in fast hx_rsm-dialog hx_rsm-modal">
      <button class="Box-btn-octicon m-0 btn-octicon position-absolute right-0 top-0" type="button" aria-label="Close dialog" data-close-dialog>
        <svg class="octicon octicon-x" viewBox="0 0 12 16" version="1.1" width="12" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.48 8l3.75 3.75-1.48 1.48L6 9.48l-3.75 3.75-1.48-1.48L4.52 8 .77 4.25l1.48-1.48L6 6.52l3.75-3.75 1.48 1.48L7.48 8z"/></svg>
      </button>
      <div class="octocat-spinner my-6 js-details-dialog-spinner"></div>
    </details-dialog>
  </details>
</template>

  <div class="Popover js-hovercard-content position-absolute" style="display: none; outline: none;" tabindex="0">
  <div class="Popover-message Popover-message--bottom-left Popover-message--large Box box-shadow-large" style="width:360px;">
  </div>
</div>

  <div aria-live="polite" class="js-global-screen-reader-notice sr-only"></div>

  </body>
</html>

