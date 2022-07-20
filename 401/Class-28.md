# Read 28

## Component Lifecycle/ `useEffect()` Hook

### Effects Hook<sup>1</sup>

#### 1. What purpose does useEffect serve in a function component compared to its counterpart(s) in class components?

Data fetching, setting up a subscription, and manually changing the DOM. It behaves in the same way `componentDidMount`, `componentDidUpdate`, and `componentWillUnmount` all do, combined.

#### 2. When using the `useEffect()` Hook:

  #### 1. What does `useEffect()` do?

  Tells React that a component needs to do something after render.

  #### 2. Why is `useEffect()` called inside a component?

  It lets us access state variables or props right from the effect

#### 3. Explain the importance of properly implementing effects with Cleanup

Its so we don't introduce a 'memory leak', we want to avoid unwanted effects

### Footnotes

<sup>1</sup>https://reactjs.org/docs/hooks-effect.html

[Back](/reading-notes/401/401-TOC.html)