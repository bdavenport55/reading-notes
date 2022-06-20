# Read 06

## Authentication

### Securing Passwords<sup>1</sup>

#### 1. Explain to a non-technical friend how you would safely hash and store a password.

If you want your password to be, say, "pA$$w0rD", you would set an index of, say, 1 character/letter up - so "pA$$w0rD" would turn into "qB%%x1sE"

#### 2. What is Bcrypt?

"Bcrypt is an adaptive hash function based on the Blowfish symmetric block cipher cryptographic algorithm and introduces a work factor (also known as security factor), which allows you to determine how expensive the hash function will be."

#### 3. Why might you use something like Bcrypt?

To increase the amount of time brute force attacks take and hopefully stop a breach from happening.

### Basic Auth<sup>2</sup>

#### 1. What is Basic Authentication?

A method for a client to provide a username and password to prove they have the permission to access something

#### 2. What properties are necessary in the header of a Basic Auth request?

`Authorization: Basic <credentials>`

#### 3. How are `username:password` in Basic Auth encoded?

[`Base64`](https://en.wikipedia.org/wiki/Base64) encoding

### OWASP auth cheatsheet<sup>3</sup>

#### 1. Define the authentication process to a non-technical recruiter.

I give you my credentials, or username and ID, plus, only something that *you* know that I would know.

#### 2. How should your error messaging respond (both HTTP and HTML)? Why?

Generically - it helps to keep attackers from having any hints that will help them fake authentication

#### 3. Bookmark this link also and consider OWASP fundamentals any time you interact with authentication. Applications developed with security in mind from inception have fewer vulnerabilities throughout their lifecycle.

### Bookmarks

[bcrypt](https://www.npmjs.com/package/bcrypt)
[OWASP](https://cheatsheetseries.owasp.org/cheatsheets/Authentication_Cheat_Sheet.html)

### Footnotes

<sup>1</sup>https://thehackernews.com/2014/04/securing-passwords-with-bcrypt-hashing.html

<sup>2</sup>https://en.wikipedia.org/wiki/Basic_access_authentication

<sup>3</sup>https://cheatsheetseries.owasp.org/cheatsheets/Authentication_Cheat_Sheet.html

[Back](/reading-notes/401/401-TOC.html)