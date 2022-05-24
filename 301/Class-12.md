# Read 12

## Status Codes Based on REST Methods<sup>1</sup>

### 1. In your own words, describe what each group of status code represents:

* 100s = Informational codes, updates on status of requests
* 200s = Requests, or at least validation requirements of requests, were successful
* 300s = The requested resource exists but not in the targeted location, look elsewhere
* 400s = Errors occurring on the client side - timeouts, wrong URI, missing auth
* 500s = Errors occuring on server side - overwhelmed servers, servers behind proxies

### 2. What is a status code 202?

  Accepted - the request was valid but processing will finish in the future

### 3. What is a status code 308?

  Permanent redirect - use another URL to access the resource, not the current one

### 4. What code would you use if an update didn’t return data to a client?

  204 No Content

### 5. What code would you use if a resource used to exist but no longer does?

  410 Gone

### 6. What is the ‘Forbidden’ status code?

  403 - client does not have permissions to access resource

## Build a REST API with Node.js, Express, & MongoDB<sup>2</sup>

### 1. Why do we need to pull our MongoDB database string out of our server and put it into our .env?

  When we deploy our application we're going to want to use something that is not our local host, and we don't want it in the public code

### 2. What is middleware?

  Code that runs when the server gets a request but before it gets passed to a route

### 3. What does `app.use(express.json())` do?

  Lets our server accept json as a body instead of a post element or get element, etc

### 4. What does the `/:id` mean in a route?

  A parameter, which can then be used in queries to access what is passed in after the slash

### 5. What is the difference between `PUT` and `PATCH`?

  PUT will update all of the information, PATCH only updates based on what the user inputs

### 6. How do you make a default value in a schema?

  In the object, set a property to have the key 'default' and the value equal to what you want the default value to be

### 7. What does a 500 error status code mean?

  There is an error on the server itself, has nothing to do with the client

### 8. What is the difference between a status 200 and a status 201?

  201 - successfully created an object, 200 - general success message, not specific about what was created

### Footnotes

<sup>1</sup>https://www.moesif.com/blog/technical/api-design/Which-HTTP-Status-Code-To-Use-For-Every-CRUD-App/

<sup>2</sup>https://www.youtube.com/channel/UCFbNIlppjAuEX4znoulh0Cw

[Back](/reading-notes/301/301-TOC.html)