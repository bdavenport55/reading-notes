# Read 03

## Express REST API

### Review: ES6 Classes<sup>1</sup>

### 1. Classes are a template for creating ____.

Objects

### 2. Can a class declaration be hoisted?

No, the class can be hoisted but its values do not get hoisted with it.

### 3. How would you describe a constructor and contextual “this” to a non-technical friend?

A constructor is something that creates a collection of data, or an object, that can be referred to later, and `this` is a keyword used to reference the data in the current object.

### Using Express Routing<sup>2</sup>

### 1. Within Express, what does routing refer to?

"...how an application's endpoints (URIs) respond to client requests.

### 2. What is the difference between a route path and a route method?

* route method - derived from one of the HTTP methods, attached to an instance of the `express` class.

* route path - in combination with a request method, define the endpoints at which requests can be made.

### 3. When is it appropriate to add `next` as a parameter to a route handler and what must you do if `next` has been passed to your middleware as a parameter?

* When there are multiple callback functions
* call `next()` within the body of the function to hand off control to the next callback

### Express Routing<sup>3</sup>

### 1. What is an Express Router?

It's like a mini Express app - it doesn't bring in views or settings but provides routing APIs - `.use`, `.get`, `.param`, `route`.

### 2. By what means do we initialize `express.Router()` in an express server?

It doesn't require any more dependencies on top of `express`, so there are no extra steps.

### 3. What do we use route middleware for?

"...to do something before a request is processed", (i.e. checking if a user is authenticated).

### Footnotes

<sup>1</sup>https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Classes

<sup>2</sup>https://expressjs.com/en/guide/routing.html

<sup>3</sup>https://www.digitalocean.com/community/tutorials/learn-to-use-the-new-router-in-expressjs-4

[Back](/reading-notes/401/401-TOC.html)