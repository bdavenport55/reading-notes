# Read 37

## Redux - Combined Reducers

### Multiple Reducers Example<sup>1</sup>

#### 1. Why create multiple reducers?

It allows for better, cleaner organization so you don't have one big mess of a single reducer to deal with.

#### 2. How would you combine multiple reducers?

The `combineReducers` function from Redux

```js
const reducers = combineReducers({
  user: userReducer
  things: thingsReducer
});
```

#### 3. How will you manage state as an immutable object? why?

Never return the input state object, return a *new* state object

### Redux Docs: Using Combined Reducers<sup>2</sup>

#### 1. `combineReducers` is a utility function to simplify the most common use case when writing ___ _____ .

Redux reducers

#### 2. Explain how `combineReducers` assembles the new state tree.

It will call each 'slice' reducer with its current slice of state and the current action, giving the slice reducer a chance to respond and update its slice of state if needed.

#### 3. How would you define initial state in an app using combineReducers?

- `createStore`, which takes a `preloadedState` as its second argument
- or, the root reducer returns the initial state value when the state argument is `undefined`

### Redux Docs: Combined Reducer Syntax<sup>3</sup>

#### 1. Why will you want to split your reducing functions as your app becomes more complex?

To manage independent parts of the `state`

#### 2. The _____ helper function turns an object whose values are different reducing functions into a single reducing function you can pass to ____.

`combineReducers`, `createStore`

#### 3. What is a popular convention when naming reducers?

To name reducers after the state slices they manage, so you can use ES6 property shorthand notation (i.e. `combineReducers({ counter, todos}))` is equivalent to `combineReducers({ counter: counter, todos: todos })`.

### Footnotes

<sup>1</sup>https://www.youtube.com/watch?v=gBER4Or86hE

<sup>2</sup>https://redux.js.org/usage/structuring-reducers/using-combinereducers/

<sup>3</sup>https://redux.js.org/api/combinereducers/

[Back](/reading-notes/401/401-TOC.html)