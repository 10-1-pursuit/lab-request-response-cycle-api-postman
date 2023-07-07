# Request Response Cycle, APIs, and Postman Lab

You will be working with a free API of your choice for this lab.

## Getting Started

1. Choose an API that has no auth and no CORS from the following list: [public APIs](https://github.com/public-apis/public-apis)
1. Write your answers in this README.md file. Do not delete the questions. Write your answers after the `>`. If you need to write more than one paragraph, add more `>`.

## Instructions

Do your best to answer the questions with specific details when required fully. Writing about code clearly and thoroughly is a critical skill to practice. 

- Which one did you choose? Provide the name and base URL

Coinbase since I have to actually google recent APIs
>https://docs.cloud.coinbase.com/
<!-- https://boardgamegeek.com/ -->

<!-- https://api.nasa.gov -->

- What purpose is this API for (education/fun and games/information/etc.)?

> The purpose of this API is educating consumers on their products through use of interactive elements 

- What is the URL of the documentation?

> https://docs.cloud.coinbase.com/
<!-- https://boardgamegeek.com/wiki/page/BGG_XML_API2 -->
<!-- https://api.nasa.gov/techtransfer -->

- What is the full URL of one endpoint?

> https://docs.cloud.coinbase.com/sign-in-with-coinbase/docs/api-users#data-endpoints

- What is a sample of the data from the endpoint (copy and paste results from Postman, ok to shorten if it’s over 100 lines)? Be sure to wrap your answer in the correct formatting for code/JSON.

```json
the body is empty so im not sure how this is going to work

```

- What status code did you get back?

> 403 forbidden 🥲

However, on the actual website, looking through `network` i see some 200 statuses. Though no tab with reqquest types 

- Click on the **response** headers in Postman. What are the `Content-Type` and `Content-Length` (provide exact values)?

> `Content-Type`
this is nonexistent 
> `Content-Length`
🫠
> `content encoding` is gzip though

- Summarize the most salient parts of the data you are getting back (for example, Cat facts returns JSON that identifies the source of the cat fact, the cat fact, information about when the fact was created and updated, and the fact itself).

> The summary of the data is ... that I am trying to access secrets 😭 on Pursuit's cpu
>Coinbase has high security (AS THEY SHOULD) & a whole ton of js files

- How could you use this data in an application?

> I could imagine integrating this API into an app that ... I could really keep some hackers out if I figure out exactly the route CB took

- What did you like about the documentation?

> The documentation was ... formatted in a way that's legible. The design is praactical and the options vary.

- What did you find challenging about the documentation?

> I found the documentation ... challenging when I tried about 4 different APIs and majority gave me issues in regards to needing a CORS after I was already making headway through the questions. 
>It's most challenging given a task and your actual results are the opposite of the expected.

- Did the quality of the documentation impact your decision to use it?

> Yes because... Im intersted to check out the properties on other web pages and see what i can digest 

- Did you switch which API you chose initially because of its documentation, or did you stick with the one you selected and work your way through it?

> Yes I ended up ... switching about 4 times because I wasn't getting sufficient access to make the most out of the asignment

- In your own words, summarize the request-response cycle.

> The request-response cycle ... is a relationship between a webpage/client and the server. Clients make a request and servers respond depending on the available enviornments, or data. 

- In your own words, describe what an API is.

> An API is ... an enviornment with rules of communicating between 2 parties. So, for good vibes , a discussion, if all else fails, a boot to the face

- In your own words, describe the purpose of Postman.

> Postman is an application that ... allows users/devs to see and create the request-response cycle. A user has the option to build, test, or design their own APIs or existing ones.

