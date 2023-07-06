# Request Response Cycle, APIs, and Postman Lab

You will be working with a free API of your choice for this lab.

## Getting Started

1. Choose an API that has no auth and no CORS from the following list: [public APIs](https://github.com/public-apis/public-apis)
1. Write your answers in this README.md file. Do not delete the questions. Write your answers after the `>`. If you need to write more than one paragraph, add more `>`.

## Instructions

Do your best to answer the questions with specific details when required fully. Writing about code clearly and thoroughly is a critical skill to practice. 

- Which one did you choose? Provide the name and base URL

>I chose Openwhyd API
> https://openwhyd.org/

- What purpose is this API for (education/fun and games/information/etc.)?

> The purpose of this API is for entertainment. It allows users to create playlists of music from different streaming platforms and discover the music posted by other users.

- What is the URL of the documentation?

> https://openwhyd.org/

- What is the full URL of one endpoint?

>{"endpoints":[{"url":"https:\/\/a.nel.cloudflare.com\/report\/v3?s=nVGNkzNOa0W9ZqN0z%2F%2FmM6f6Xew6nl%2FEQ%2ByzShnrceJYJKm9v1HRlrMQNP3tCpIVzOXRG3vwNJmQ%2FTPZUoygyDUwgo2xVjr%2B68f17odO%2BUTr95kWKBG4ECHF6yRmUe8%3D"}],"group":"cf-nel","max_age":604800}

- What is a sample of the data from the endpoint (copy and paste results from Postman, ok to shorten if it’s over 100 lines)? Be sure to wrap your answer in the correct formatting for code/JSON.

```html
<!DOCTYPE html>
<html lang="en">

<head prefix="og: http://ogp.me/ns# fb: http://ogp.me/ns/fb# whydapp: http://ogp.me/ns/fb/whydapp#">
	<meta charset="utf-8" />
	<meta name="google-site-verification" content="mmqzgEU1bjTfJ__nW6zioi7O9vuur1SyYfW44DH6ozg" />
	<meta name="apple-itunes-app" content="app-id=874380201, app-argument=whyd://app?href=http://openwhyd.org/">
	<link rel="image_src" href="https://openwhyd.org/images/logo-black-square-smaller.png" />
	<meta name="description" content="Discover and collect music gems from Youtube, Soundcloud, Deezer and more" />
	<meta name="keywords"
		content="discover, music, curation, streaming, tracks, youtube, soundcloud, bandcamp, playlists, play, free" />
	<meta name="twitter:card" content="summary" />
	<meta name="twitter:site" content="@open_whyd" />
	<meta property="og:image" content="https://openwhyd.org/images/logo-black-square-smaller.png" />
	<meta property="og:description"
		content="Discover and collect music gems from Youtube, Soundcloud, Deezer and more" />
	<meta property="fb:app_id" content="169250156435902" />
	<meta property="fb:admins" content="510739408" />
	<meta property="og:type" content="website" />
	<meta property="og:url" content="https://openwhyd.org/" />
	<link href="/favicon.ico" rel="shortcut icon" type="image/x-icon" />
	<link href="/favicon.png" rel="icon" type="image/png" />
	<link href='//fonts.googleapis.com/css?family=Varela+Round' rel='stylesheet' type='text/css'>
	<link href='//fonts.googleapis.com/css?family=Varela' rel='stylesheet' type='text/css'>
	<link rel="search" type="application/opensearchdescription+xml" title="Whyd"
		href="https://openwhyd.org/html/opensearch.xml">
	<link rel="chrome-webstore-item" href="https://chrome.google.com/webstore/detail/foohaghobcolamikniehcnnijdjehfjk">

	<script>
		(function(h,o,u,n,d) {
    h=h[d]=h[d]||{q:[],onReady:function(c){h.q.push(c)}}
    d=o.createElement(u);d.async=1;d.src=n
    n=o.getElementsByTagName(u)[0];n.parentNode.insertBefore(d,n)
  })(window,document,'script','https://www.datadoghq-browser-agent.com/datadog-rum.js','DD_RUM')
  DD_RUM.onReady(function() {
    DD_RUM.init({
      clientToken: 'pub8eeb8858448e59bbb3db9e58371cc3d2',
      applicationId: '5897e862-9942-4dd4-98a7-87a51a93fb91',
      site: 'datadoghq.com',
      service: 'openwhyd.org',
      //  env: 'production',
      //  version: '1.0.0',
      sampleRate: 100,
      trackInteractions: true,
    })
  })
	</script>
	<script>
		window.user = {
  id: undefined,
  name: '',
  fbId: undefined,
  handle: '',
  pref: {},
  lastFm: undefined
};
  window.playTrack = window.playTrack || function(){};
	</script>
	<script src="/js/whydtr.js?1.49.2"></script>
	<link rel="stylesheet" type="text/css" href="/css/cookieconsent2-3.0.3.min.css" />
	<script src="/js/cookieconsent2-3.0.3.min.js"></script>
	<script>
		/* generated from https://cookieconsent.insites.com/download/ */
  window.addEventListener("load", function(){
    window.cookieconsent.initialise({
      palette: { popup: { background: "#000" }, button: { background: "#f1d600" } }
    })
  });
	</script>
	<title>Openwhyd – Discover and collect the best music tracks from the web</title>
	<link href="/css/common.css?1.49.2" rel="stylesheet" type="text/css" />
	<link href="/css/browse.css?1.49.2" rel="stylesheet" type="text/css" />
	<link href="/css/tipsy.css?1.49.2" rel="stylesheet" type="text/css" />
	<link href="/css/userProfileV2.css?1.49.2" rel="stylesheet" type="text/css" />
	<link href="/css/userPlaylistV2.css?1.49.2" rel="stylesheet" type="text/css" />
	<link href="/css/dlgEditProfileCover.css?1.49.2" rel="stylesheet" type="text/css" />
	<script src="/js/jquery-1.10.2.min.js"></script>
	<script src="/js/jquery-migrate-1.2.1.js"></script>
	<script type="text/javascript" src="/js/jquery.history.js"></script>
	<script src="/js/soundmanager2-nodebug-jsmin.js"></script>
	<script>
		soundManager.setup({url: "/swf/", flashVersion: 9, onready: function() {soundManager.isReady=true;}});
	</script>
</head>

<body class="pgStream pgFullStream pgWithSideBar home visitor">
	<div id="fb-root"></div>
	<!--[if lt IE 8]>
<div class="topWarning">Warning: your web browser is not supported by Openwhyd. Please upgrade to a modern browser.</div>
<![endif]-->


```

- What status code did you get back?

> 200

- Click on the **response** headers in Postman. What are the `Content-Type` and `Content-Length` (provide exact values)?

> `Content-Type` = text/html; charset=utf-8

> `Content-Length` = N/A - I was unable to find content length

- Summarize the most salient parts of the data you are getting back (for example, Cat facts returns JSON that identifies the source of the cat fact, the cat fact, information about when the fact was created and updated, and the fact itself).

> The summary of the data is openwyd.org can be used to find music from different music streaming platforms (ex: YouTube, Soundcloud,Spotify, etc.) and consolidate it in one place. You can also create playlists as well as search and download playlists created by other users on streaming platforms. 

- How could you use this data in an application?

> I could imagine integrating this API into an app that collects music and allows users to create and share playlists. Sort of like my own version of YouTube maybe geared towards parents to compile music from Disney movies, or kid shows to play for their children. 

- What did you like about the documentation?

> The documentation was in html, so I was able to read and understand what it was talking about a tiny bit. For instance I saw some createElements along with some addEventListeners so that was familiar since we just went over those things in class, as well as used on our last project.

- What did you find challenging about the documentation?

> I found the documentation challenging because it was a lot to read through. There was still a lot of the information that I did not quite understand what it meant and if I was even looking at the right documentation at first. After skimming through it more, I was able to identify a few familar elements.

- Did the quality of the documentation impact your decision to use it?

> No because I was not sure what was needed in the documentation to complete this assignment. Once I started to understand and answer the questions, the documentation seemed sufficient.

- Did you switch which API you chose initially because of its documentation, or did you stick with the one you selected and work your way through it?

> I did not switch the API I chose initially. I kept the original one I was interested in and decided to work through it. I'm glad I did because I was able to see a few things I understood and google some things I didn't understand but wanted more information on. 

- In your own words, summarize the request-response cycle.

> The request-response cycle is similar to ordering food at a restaurant. You/client asks/requests the waiter/server to make your food order/request. The waiter/server then takes/listens for your food order/request. Lastly the waiter/server gives/response you/client your food order/request.

- In your own words, describe what an API is.

> An API is a way for applications/programs to interact/communicate with eachother. 

- In your own words, describe the purpose of Postman.

> Postman is an application that allows us to work with API's a little easier. 
