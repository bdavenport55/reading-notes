# Read 39

## Redux - Additional Topics

### Redux Toolkit (RTK)<sup>1</sup>

#### 1. What concerns are addressed by Redux Toolkit?

- "Configuring a Redux store is too complicated"
- "I have to add a lot of packages to get Redux to do anything useful"
- "Redux requires too much boilerplate code"

#### 2. What does `configureStore()` do?

"wraps `createStore` to provide simplified configuration options and good defaults. It can automatically combine your slice reducers, adds whatever Redux middleware you supply, includes redux-thunk by default, and enables use of the Redux DevTools Extension."

#### 3. How would I use `createSlice()`?

Pass it an initial state object - your object of reducer functions

### MobX<sup>2</sup>

#### 1. What is Mobx?

3rd party state management system, a standalone library most commonly being used with React

#### 2. How does MobX make it “impossible” to produce an inconsistent state?

"Make sure that everything that can be derived from the application state, will be derived. Automatically."

#### 3. How would we build a reactive user interface?

wrapping the React component in `autorun`

### Tutorial<sup>3</sup>

#### 1. What take-away(s) did this tutorial provide?

- install Toolkit: `npm i @reduxjs/toolkit react-redux`
- Create Redux store
- Provide the redux store to react
- Create a redux state slice
- Add slice reducers to the store
- Use redux state and actions in react components

### Bookmarks

[Redux Toolkit](https://redux-toolkit.js.org/)
[HookState](https://hookstate.js.org/)

### Footnotes

<sup>1</sup>https://redux-toolkit.js.org/introduction/getting-started

<sup>2</sup>https://mobx.js.org/getting-started.html

<sup>3</sup>

[Back](/reading-notes/401/401-TOC.html)