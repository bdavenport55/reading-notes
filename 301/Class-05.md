# Read 05

## Thinking in React<sup>1</sup>

### 1. What is the `single responsibility principle` and how does it apply to components?

  A component should ideally only do one thing

### 2. What does it mean to build a ‘static’ version of your application?

  Built to take in data and render a UI but has no interactivity

### 3. Once you have a static application, what do you need to add?

  Interactivity

### 4. What are the three questions you can ask to determine if something is state?

* Is it passed in from a parent via props? If so, it probably isn't state.
* Does it remain unchanged over time? If so, it probably isn't state.
* Can you compute it based on any other state or props in your component? If so, if isn't state.

### 5. How can you identify where state needs to live?

* Identify every component that renders something based on that state.
* Find a common owner component (a single component above all the components that need the state in the hierarchy).
* Either the common owner or another component higher up in the hierarchy should own the state.
* If you can’t find a component where it makes sense to own the state, create a new component solely for holding the state and add it somewhere in the hierarchy above the common owner component.

## Higher-Order Functions<sup>2</sup>

### 1. What is a “higher-order function”?

  Functions that operate on other functions, either by taking them as arguments of by returning them.

### 2. Explore the `greaterThan` function as defined in the reading. In your own words, what is line 2 of this function doing?

  returning whehter or not the result of another function is true

### 3. Explain how either `map` or `reduce` operates, with regards to higher-order functions.

### Footnotes

<sup>1</sup>https://reactjs.org/docs/thinking-in-react.html

<sup>2</sup>https://eloquentjavascript.net/05_higher_order.html#h_xxCc98lOBK

[Back](/reading-notes/301/301-TOC.html)