# Read 26

## Component-based UI

### React hello world<sup>1</sup>

#### 1. What are the building blocks of a React app?

* Elements
* Components

#### 2. What is the difference between an element and a React component?

* Element - the smallest building blocks of React apps
* Components - made of elements

#### 3. What are some advantages of React’s component based architecture?

Split UI into independent, reusable pieces

### Introducing JSX<sup>2</sup>

#### 1. What is JSX and why do we use it?

It is a syntax extension of JavaScript, describes what the UI should look like.

`const element = <h1>Hello, world!</h1>;`

#### 2. Describe the process of embedding JavaScript expressions in JSX.

Define a variable whose property is a wrapped in some sort of tag, embed a different variable inside of the tags, wrapped in curly braces

`const name = 'Josh Perez';`
`const element = <h1>Hello, {name}</h1>;`

#### 3. Is it safe to embed user input in JSX? Explain.

Yes, "By default, React DOM escapes any values embedded in JSX before rendering them. Thus it ensures that you can never inject anything that’s not explicitly written in your application. Everything is converted to a string before being rendered. This helps prevent XSS (cross-site-scripting) attacks."

### Rendering Elements<sup>3</sup>

#### 1. Explain what a React Component is to a non-technical friend.

Its like apps on your phone, you can download the app (insert it into the code) and it creates a new behavior that your phone does.

#### 2. Describe mutability and React Components, specifically, how is the UI updated?

Elements themselves are immutable (cannot be changed), the UI is updated when `render.root()` is called and only updates parts which contents has been changed.

#### 3. If changes are made to the UI, what does React update?

Only the part that has been changed.

### Bookmarks

* [Sass cheatsheet](https://devhints.io/sass)
* [React cheatsheet](https://devhints.io/react)
* [Another React cheatsheet](https://reactcheatsheet.com)

### Footnotes

<sup>1</sup>https://reactjs.org/docs/hello-world.html

<sup>2</sup>https://reactjs.org/docs/introducing-jsx.html

<sup>3</sup>https://reactjs.org/docs/rendering-elements.html

[Back](/reading-notes/401/401-TOC.html)