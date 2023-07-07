# Request Response Cycle, APIs, and Postman Lab

You will be working with a free API of your choice for this lab.

## Getting Started

1. Choose an API that has no auth and no CORS from the following list: [public APIs](https://github.com/public-apis/public-apis)
1. Write your answers in this README.md file. Do not delete the questions. Write your answers after the `>`. If you need to write more than one paragraph, add more `>`.

## Instructions

Do your best to answer the questions with specific details when required fully. Writing about code clearly and thoroughly is a critical skill to practice. 

- Which one did you choose? Provide the name and base URL

> https://waifu.pics/docs

- What purpose is this API for (education/fun and games/information/etc.)?

> The purpose of this API is for anime lovers who love anime style artwork.

- What is the URL of the documentation?

> https://api.waifu.pics

- What is the full URL of one endpoint?

>://api.waifu.pics/type/category

- What is a sample of the data from the endpoint (copy and paste results from Postman, ok to shorten if it’s over 100 lines)? Be sure to wrap your answer in the correct formatting for code/JSON.

```json

{"url":"https://i.waifu.pics/AEN0FkJ.jpg"}
```

- What status code did you get back?

> 200 OK

- Click on the **response** headers in Postman. What are the `Content-Type` and `Content-Length` (provide exact values)?

> `application/json; charset=UTF-8`

> `43`

- Summarize the most salient parts of the data you are getting back (for example, Cat facts returns JSON that identifies the source of the cat fact, the cat fact, information about when the fact was created and updated, and the fact itself).

> The summary of the data is a JSON file that holds a single url for a random anime imgae.

- How could you use this data in an application?

> I could imagine integrating this API into an app that shows different styles of anime and classify it by audience.

- What did you like about the documentation?

> The documentation was clear for a first time user compared to the other APIs. You just need to input the type (child friendly/ adult rated) and category.

- What did you find challenging about the documentation?

> I found the documentation confusing when it showed the endpoint references. I didn't know whether to add on top of it, or replace the references at first.

- Did the quality of the documentation impact your decision to use it?

> Yes becasue you only have to input two words respectively. The other ones required a whole but of symbols and words.

- Did you switch which API you chose initially because of its documentation, or did you stick with the one you selected and work your way through it?

> Yes, I wanted to use a gaming API but there weren't much that had no auth and no cors that I was interested in. 

- In your own words, summarize the request-response cycle.

> The request-response cycle sends the request from the user to the server and the server then reponds to the specific request by sending something back to the user.

- In your own words, describe what an API is.

> An API is a way of obtaining information from other places/apps/websites.

- In your own words, describe the purpose of Postman.

> Postman is an application that shows you whether or not your request went well or failed. Also gives you the response in numberical form.
