# Read 32

## Context API - Behaviors

### Hooks and Context example<sup>1</sup>

#### 1. With regard to the React Context API, what does a “provider” do?

- displays local state of the component
- exposes an API for globally managing components

#### 2. With regard to the React Context API, how would we implement a “consumer” role?

wrap the custom hook around `useContext`

#### 3. Specifically with Context, how are we “wrapping” components to achieve our goals?

`useContext` goes inside of custom hooks

### Awesome React Context links<sup>2, 3</sup>

#### 1. Consume content from (at least) two of the Awesome React Context links. Share your take-away from each:

- Takeaway 1: `Context.Consumer` requires a 'function as a child` 

```js
<MyContext.Consumer>
  {value => /* render something based on the context value */}
</MyContext.Consumer>
```

- Takeaway 2: 
>The React docs suggest that providing a default value "can be helpful in testing components in isolation without wrapping them." While it's true that it allows you to do this, I disagree that it's better than wrapping your components with the necessary context. Remember that every time you do something in your test that you don't do in your application, you reduce the amount of confidence that test can give you. There are reasons to do this, but that's not one of them.

### Footnotes

<sup>1</sup>https://medium.com/swlh/snackbars-in-react-an-exercise-in-hooks-and-context-299b43fd2a2b

<sup>2</sup>https://reactjs.org/docs/context.html

<sup>3</sup>https://kentcdodds.com/blog/how-to-use-react-context-effectively

[Back](/reading-notes/401/401-TOC.html)