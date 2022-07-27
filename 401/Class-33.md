# Read 33

## `<Login />` and `<Auth />`

### What is Role Based Access Control<sup>1</sup>

#### 1. What is Role Based Access Control (RBAC)?

> Role-based access control (RBAC) restricts network access based on a person's role within an organization and has become one of the main methods for advanced access control. The roles in RBAC refer to the levels of access that employees have to the network.

If you are authenticated in a certain role, you get to do the things anybody else in that role can do

#### 2. Share an example of RBAC including all possible CRUD operations and correlating roles.

- Viewer: can read
- User: can read and create
- Administrator: can read, create, update, and delete

#### 3. What are the Benefits of RBAC?

- reduce admin work and IT support
- maximize operational efficiency
- improving compliance

### Compare and contrast 'react-cookie library' and 'react-cookies component'<sup>2,3</sup>

#### 1. Describe some `react-cookie` features.

- is a hook
- can get, getAll, set, and remove cookies

#### 2. Describe some `react-cookies` features.

- is a component
- can `.load`, `.loadAll`, `.save`, `.remove`, `.plugToRequest`, `.setRawCookie`
- can specify name, value, options, path, expires, max age, domain, secure, httpOnly

#### 3. Which library would you prefer would you prefer? Why?

Seems like if you want to specify a lot of stuff, `react-cookies` is the way to go, but if you only need a simple cookie, `react-cookie` will work

### Bookmarks

- [react-cookie library](https://www.npmjs.com/package/react-cookie)
- [react-cookies component](https://www.npmjs.com/package/react-cookies)

### Footnotes

<sup>1</sup>https://digitalguardian.com/blog/what-role-based-access-control-rbac-examples-benefits-and-more

<sup>2</sup>https://www.npmjs.com/package/react-cookie

<sup>3</sup>https://www.npmjs.com/package/react-cookies

[Back](/reading-notes/401/401-TOC.html)