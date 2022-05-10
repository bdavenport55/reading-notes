# Read 02

## React lifecycle<sup>1</sup>

1. Based off the diagram, what happens first, the 'render' or the 'componentDidMount'?

    The render appears to be first

2. What is the very first thing to happen in the lifecycle of React?

    Creation of the constructo

3. React things in order that they happen:

   `constructor` > `render` > `React Updates` > `componentDidMount` > `componentWillUnmount`

4. What does `componentDidMount` do?

  Immediately after a method is invoked, if anything needs to be loaded using a network request or to initialize the DOM, it's done here.

## React State vs Props<sup>2</sup>

1. What types of things can you pass in the props?
  Things being displayed to the user that are static - counters, titles, subtitles

2. What is the big difference between props and state?
  Props pass into a component, state is handled inside of the component

3. When do we re-render our application?
  When state is changed within an component, it will re-render then; props change outside of the component

4. What are some examples of things that we could store in state?
  Things that change and update based off of user input - input element, form, check box

### Footnotes

<sup>1</sup>https://medium.com/@joshuablankenshipnola/react-component-lifecycle-events-cb77e670a093

<sup>2</sup>https://www.youtube.com/watch?v=IYvD9oBCuJI

[Back](/reading-notes/301/301-TOC.html)