# Request Response Cycle, APIs, and Postman Lab

You will be working with a free API of your choice for this lab.

## Getting Started

1. Choose an API that has no auth and no CORS from the following list: [public APIs](https://github.com/public-apis/public-apis)
1. Write your answers in this README.md file. Do not delete the questions. Write your answers after the `>`. If you need to write more than one paragraph, add more `>`.

## Instructions

Do your best to answer the questions with specific details when required fully. Writing about code clearly and thoroughly is a critical skill to practice. 

- Which one did you choose? Provide the name and base URL

> https://whiskyhunter.net/api/

- What purpose is this API for (education/fun and games/information/etc.)? Shopping 

> The purpose of this API is:  It's an auction site to purchase rare types of Whiskey, without the huge price tag attached to it. 

- What is the URL of the documentation?

> https://whiskyhunter.net/api/

- What is the full URL of one endpoint? 

> https://whiskyhunter.net/

- What is a sample of the data from the endpoint (copy and paste results from Postman, ok to shorten if it’s over 100 lines)? Be sure to wrap your answer in the correct formatting for code/JSON.

```json


<!DOCTYPE html>
<html lang="en">

<head>
  

<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">
<meta name="format-detection" content="telephone=no"/>

<link rel="icon" type="image/png" href="/static/favicon.png"/>
<link rel="apple-touch-icon" sizes="180x180" href="/static/apple-touch-icon-180x180.png">


  <title>Whisky Hunter API</title>

   <link rel="stylesheet" href="/static/css/api.min.css">
  <link rel="stylesheet" type="text/css" href="/static/drf-yasg/style.css" />
  <link rel="stylesheet" type="text/css" href="/static/drf-yasg/swagger-ui-dist/swagger-ui.css">
  
  <style>
    .swagger-ui .topbar {
      display: none
}
  </style>
  
</head>

<body class="swagger-body page">

  <header>
    
<nav class="navbar navbar-expand-md navbar-dark bg-dark container-fluid">
    <div style="display: none;">
        <svg xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink"><symbol id="box-archive" viewBox="0 0 512 512"><!--! Font Awesome Free 6.0.0 by @fontawesome - https: //fontawesome.com License - https://fontawesome.com/license/free 

```

- What status code did you get back?

> 200

- Click on the **response** headers in Postman. What are the `Content-Type` and `Content-Length` (provide exact values)?

> `Content-Type` text/html; charset=utf-8

> `Content-Length` There is no content length listed.

- Summarize the most salient parts of the data you are getting back (for example, Cat facts returns JSON that identifies the source of the cat fact, the cat fact, information about when the fact was created and updated, and the fact itself).

> The summary of the data is ... Listing the distellery information and the responses for that particular item. 

- How could you use this data in an application? Find which types of rare Whiskey are the most popular. 

> I could imagine integrating this API into an app that ... tracks the best rare whiskeys that are hard to find but high in demand.

- What did you like about the documentation?  I liked the spacing and the asethetics that were selected for this website.

> The documentation was ... HTTPS

- What did you find challenging about the documentation? There's only one version. 

> I found the documentation ... Easy on the eyes. 

- Did the quality of the documentation impact your decision to use it?

> Yes/No because... No, because I want to know more about the rare Whiskeys that are avaiable in the auction. 

- Did you switch which API you chose initially because of its documentation, or did you stick with the one you selected and work your way through it?

> Yes/No I ended up ... No, I only had one type.

- In your own words, summarize the request-response cycle. 

> The request-response cycle is an exchange of data using two computers that are in communication. One initially sends the requesst, while the other responds to that request.

- In your own words, describe what an API is.

> An API is a set of rules and definitions implemented for building a software application.

- In your own words, describe the purpose of Postman.

> Postman is an application that can find API's in a public network. 
