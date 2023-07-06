# Request Response Cycle, APIs, and Postman Lab

You will be working with a free API of your choice for this lab.

## Getting Started

1. Choose an API that has no auth and no CORS from the following list: [public APIs](https://github.com/public-apis/public-apis)
1. Write your answers in this README.md file. Do not delete the questions. Write your answers after the `>`. If you need to write more than one paragraph, add more `>`.

## Instructions

Do your best to answer the questions with specific details when required fully. Writing about code clearly and thoroughly is a critical skill to practice. 

- Which one did you choose? Provide the name and base URL

> https://www.dnd5eapi.co/

- What purpose is this API for (education/fun and games/information/etc.)?

> This API is for fun/entertainment purposes, providing users with information about spells, classes, etc from the game dungeons and dragons.

- What is the URL of the documentation?

> https://www.dnd5eapi.co/docs/

- What is the full URL of one endpoint?

> http://https://www.dnd5eapi.co/api/ability-scores/cha

- What is a sample of the data from the endpoint (copy and paste results from Postman, ok to shorten if it’s over 100 lines)? Be sure to wrap your answer in the correct formatting for code/JSON.

```json
{
    "index": "cha",
    "name": "CHA",
    "full_name": "Charisma",
    "desc": [
        "Charisma measures your ability to interact effectively with others. It includes such factors as confidence and eloquence, and it can represent a charming or commanding personality.",
        "A Charisma check might arise when you try to influence or entertain others, when you try to make an impression or tell a convincing lie, or when you are navigating a tricky social situation. The Deception, Intimidation, Performance, and Persuasion skills reflect aptitude in certain kinds of Charisma checks."
    ],
    "skills": [
        {
            "name": "Deception",
            "index": "deception",
            "url": "/api/skills/deception"
        },
        {
            "name": "Intimidation",
            "index": "intimidation",
            "url": "/api/skills/intimidation"
        },
        {
            "name": "Performance",
            "index": "performance",
            "url": "/api/skills/performance"
        },
        {
            "name": "Persuasion",
            "index": "persuasion",
            "url": "/api/skills/persuasion"
        }
    ],
    "url": "/api/ability-scores/cha"
}

```

- What status code did you get back?

> 200 OK

- Click on the **response** headers in Postman. What are the `Content-Type` and `Content-Length` (provide exact values)?

> `Content-Type` application/json; charset=utf-8

> `Content-Length` 899

- Summarize the most salient parts of the data you are getting back (for example, Cat facts returns JSON that identifies the source of the cat fact, the cat fact, information about when the fact was created and updated, and the fact itself).

> The summary of the data is information about character stats and skills which is returned from a JSON.

- How could you use this data in an application?

> I could imagine integrating this API into an app that generates random dungeon and dragon stats for the user

- What did you like about the documentation?

> The documentation was informative and not too long.

- What did you find challenging about the documentation?

> I found the documentation not challenging.

- Did the quality of the documentation impact your decision to use it?

> Yes because it made it easy to use.

- Did you switch which API you chose initially because of its documentation, or did you stick with the one you selected and work your way through it?

> Yes I started with a cat fact api but i couldnt get the information as easily so i switched to this one.

- In your own words, summarize the request-response cycle.

> The request-response cycle is a process in which the web browser or app sends a request typically using HTTP method and a url, the server receives the request, processes it based on the parameters provided and generates a response. The status code is included along with headers and a body that contains the requested data.

- In your own words, describe what an API is.

> An API is a set of protocols that allows different software systems to communicate and interact with each other.

- In your own words, describe the purpose of Postman.

> Postman is an application that provides a user-friendly interface mainly for developers to interact with APIs. It allows us to send HTTP requests to APIs, and get the data along with testing the functionality.
