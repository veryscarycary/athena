## Tech spec for Athena ##

>Purpose of this doc: plan ahead so you run into less trouble later.
>How to use this doc: address all the TODO's. If a given TODO is irrelevant, just delete it.

## App overview ## 
[TODO briefly explain the app. Imagine you have literally 60 seconds to pitch your app to an investor. That’s how much verbiage should go here.]

 The product is a service optimization solution for capturing actionable knowledge from customer interactions. It provides a ticketing system to resolve customer pain-points and identify product shortcomings, a knowledge base platform to generate relevant, reusable documentation, and an administrative dashboard that presents distilled, dynamic data to inform targeted solutions.

## Mockups ##
[TODO draw out a simple skeleton of what your UI might look like]

[KB Mockup](https://github.com/Wistful-Bison/athena/blob/master/mockupFiles/kbArticle.html)


## Architecture ##
[TODO Sketch out your system architecture -- pretty much just what you’d sketch out on a whiteboard to explain things to yourselves while planning. If you’re unsure how to draw such diagrams -- there should be a box for each major component of the system. Key flows (requests/responses, data being moved and processed, etc) that tie those components together are represented by lines between boxes. Imagine diagramming how a restaurant handles an order. Note that there isn't one canonical way to draw these diagrams, don’t get too hung up on format.]

[TODO use LucidChart or other stuff to make system diagrams. There should be a box for each major component of the system, and key flows that tie those components together are represented by lines between boxes]
[TODO sequence diagram of the overall flow]
[TODO system diagram of the components and their relationships]

LUCIDART Diagram - ![alt text](https://github.com/Wistful-Bison/athena/blob/master/Diagrams/Thesis%20Architecture%20-%20Page%201.png)


[TODO E-R diagram or other description of the schema]
SCHEMA DIAGRAM - ![alt text](https://github.com/Wistful-Bison/athena/blob/master/Diagrams/Screen%20Shot%202016-09-22%20at%203.14.40%20PM.png)

[TODO API spec]
API SPEC - ![alt text](https://github.com/Wistful-Bison/athena/blob/master/Diagrams/API%20Spec.jpg)


## Tools and technologies we plan to use ##
[TODO list all key frameworks and libraries]

Front-end
------------
React
Redux

Back-end
---------
Node
Express
Sequelize
PostgresQL
Docker


## What will be cool / hard / done from scratch? ##
[TODO what things do you plan to do, technically speaking, that would at least mildly impress a fellow nerd? stuff that goes beyond run-of-the-mill usage of the usual tools.]

-Docker
-Service-oriented Architecture
-Ticketing System
-Relational data
-Oauth

## Technical investigations done / to do ##
[TODO define any time-boxed investigation / prototyping that must be done before the team can safely proceed, and/or link to the results of such investigations that you did]

-Relational schema and API endpoints
-Redux research
-Testing
-Docker
-Knowledge Base Implementations(Knowledge-centered Support)

## Ownership ##
[TODO for each major system area / work area, please list who is the single owner (the  “go-to person”) for that area. Identifying “go to” ownership of areas at project start is helpful later, in the Outcomes phase of Hack Reactor, when you will need to convince hiring managers that you really did and really can do the things you list on your resume. ]

Brad - Backend
Amelia - Frontend
Cary - Frontend
