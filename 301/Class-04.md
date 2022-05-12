# Read 04

## Forms<sup>1</sup>

1. What is a ‘Controlled Component’?
  A component whose input's value is always driven by the React state.

2. Should we wait to store the users responses from the form into state when they submit the form OR should we update the state with their responses as soon as they enter them? Why.
  Update as soon as they enter them, because the state is the "single source of truth", it updates with every keystroke.

3. How do we target what the user is entering if we have an event handler on an input field?
  Add a name attribute, let the handler function choose what to do based on the value of `event.target.name`

## The Conditional (Ternary) Operator<sup>2</sup>

1. Why would we use a ternary operator?
  To shorten `if` statements into one line of code

2. Rewrite the following statement using a ternary statement:

```js
if(x===y){
  console.log(true);
} else {
  console.log(false);
}
```

```js
x === y ? 'true' : 'false';
```

### Footnotes

<sup>1</sup>https://reactjs.org/docs/forms.html

<sup>2</sup>https://codeburst.io/javascript-the-conditional-ternary-operator-explained-cac7218beeff

[Back](/reading-notes/301/301-TOC.html)