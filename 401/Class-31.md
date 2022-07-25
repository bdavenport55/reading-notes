# Read 31

## Context API

### Context API<sup>1</sup>

#### 1. What can React Context provide your app?

A way to pass data through the component tree without having to pass props down manually at every level

#### 2. Why might we use Context?

It provides a way to share values between components without having to explicitly pass a prop though every level of the tree. Used when data is considered "global" for a component tree

#### 3. Why should we use it sparingly?

It makes component reuse more difficult

### Awesome React Context links<sup>2</sup><sup>3</sup>

#### 1. Consume content from (at least) two of the Awesome React Context links. Share your take-away from each:

- Takeaway 1: Three parts to React Context API
  - `Context`
  - `Provider`
  - `Consumer`

- Takeaway 2: Accessible as `React.createContext()`, creates two components
  - `Provider` - special component which aims to provice data to all components in its sub-tree
  - `Consumer`
    - must have access to the same Context component
    - new syntax uses the function as child pattern
    - no longer required to use `prop-types` to specify `contextProps`

### Bookmarks

[Awesome React Context GitHub](https://github.com/diegohaz/awesome-react-context)

### Footnotes

<sup>1</sup>https://reactjs.org/docs/context.html

<sup>2</sup>https://www.freecodecamp.org/news/reacts-new-context-api-how-to-toggle-between-local-and-global-state-c6ace81443d0

<sup>3</sup>https://medium.com/@baphemot/whats-new-in-react-16-3-d2c9b7b6193b

[Back](/reading-notes/401/401-TOC.html)