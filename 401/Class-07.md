# Read 07

## Bearer Authorization

### <sup>1</sup>

#### 1. What is a JSON Web Token (JWT)?

"...an open standard (RFC 7519) that defines a compact and self-contained way for securely transmitting information between parties as a JSON object."

#### 2. When should we use JSON Web Tokens?

* Authorization
* Information Exchange

#### 3. Claims are expected in which structural component of a JWT?

Payload

### <sup>2</sup>

#### 1. If I get a JWT and I can decode the payload, how can we call that secure?

JWTs are signed and digital signatures show what kind of activity is attributed to who, which would alert to any fraud.

#### 2. If sending a JWT, what must sender and receiver both know? Hint, it’s appended in the signature.

`Hash(payload + secret)`

#### 3. Explain how concatenated content and secret can be sent and received securely to a non-technical recruiter.

Anybody trying to get their hands on the secure content and meddle with it would need to know two different variables in order to 1) get in and 2) leave an appropriate signature to obscure their presence, which is highly unlikely

### <sup>3</sup>

#### 1. Why use JWT?

"...to securely transfer information between any two bodies."

#### 2. JWT is Compact and self-contained. Describe how this is useful to a non-technical friend.

It's very fast - you won't be sitting there looking at a web page loading and being impatiently frustrated with it.  It also cuts down on the number of back and forth information transmissions, which also makes things faster.

#### 3. What are the three components (the structure) of a JWT signature?

* Header
* Payload
* Signature

### Bookmarks

[npm jsonwebtoken docs](https://www.npmjs.com/package/jsonwebtoken)

### Footnotes

<sup>1</sup>https://jwt.io/introduction/

<sup>2</sup>https://stackoverflow.com/questions/27301557/if-you-can-decode-jwt-how-are-they-secure

<sup>3</sup>https://www.youtube.com/watch?v=926mknSW9Lo

[Back](/reading-notes/401/401-TOC.html)