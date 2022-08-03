# Read 38

## Redux - Asynchronous Actions

### Async actions<sup>1</sup>

#### 1. Why use Redux middleware?

To write logic in your app that has side effects, which cannot be in a Redux reducer

#### 2. Consider the Redux Async Data Flow Diagram. Describe the flow in your own words.

The middleware is an additional step in the existing data flow.  The middleware makes an API request, whose response will be used in the dispatch action in the reducer

#### 3. How are we accommodating async in our Redux app?

"Thunk" middleware - allows us to write functions that get `dispatch` and `getState` as arguments 

### Thunk middleware<sup>2</sup>

#### 1. Why would you need redux-thunk middleware?

To pass a function to `dispatch` so we can interact with a store

#### 2. Redux Thunk middleware allows you to write action creators that return a ____ instead of an action.

function

#### 3. Describe how any return value from the inner thunk function will be made available.

As the return value of `dispatch` itself

### Footnotes

<sup>1</sup>https://redux.js.org/tutorials/fundamentals/part-6-async-logic

<sup>2</sup>https://github.com/reduxjs/redux-thunk

[Back](/reading-notes/401/401-TOC.html)