# Request Response Cycle, APIs, and Postman Lab

You will be working with a free API of your choice for this lab.

## Getting Started

1. Choose an API that has no auth and no CORS from the following list: [public APIs](https://github.com/public-apis/public-apis)
1. Write your answers in this README.md file. Do not delete the questions. Write your answers after the `>`. If you need to write more than one paragraph, add more `>`.

## Instructions

Do your best to answer the questions with specific details when required fully. Writing about code clearly and thoroughly is a critical skill to practice. 

- Which one did you choose? Provide the name and base URL

> http:// GET https://emojihub.yurace.pro/api/random

- What purpose is this API for (education/fun and games/information/etc.)?

> The purpose of this apI is get random emojis

- What is the URL of the documentation?

> https://github.com/cheatsnake/emojihub

- What is the full URL of one endpoint?

> http://https://emojihub.yurace.pro/api/

- What is a sample of the data from the endpoint (copy and paste results from Postman, ok to shorten if it’s over 100 lines)? Be sure to wrap your answer in the correct formatting for code/JSON.

```json
{
    "name": "hugging face",
    "category": "smileys and people",
    "group": "face positive",
    "htmlCode": ["&#129303;"],
    "unicode": ["U+1F917"]
}

```

- What status code did you get back?

> 200

- Click on the **response** headers in Postman. What are the `Content-Type` and `Content-Length` (provide exact values)?

> `Content-Type` application/json

> `Content-Length` 142

- Summarize the most salient parts of the data you are getting back (for example, Cat facts returns JSON that identifies the source of the cat fact, the cat fact, information about when the fact was created and updated, and the fact itself).

> The summary of the data is ... json file including  object with key value pairs of emoji name : hugging hands , emoji catergory : smiles and people  , emoji group: face postiive , emoji htmlcode : "htmlCode": [&#129303;]", emoji unicode ""unicode": [U+1F917]",

- How could you use this data in an application?

> I could imagine integrating this API into an app that .. tells people a random fact   your birthday 

- What did you like about the documentation?

> The documentation was ... it was informative 

- What did you find challenging about the documentation?

> I found the documentation ... accessing the api endpoints

- Did the quality of the documentation impact your decision to use it?

>  yes it did easy to you 

- Did you switch which API you chose initially because of its documentation, or did you stick with the one you selected and work your way through it?

> Yes/No I ended up ... yes it was in russian 

- In your own words, summarize the request-response cycle.

> The request-response cycle ... 

- In your own words, describe what an API is.

> An API is ... Application Programming Interface

- In your own words, describe the purpose of Postman.

> Postman is an application that ... to get details of an api 
