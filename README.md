# Request Response Cycle, APIs, and Postman Lab

You will be working with a free API of your choice for this lab.

## Getting Started

1. Choose an API that has no auth and no CORS from the following list: [public APIs](https://github.com/public-apis/public-apis)
1. Write your answers in this README.md file. Do not delete the questions. Write your answers after the `>`. If you need to write more than one paragraph, add more `>`.

## Instructions

Do your best to answer the questions with specific details when required fully. Writing about code clearly and thoroughly is a critical skill to practice. 

- Which one did you choose? Provide the name and base URL

> http://dnd5eapi.co/api/

- What purpose is this API for (education/fun and games/information/etc.)?

> The purpose of this API is: Is an

- What is the URL of the documentation?

> http://dnd5eapi.co/docs/

- What is the full URL of one endpoint?

> http://dnd5eapi.co/api/languages/abyssal

- What is a sample of the data from the endpoint (copy and paste results from Postman, ok to shorten if it’s over 100 lines)? Be sure to wrap your answer in the correct formatting for code/JSON.

```json
{
    "index": "abyssal",
    "name": "Abyssal",
    "type": "Exotic",
    "typical_speakers": [
        "Demons"
    ],
    "script": "Infernal",
    "url": "/api/languages/abyssal"
}

```

- What status code did you get back?

> 200 Ok

- Click on the **response** headers in Postman. What are the `Content-Type` and `Content-Length` (provide exact values)?

> `application/json; charset=utf-8` The media's resource type

> `133` The size of the entity body in bytes.

- Summarize the most salient parts of the data you are getting back (for example, Cat facts returns JSON that identifies the source of the cat fact, the cat fact, information about when the fact was created and updated, and the fact itself).

> The summary of the data is ... "a JSON file that has that usually includes a description, a resource index for shorthand searching. the URAL of the referenced resource and other relevant information."

- How could you use this data in an application?

 * This would be a great for a character builder application. A fill in the blank sorta deal where you could build out your character and update it with commonly used spells and monsters encountered. 

> I could imagine integrating this API into an app that ...
   Allowed you to create a character and keep him on deck with his spells and wepons and tools attached and easily changed and acceptable. 

- What did you like about the documentation?

> The documentation was-well laid out and broken down. accessable in its components.

- What did you find challenging about the documentation?

> I found the documentation ... left much to be desired. Pictues or more detailed. The world of DND is SO exspansive and im superprised its not as dense. 

- Did the quality of the documentation impact your decision to use it?

>  Yes. I very much so. I would have to look for more resources if I wanted to create an app for my party.

- Did you switch which API you chose initially because of its documentation, or did you stick with the one you selected and work your way through it?

> No ...I stuck with it, so i could get a full(er) understanding of it and the way it works. My API is simple and you can only use GET with it, so i found it was easier to use the downloaded chrome extension to read the json data. If i could POST or do other things with the API i chose maybe it would be more useful.

- In your own words, summarize the request-response cycle.

> The request-response cycle ...
It's a one stop deal that you make over and over. You can make only one request and get only one response. Im not sure how this works when we intergrate them into website but ill find out tomorrow i guess. 

- In your own words, describe what an API is.

> An API is ... Access to another applications database. A middle man; without the clumsy of loading another website. 

- In your own words, describe the purpose of Postman.

> Postman is an application that ... It gives you cleaner access to api's and a more structed use of the HTTP Verbs.
