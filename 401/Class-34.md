# Read 34

## API Integration

### Review API Server Build<sup>1</sup>

#### 1. Explain the different between a query string parameter and a path parameter.

- Query string: is like a filter, looking for all resources that fit that category (i.e. `/tshirts/blue`)
- Path parameter: looking for a single, specific resource (i.e. `GET /people/:id`)

#### 2. What would our API URL with a path id parameter be given the following information:

  1. Domain: `http://our-site.com`
  2. `v3`
  3. model name: `stuff`
  4. id: `things`

`http://our-site.com//api/v3/stuff/things/:id`

#### 3. We have created a dynamic API with an “interface”. Describe how that interface works to a non-technical friend.

Its like a template of a template, so if you want to create a new filter or category, you just use the template so it matches the others

### Review Auth Server Build<sup>2</sup>

#### 1. Describe how you would use middleware to implement basic and bearer auth.

The middleware would check the headers of an API request to ensure the requester is authenticated/authorized

#### 2. Describe the handshake necessary to implement OAuth.

A `GET` request is made from the API to the 3rd party auth provider, which returns a token, allowing the user to access the resources they are authorized to

#### 3. Describe how Role Based Access Control works to a non-technical friend.

Its like in the movies, where sombody has an inflated ego by having "level 'x' credentials out of 'y' levels". A person has access to the places that correlate with their badge level.

### Footnotes

<sup>1</sup>https://codefellows.github.io/code-401-javascript-guide/curriculum/apps-and-libraries/api-server/

<sup>2</sup>https://codefellows.github.io/code-401-javascript-guide/curriculum/apps-and-libraries/auth-server/

[Back](/reading-notes/401/401-TOC.html)