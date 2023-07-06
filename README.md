# Request Response Cycle, APIs, and Postman Lab

You will be working with a free API of your choice for this lab.

## Getting Started

1. Choose an API that has no auth and no CORS from the following list: [public APIs](https://github.com/public-apis/public-apis)
1. Write your answers in this README.md file. Do not delete the questions. Write your answers after the `>`. If you need to write more than one paragraph, add more `>`.

## Instructions

Do your best to answer the questions with specific details when required fully. Writing about code clearly and thoroughly is a critical skill to practice. 

- Which one did you choose? Provide the name and base URL

> https://uselessfacts.jsph.pl/ - Useless Random Facts

- What purpose is this API for (education/fun and games/information/etc.)?

> The purpose of this API is for entertainment

- What is the URL of the documentation?

> https://uselessfacts.jsph.pl/api/v2/facts/random?language=en

- What is the full URL of one endpoint?

> [http://GET /api/v2/facts/random](https://uselessfacts.jsph.pl//api/v2/facts/random)

- What is a sample of the data from the endpoint (copy and paste results from Postman, ok to shorten if it’s over 100 lines)? Be sure to wrap your answer in the correct formatting for code/JSON.

```json
{
    "id": "c5e8d5dee90922fb985462ff04f849cf",
    "text": "The average lead pencil will draw a line 35 miles long or write approximately 50,000 English words.  More than 2 billion pencils are manufactured each year in the United States. If these were laid end to end they would circle the world nine times.",
    "source": "djtech.net",
    "source_url": "http://www.djtech.net/humor/useless_facts.htm",
    "language": "en",
    "permalink": "https://uselessfacts.jsph.pl/api/v2/facts/c5e8d5dee90922fb985462ff04f849cf"
}

```

- What status code did you get back?

> 200 OK

- Click on the **response** headers in Postman. What are the `Content-Type` and `Content-Length` (provide exact values)?

> `Content-Type` application/json; charset=UTF-8

> `Content-Length` 488

- Summarize the most salient parts of the data you are getting back (for example, Cat facts returns JSON that identifies the source of the cat fact, the cat fact, information about when the fact was created and updated, and the fact itself).

> The summary of the data is an id for the fact, the fact, source and source-url, the language and permalink.

- How could you use this data in an application?

> I could imagine integrating this API into an app that shows you a fact while it loads.

- What did you like about the documentation?

> The documentation was interesting and not overwhelming with information.

- What did you find challenging about the documentation?

> I found the documentation to be a bit challenging to navigate at first.

- Did the quality of the documentation impact your decision to use it?

> Yes because the documentation was not overwhelming so I'm more inclined to use it.

- Did you switch which API you chose initially because of its documentation, or did you stick with the one you selected and work your way through it?

> Yes I ended up switching because the first API link gave me a security warning.

- In your own words, summarize the request-response cycle.

> The request-response cycle is when the server recieves a request and builds a response with the requested information. The built response is then sent back in the resquested format to be rendered by the user. 

- In your own words, describe what an API is.

> An API is software information used to interact between applications or websites. They are an accessible way to extract and share data.

- In your own words, describe the purpose of Postman.

> Postman is an application that allows users to build and use APIs.
