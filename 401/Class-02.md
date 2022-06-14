# Read 02: Express, NPM, TDD, CI/CD

## An introduction to Node.js and Express<sup>1</sup>

### 1. Explain middleware, answer as though I were a non-technical recruiter.

Middleware is a type of software that allows a main collection of software to use other services that are not already a part of it. It's like the pipes in your house that bring you (the user) water (product or service).

### 2. Express is the most popular ______.

Node web framework

### 3. Express is “unopinionated.” What does that mean?

It has fewer restrictions than its opinionated counterparts on "the best way to glue components together to achieve a goal, or even what components should be used." There are much more choices for middleware.

### 4. What is a module and why is modularity useful to us as developers?

A module is a JavaScript library or file that you can import into other code using Node's `require()` function.  Modularity allows for better organization of code into manageable parts.

## What is NPM?<sup>2</sup>

"npm is the world's largest software registry." It is a place to share and borrow packages. It consists of its website, the CLI, and the registry (the large public database of JavaScript software)

### 1. What version of npm are you running on your machine?

8.11.0

### 2. What command would you type to install a library/package called ‘jshint’ into your node project?

`npm i jshint`

## What is TDD?<sup>3</sup>

### 1. Explain why tests are important. Please explain as though I were your non technical elder.

If we just made our product and didn't test it to ensure it is working correctly, we could put it out in the market and then all of the users of the product wouldn't be able to use it correctly.  Plus, taking the risk of doing it that and hoping for the best is actually more costly than if we just take a little time before we put the product out there to do our tests and make sure everything is working correctly.

### 2. What are three expected benefits of testing

* Reduction in defect rates
* Overheads required of moderately increased initial dev times are *more* than offset by reduction in effort in final phases
* Anecdotal evidence supports "higher degree of 'internal' or technical quality"

### 3. Name at lest 2 individual pitfalls and at least 2 team pitfalls commonly encountered while writing tests.

* forgetting to run tests frequently
* writing overly trivial tests

* partial adoption - whole team not using same guiding test practices
* poor/abandoned test suites

## CI/CD<sup>4</sup>

### 1. What are three benefits of Continuous Integration?

* Ensure everyone's changes integrate
* Catch bugs
* Reduce merge conflicts

### 2. What is the difference between Continuos Delivery and Continuous Deployment?

Delivery - practice of developing software in a way that it could be released at any time

Deployment - allows immediate deployment of new features

### 3. Explain how GitHub fits into this process assuming the listener comes from a non-technical background

GitHub is a central place where developers can upload their written code, and it notifies other any other developers of the change, then sends them what changes were made, so it can fit into the code they are writing

## Bookmarks

[node.js docs](https://nodejs.org/en/docs/)
[npm docs](https://docs.npmjs.com/)
[express docs](https://expressjs.com/en/4x/api.html)
[http status codes](https://www.restapitutorial.com/httpstatuscodes.html)
[supertest](https://github.com/visionmedia/supertest)

### Footnotes

<sup>1</sup>https://developer.mozilla.org/en-US/docs/Learn/Server-side/Express_Nodejs/Introduction

<sup>2</sup>https://docs.npmjs.com/about-npm

<sup>3</sup>https://www.agilealliance.org/glossary/tdd/#q=~(infinite~false~filters~(postType~(~'page~'post~'aa_book~'aa_event_session~'aa_experience_report~'aa_glossary~'aa_research_paper~'aa_video)~tags~(~'tdd))~searchTerm~'~sort~false~sortDirection~'asc~page~1)

<sup>4</sup>https://www.youtube.com/watch?v=xSv_m3KhUO8

[Back](/reading-notes/401/401-TOC.html)