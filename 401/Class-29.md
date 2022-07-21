# Read 29

## Advanced State with Reducers

### useReducer Hook<sup>1</sup>

#### 1. Name an alternative to the useState Hook.

useReducer

#### 2. Why might the useReducer Hook be preferable to the useState Hook?

When you have complex state logic that involves multiple sub-values or when the next state depends on the previous one

#### 3. What are two ways to set the initial state?

* Pass the initial state as a second argument
* Pass an `init` function as the third argument (lazy way)

### Ultimate Guid to useReducer<sup>2</sup>

#### 1. In terms of state, what does useReducer expect to receive as a parameter?

The initial state

#### 2. What does useReducer return?

An array that holds the current state value and a `dispatch` function to which you can pass an action and later invoke it.

#### 3. Explain dispatch to a non-technical recruiter.

It sends the type of action to the reducer function to perform its job.

### Footnotes

<sup>1</sup>https://reactjs.org/docs/hooks-reference.html#usereducer

<sup>2</sup>https://blog.logrocket.com/react-usereducer-hook-ultimate-guide/

[Back](/reading-notes/401/401-TOC.html)
