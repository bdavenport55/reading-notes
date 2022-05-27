# Read 15

## What is OAuth<sup>1</sup>

### 1. What is OAuth?

  "An open-standard authorization protocol or framework that describes how unrelated servers and services can safely allow authenticated access to their assets without actually sharing the initial, related, single logon credential. In authentication parlance, this is known as secure, third-party, user-agent, delegated authorization."

  In my own words I would describe it as: a security feature that adds credentialed access to resources

### 2. Give an example of what using OAuth would look like.

  When you log onto a website and it offers one or more opportunities to log on using another website's/service's logon (i.e. sign in with Google).

### 3. How does OAuth work? What are the steps that it takes to authenticate the user?

  1. Website connects to second website on user's behalf
  2. Second site generates one-time token
  3. First site gives token to user's client software needing it
  4. Client software presents token
  5. Client is authenticated
  6. User approves a particular transaction on first website
  7. User is given access token
  8. User gives access token to first website
  9. First website gives access token to second to authenticate user
  10. Second website lets first website access on behalf of user
  11. User sees successful transaction

### 4. What is OpenID?

  Essentially Oauth, but it is about authentication wheras Oauth is about authorization

## Authorization and Authentication flows<sup>2</sup>

### 1. What is the difference between authorization and authentication?

  Authentication is about identifying *who* users are, authorization is about identifying *what* credentials a user has

### 2. What is Authorization Code Flow?

  The process of exchanging an authorization code for a token

### 3. What is Authorization Code Flow with Proof Key for Code Exchange (PKCE)?

  Authorization Code Flow with extra security - a Code Verifier

### 4. What is Implicit Flow with Form Post?

  An alternative to Authorization Code Flow which is intended for Public Clients, or applications which are unable to securely store Client Secrets.

### 5. What is Client Credentials Flow?

  The login credentials for a whole app versus a single user

### 6. What is Device Authorization Flow?

  Authorization given to a device via authentication by the user's following of links

### 7. What is Resource Owner Password Flow?

  Simple username and password authorization and authentication

### Footnotes

<sup>1</sup>https://www.csoonline.com/article/3216404/what-is-oauth-how-the-open-authorization-framework-works.html

<sup>2</sup>https://auth0.com/docs/get-started/authentication-and-authorization-flow

[Back](/reading-notes/301/301-TOC.html)