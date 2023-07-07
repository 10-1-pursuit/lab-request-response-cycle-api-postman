# Request Response Cycle, APIs, and Postman Lab

You will be working with a free API of your choice for this lab.

## Getting Started

1. Choose an API that has no auth and no CORS from the following list: [public APIs](https://github.com/public-apis/public-apis)
1. Write your answers in this README.md file. Do not delete the questions. Write your answers after the `>`. If you need to write more than one paragraph, add more `>`.

## Instructions

Do your best to answer the questions with specific details when required fully. Writing about code clearly and thoroughly is a critical skill to practice. 

- Which one did you choose? Provide the name and base URL

Name: Rick and Morty
> https://rickandmortyapi.com/

- What purpose is this API for (education/fun and games/information/etc.)?



> The purpose of this API is to be educational and fun. This data collection is filled with information as seen on the tv show including images, characters, locations and episodes.

- What is the URL of the documentation?

> https://rickandmortyapi.com/documentation

- What is the full URL of one endpoint?

> https://rickandmortyapi.com/api

- What is a sample of the data from the endpoint (copy and paste results from Postman, ok to shorten if it’s over 100 lines)? Be sure to wrap your answer in the correct formatting for code/JSON.

```json
{
    "characters": "https://rickandmortyapi.com/api/character",
    "locations": "https://rickandmortyapi.com/api/location",
    "episodes": "https://rickandmortyapi.com/api/episode"
}

```

- What status code did you get back?

> 200 ok

- Click on the **response** headers in Postman. What are the `Content-Type` and `Content-Length` (provide exact values)?

> `Content-Type` 
166
> `Content-Length`
application/json; charset=utf-8

- Summarize the most salient parts of the data you are getting back (for example, Cat facts returns JSON that identifies the source of the cat fact, the cat fact, information about when the fact was created and updated, and the fact itself).

> The summary of the data is ...
The rest URL (https://rickandmortyapi.com/api) provides a json file with an object of 3 URL links to Characters, locations, and episodes from the tv show.

- How could you use this data in an application?

> I could imagine integrating this API into an app that tracks and records information about each character. A wiki for each character that consists of the characters' ID, name, species, origin, gender, what episode they first were featured, time when they were created in the database, link to their last known location endpoint, episode list, and 300x300 images. For the Location page, it gives the location id, name, type of dimension, which characters appeared in that dimension, and the links to the residents (characters) that live in that dimension.

- What did you like about the documentation?

> The documentation was very well organized. I could see exactly what was featured inside the API, the different endpoints for Rest, GraphQL etc. It showed various code blocks for filtering characters, locations and episodes by ID, name, type of dimension, by single or multiple characters, locations, or episodes. It also showed the different libraries of languages and links to the languages, which include PHP, Python, Javascript, Java, Dust, Elixir, Ruby and Rust. 

- What did you find challenging about the documentation?

> I found the documentation confusing at first because I wasn't sure where to find the URL endpoint. I was informed that GraphQL is more complicated than Rest,and was recommended to use.

- Did the quality of the documentation impact your decision to use it?

> Yes, because this particular API references a Cartoon show that I enjoy watching. The documentation was super easy to navigate through. It has an index/menu on the left side that makes it accessible. Then the documentation page is long form and goes into detail of each feature, has an introduction, explains libraries and what they are, shows the codeblock for each function/method for searching through the database, and it also shows Key/Type and description for how pagination works while retrieving data.

- Did you switch which API you chose initially because of its documentation, or did you stick with the one you selected and work your way through it?

>No I ended up sticking with the Rick and Morty API because of the context, and the documentation helped me settle with this particular API.

- In your own words, summarize the request-response cycle.

> The request-response cycle is how a user gains access to a website after entering a URL address. The user enters a URL address into a web browser such as Chrome, Firefox, or Bing and that http request is sent to a webserver. A server receives the request and runs an application to review and process the request. The server translates and executes the request into an HTTP response and the user recieves the response in the form they requested. 


- In your own words, describe what an API is.

> An API stands for Application Programming Interface and it acts as an intermediary between two or more unrelated applications. These applications interact in a way that utilize requests and responses, and allows users access to coding blocks, algorithms, protocols, and data collections. These resources are critical for developers to create applications. 

- In your own words, describe the purpose of Postman.

> Postman is an application that acts as a HUB and a workspace for developers to test APIs, build, package and share APIs with other software developers.
