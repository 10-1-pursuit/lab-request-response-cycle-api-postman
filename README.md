# Request Response Cycle, APIs, and Postman Lab

jackie
You will be working with a free API of your choice for this lab.

## Getting Started

1. Choose an API that has no auth and no CORS from the following list: [public APIs](https://github.com/public-apis/public-apis)
1. Write your answers in this README.md file. Do not delete the questions. Write your answers after the `>`. If you need to write more than one paragraph, add more `>`.

## Instructions

Do your best to answer the questions with specific details when required fully. Writing about code clearly and thoroughly is a critical skill to practice.

- Which one did you choose? Provide the name and base URL

> https://www.wwe.com/worldwrestlingentertainment

- What purpose is this API for (education/fun and games/information/etc.)?

> The purpose of this API is for wrestling entertainment purpose.

- What is the URL of the documentation?

> https://www.wwe.com/

- What is the full URL of one endpoint?

> https://www.wwe.com/superstars

- What is a sample of the data from the endpoint (copy and paste results from Postman, ok to shorten if it’s over 100 lines)? Be sure to wrap your answer in the correct formatting for code/JSON.

```json
(function(i,s,o,g,r,a,m){i['GoogleAnalyticsObject'
    ]=r;i[r
    ]=i[r
    ]||function(){
	  (i[r
        ].q=i[r
        ].q||[]).push(arguments)
    },i[r
    ].l=1*new Date();a=s.createElement(o),
	  m=s.getElementsByTagName(o)[
        0
    ];a.async=1;a.src=g;m.parentNode.insertBefore(a,m)
})(window,document,'script',' //www.google-analytics.com/analytics.js','ga');

	  ga('create', 'UA-30947115-5', 'auto');
	  ga('send', 'pageview');



```

- What status code did you get back?

> 200

- Click on the **response** headers in Postman. What are the `Content-Type` and `Content-Length` (provide exact values)?

> `Content-Type` text html

> `Content-Length`4419

- Summarize the most salient parts of the data you are getting back (for example, Cat facts returns JSON that identifies the source of the cat fact, the cat fact, information about when the fact was created and updated, and the fact itself).

> The summary of the data is to provide the source of the cat fact, timestamps for creation and the cat itself as the main content.

- How could you use this data in an application?

> I could imagine integrating this API into an app that allows user to make a cat app quiz game to test the knowledge of cat lovers.

- What did you like about the documentation?

> The documentation was well organized and easy to follow. It provided clear instructions on how to use the API including details in depth.

- What did you find challenging about the documentation?

> I found the documentation to be lacking in some areas. While it provided basic information on how to use the API, there were certain aspects that could have been explained in more detail.

- Did the quality of the documentation impact your decision to use it?

> Yes,the quality of the documentation did impact my decision to use it. Since the documentation was lacking in some areas and did not provide sufficient information or examples, it made it more difficult for me to fully understand and utilize the API.

- Did you switch which API you chose initially because of its documentation, or did you stick with the one you selected and work your way through it?

> Yes,I ended up switching the API I initially chose because of its documentation. The lack of clear and comprehensive documentation made it challenging for me to understand and implement the API effectively

- In your own words, summarize the request-response cycle.

> The request-response cycle is a concept in web development that describes the flow of communicatiuon between a client (web browser)
> and a server.

- In your own words, describe what an API is.

> An API is known as Application Program Interface which is a set of rules and protocols that allows differnent software applications to communicate and interact with each other.

- In your own words, describe the purpose of Postman.

> Postman is an application that serves as a comprehesive tool for API development and testing. It allows developers to design and build and document APIs more efficiently.
