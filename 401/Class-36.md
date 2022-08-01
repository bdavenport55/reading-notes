# Read 36

## Application State with Redux

### Dan Abramov Redux Tutorials<sup>1</sup>

#### 1. What is the first principle of Redux?

State of whole app is contained in a single JS object, the 'state tree'

#### 2. what is a store and what do we use our reducers for within that store?

- holds the current app's state object
- lets you dispatch actions
- upon creation, need to specify reducer that tells how state is updated with actions

#### 3. Name three Redux store methods given to us by createStore and describe their use.

- `getState`: retrieves current state of redux store
- `dispatch`: dispatch actions to change state of the app
- `subscribe`: register a callback that redux store will call any time an action has been dispatched so UI can be updated

#### 4. Explain to a non-technical recruiter what combineReducers() does and why it is useful.

Its essentially instructions for instructions that an automated process is reading.  Its how the automated process knows how and when to automate the things it does

### Bookmarks

- [world's easiest guide to redux](https://www.freecodecamp.org/news/understanding-redux-the-worlds-easiest-guide-to-beginning-redux-c695f45546f6)
- [testing reducers](https://medium.com/@netxm/testing-redux-reducers-with-jest-6653abbfe3e1)
- [Redux docs](https://redux.js.org/)

### Footnotes

<sup>1</sup>https://egghead.io/courses/fundamentals-of-redux-course-from-dan-abramov-bd5cc867

[Back](/reading-notes/401/401-TOC.html)
