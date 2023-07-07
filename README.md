# Request Response Cycle, APIs, and Postman Lab

You will be working with a free API of your choice for this lab.

## Getting Started

1. Choose an API that has no auth and no CORS from the following list: [public APIs](https://github.com/public-apis/public-apis)
1. Write your answers in this README.md file. Do not delete the questions. Write your answers after the `>`. If you need to write more than one paragraph, add more `>`.

## Instructions

Do your best to answer the questions with specific details when required fully. Writing about code clearly and thoroughly is a critical skill to practice. 

- Which one did you choose? Provide the name and base URL

> [Random Cat Pictures & GIFs](https://cataas.com/#/)

- What purpose is this API for (education/fun and games/information/etc.)?

> The purpose of this API is for fun and to spread peace and love (or not) thanks to cats.

- What is the URL of the documentation?

> https://cataas.com/doc.html

- What is the full URL of one endpoint?

> https://cataas.com/cat/gif

- What is a sample of the data from the endpoint (copy and paste results from Postman, ok to shorten if it’s over 100 lines)? Be sure to wrap your answer in the correct formatting for code/JSON.

```json
{
    "tags": [
        "gif"
    ],
    "createdAt": "2022-06-01T22:29:22.394Z",
    "updatedAt": "2022-10-11T07:52:32.761Z",
    "validated": true,
    "owner": "null",
    "file": "6297e84400442300175bb4cc.gif",
    "mimetype": "image/gif",
    "size": 10514671,
    "_id": "ZHrXPVRJniYPR6pp",
    "url": "/cat/ZHrXPVRJniYPR6pp"
}

```

- What status code did you get back?

> 200 OK

- Click on the **response** headers in Postman. What are the `Content-Type` and `Content-Length` (provide exact values)?

> `Content-Type` - image/gif

> `Content-Length` - 1496590

- Summarize the most salient parts of the data you are getting back (for example, Cat facts returns JSON that identifies the source of the cat fact, the cat fact, information about when the fact was created and updated, and the fact itself).

> The summary of the data is JSON that identifies when the image of the cat was created, updated, validity, file name, file type, owner, size in bytes and url path.

- How could you use this data in an application?

> I could imagine integrating this API into an app that generates random cat pictures and gifs. 

- What did you like about the documentation?

> The documentation was entertaining and simple to use. 

- What did you find challenging about the documentation?

> I found the documentation was lacking more detailed information.

- Did the quality of the documentation impact your decision to use it?

> Yes because of it's simple layout.

- Did you switch which API you chose initially because of its documentation, or did you stick with the one you selected and work your way through it?

> Yes starting using a random duck api which wasnt working properly so I had to switch it up.

- In your own words, summarize the request-response cycle.

> The request-response cycle is communication between clients and servers in web applications and APIs.

- In your own words, describe what an API is.

> An API is a set of rules and tools that allow software applications to communicate and interact with each other.

- In your own words, describe the purpose of Postman.

> Postman is an application that is designed to simplify and streamline the process of working with APIs.
