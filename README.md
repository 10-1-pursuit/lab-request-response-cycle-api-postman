# Request Response Cycle, APIs, and Postman Lab

You will be working with a free API of your choice for this lab.

## Getting Started

1. Choose an API that has no auth and no CORS from the following list: [public APIs](https://github.com/public-apis/public-apis)
1. Write your answers in this README.md file. Do not delete the questions. Write your answers after the `>`. If you need to write more than one paragraph, add more `>`.

## Instructions

Do your best to answer the questions with specific details when required fully. Writing about code clearly and thoroughly is a critical skill to practice. 

- Which one did you choose? Provide the name and base URL

> meowfacts
> curl https://meowfacts.herokuapp.com/

- What purpose is this API for (education/fun and games/information/etc.)?

> The purpose of this API is to return a random fact about cats on 
> a GET request.

- What is the URL of the documentation?

> https://github.com/wh-iterabb-it/meowfacts

- What is the full URL of one endpoint?

> curl https://meowfacts.herokuapp.com/?count=3

- What is a sample of the data from the endpoint (copy and paste results from Postman, ok to shorten if it’s over 100 lines)? Be sure to wrap your answer in the correct formatting for code/JSON.

```json
{
    "data": [
        "Mother cats teach their kittens to use the litter box.",
        "The word 'cat' in various languages: French: chat; German: katze; Italian: gatto; Spanish/Portugese: gato; Yiddish: kats; Maltese: qattus; Swedish/Norwegian: katt; Dutch: kat; Icelandic: kottur; Greek: catta; Hindu: katas; Japanese:neko; Polish: kot; Ukranian: kotuk; Hawiian: popoki; Russian: koshka; Latin: cattus; Egyptian: mau; Turkish: kedi; Armenian: Gatz; Chinese: mao; Arabic: biss; Indonesian: kucing; Bulgarian: kotka; Malay: kucing; Thai/Vietnamese: meo; Romanian: pisica; Lithuanian: katinas; Czech: kocka; Slovak: macka; Armenian: gatz; Basque: catua; Estonian: kass; Finnish: kissa; Swahili: paka.",
        "In the Middle Ages, during the Festival of Saint John, cats were burned alive in town squares."
    ]
}

```

- What status code did you get back?

> 200

- Click on the **response** headers in Postman. What are the `Content-Type` and `Content-Length` (provide exact values)?

> `Content-Type` application/json; charset=utf-8

> `Content-Length` 778

- Summarize the most salient parts of the data you are getting back (for example, Cat facts returns JSON that identifies the source of the cat fact, the cat fact, information about when the fact was created and updated, and the fact itself).

> The summary of the data of meowcats it's a JSON that returns one 
> or more facts about cats. The The header provided various
> information such as the size of the file, the date requested,
> the connection type, and the server provider.

- How could you use this data in an application?

> I could imagine integrating this API into a website for 
> entertainment purposes on a website that provides information on 
> the healthcare and training of cats in general as well as 
> specific breeds.

- What did you like about the documentation?

> The documentation was simple and easy to understand. It also
> provided a link to NYC Animal Project, a struggling `no kill'
> cat shelter in NYC that relies entirely on fosters and help
> from small donations.

- What did you find challenging about the documentation?

> I found the documentation was simple and easy to understand, so 
> I had no difficulty using the documentation.

- Did the quality of the documentation impact your decision to use it?

> Partially yes. I enjoy everything involving cats; however, it
> the ease of use that especially made me choose this API.

- Did you switch which API you chose initially because of its documentation, or did you stick with the one you selected and work your way through it?

> I stuck with the one I selected.

- In your own words, summarize the request-response cycle.

> The request-response cycle requires that every request should
> return only one response. There is often many different types
> and many different number of requests happening at the same time
> with websites. Your computer as the client makes a request 
> through the web browser with a URL. The web server then
> responds to your web browser with the requested file/files.
> Depending on whether your request is providing information or
> asking for information, the server's database will store and/or
> retrieve the data in question. 

- In your own words, describe what an API is.

> An API stands for Application Programming Interface. It is a 
> developer resource that allow other applications to understand
> and interact with it and other applications.

- In your own words, describe the purpose of Postman.

> Postman is an application that allows you to view, make changes 
> to, and interact with APIs outside of the browser.
