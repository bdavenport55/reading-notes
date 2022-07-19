# Read 27

## `useState()` Hook

### Introducing Hooks<sup>1</sup>

#### 1. What was the motivation for introducing Hooks?

Solving a variety of problems

- Hard to reuse stateful logic between components
- Complex components become too hard to understand
- Classes confuse both people and machines

#### 2. What changes are important regarding implementing Hooks versus Component Classes?

- Hooks allow you to reuse stateful logic without changing your component hierarchy
- Hooks let you split one component into smaller functions based on what pieces are related (such as setting up a subscription or fetching data)
- Hooks let you use more of React's features without classes

#### 3. Hooks allow you to reuse stateful logic without changing ___ _______.

Component hierarchy

### hooks api<sup>2</sup>

#### 1. Name two rules imposed by React Hook usage.

1. Only call Hooks **at the top level**. Don't call Hooks inside loops, conditions, or nested functions.
2. Only call Hooks **from React function components**. Don’t call Hooks from regular JavaScript functions. (There is just one other valid place to call Hooks — your own custom Hooks. We’ll learn about them in a moment.)

#### 2. How would you identify a custom Hook and why might you create one?

- function's name starts with `use` and calls other Hooks
- custom hooks cover a wide range of use cases
  - form handling
  - animation
  - declarative subscriptions
  - timers
  - much more

### the state hook<sup>3</sup>

#### 1. What is a Hook?

A Hook is a special function that lets you “hook into” React features. For example, useState is a Hook that lets you add React state to function components.

#### 2. When would I use the `useState` Hook?

Adding React state to function components

#### 3. If you were to add React state to a function component by declaring a state variable:

- What does calling useState do?
  - It declares a "state variable"
- What do we pass to useState as an argument?
  - Only the initial state (i.e. counter starting at 0)
- What does useState return?
  - A pair of values:
    - the current state
    - a function that updates it

### Bookmarks

[hooks api reference](https://reactjs.org/docs/hooks-reference.html)

### Footnotes

<sup>1</sup>https://reactjs.org/docs/hooks-intro.html#motivation

<sup>2</sup>https://reactjs.org/docs/hooks-overview.html

<sup>3</sup>https://reactjs.org/docs/hooks-state.html

[Back](/reading-notes/401/401-TOC.html)