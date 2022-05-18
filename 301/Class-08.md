# Read 08

## API Design Best Practices<sup>1</sup>

### 1. What does REST stand for?

  Representational State Transfer

### 2. REST APIs are designed around a ____.

  Resource

### 3. What is an identifier of a resource? Give an example.

  A URI (Uniform Resource Identifier) - `https://adventure-works.com/orders/1`

### 4. What are the most common HTTP verbs?

  GET, POST, PUT, PATCH, DELETE

### 5. What should the URIs be based on?

  Nouns, when possible

### 6. Give an example of a good URI.

  `https://adventure-works.com/orders // Good`

  `https://adventure-works.com/create-order // Avoid`

### 7. What does it mean to have a ‘chatty’ web API? Is this a good or a bad thing?

  It's bad, as a chatty API imposes a larger load on the web server by exposing a large number of small resources.

### 8. What status code does a successful GET request return?

  200 (OK)

### 9. What status code does an unsuccessful GET request return?

  404 (Not Found)

### 10. What status code does a successful POST request return?

  201 (Created)

### 11. What status code does a successful DELETE request return?

  204 (No Content)

### Footnotes

<sup>1</sup>https://docs.microsoft.com/en-us/azure/architecture/best-practices/api-design

### Bookmarks

[RegExr](https://regexr.com/)
[Regex Tutorial](https://medium.com/factory-mind/regex-tutorial-a-simple-cheatsheet-by-examples-649dc1c3f285)
[Regex 101](https://regex101.com/)

[Back](/reading-notes/301/301-TOC.html)