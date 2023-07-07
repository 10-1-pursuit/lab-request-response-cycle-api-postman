# Request Response Cycle, APIs, and Postman Lab

You will be working with a free API of your choice for this lab.

## Getting Started

1. Choose an API that has no auth and no CORS from the following list: [public APIs](https://github.com/public-apis/public-apis)
1. Write your answers in this README.md file. Do not delete the questions. Write your answers after the `>`. If you need to write more than one paragraph, add more `>`.

## Instructions

Do your best to answer the questions with specific details when required fully. Writing about code clearly and thoroughly is a critical skill to practice. 

- Which one did you choose? Provide the name and base URL

> http://api.twitter.com/2

- What purpose is this API for (education/fun and games/information/etc.)?

> This API enables programmatic access to Twitter in unique and advanced ways. Taping into core elements of Twitter like: Tweets, Direct Messages, Spaces, Lists, users, and more.

- What is the URL of the documentation?

> https://developer.twitter.com/en/docs

- What is the full URL of one endpoint?

> https://api.twitter.com/2/tweets/:id

- What is a sample of the data from the endpoint (copy and paste results from Postman, ok to shorten if it’s over 100 lines)? Be sure to wrap your answer in the correct formatting for code/JSON.

```json
{
    "errors": [
        {
            "detail": "Could not find user with username: [TwitterDec].",
            "title": "Not Found Error",
            "resource_type": "user",
            "parameter": "username",
            "value": "TwitterDec",
            "type": "https://api.twitter.com/2/problems/resource-not-found"
        }
    ]
}

```

- What status code did you get back?

> 200 Ok

- Click on the **response** headers in Postman. What are the `Content-Type` and `Content-Length` (provide exact values)?

> `Content-Type` application/json; charset=utf-8

> `Content-Length` 184

- Summarize the most salient parts of the data you are getting back (for example, Cat facts returns JSON that identifies the source of the cat fact, the cat fact, information about when the fact was created and updated, and the fact itself).

> The summary of the data depends on your endpoint but essentially plenty information on twitter data can be pulled from simple tweets to their posted date, numbr of characters, authors, etc.

- How could you use this data in an application?

> I could imagine integrating this API into an app that to help people interact with twitter without ever having to go on their website or app. Most likely companies that need to maintain and post on several social media front all at once could benefit on having one app integrated with several social media API services.

- What did you like about the documentation?

> The documentation was very easy to understand and beginner friendly.

- What did you find challenging about the documentation?

> I found the documentation not very clear on must do or step by step initial setup. It assumes you know what tools or libraries are best suited for your task before it even suggest a beginner friendly way to start based on what you are trying to achieve.

- Did the quality of the documentation impact your decision to use it?

> No because i had my sight on the API a while back.

- Did you switch which API you chose initially because of its documentation, or did you stick with the one you selected and work your way through it?

> Yes I ended up using twitter after i tried sport data but couldn't either figure out if they were still maintained or if the documentation was bad.

- In your own words, summarize the request-response cycle.

> The request-response cycle 

- In your own words, describe what an API is.

> An API is a portal for other programs to communicate with 

- In your own words, describe the purpose of Postman.

> Postman is an application that help with understanding and making it easy for a developper to work with different APIs.
