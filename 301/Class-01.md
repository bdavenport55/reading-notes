# Read 01

## Introduction to React

### High Level Overview of React<sup>1</sup>

1. What is React?
    * "an agnostic user interface library"
        * Agnostic - doesn't care where UI will display
        * User Interface - going to be used to create interfaces (charts, bars, fields, widgets, etc)
        * Library - compared to a framework (helper functions, structure), lightweight, has a handful of funcitons and suggestions on structuring, but not as robust as a framework

2. What is a component?
    * "A small piece of code that fills a certain part of the user interface that you're building with React."

3. What is the dataflow of React?
    * data flows down, one way. Data is brought into a component and can flow down to its children but not up stream. Child components can trigger the parent element to gather updated data then pass it down.

4. How do we make a React element a DOM element?
    * it needs to be passed through ReactDOM

5. React is a User Interface ______.
    * Library

6. Which direction does data flow in React?
    * Down, one way

7. Every component manages its own ______.
    * state, which can be passed down to children.

### Component-Based Architecture<sup>2</sup>

1. What is a "component"?

    A set of well-defined functionality that is modular, portable, replaceable, and reusable, and interacts with other components.  It can be deployed independently.

2. What are the characteristics of a component?

    * Reusable
    * Replaceable
    * Not context specific
    * Extensible - can be extended from existing components to provide new behavior
    * Encapsulated - does not expose details of internal processes, variables, or state
    * Independent

3. What are the advantages of using component-based architecture?

    * Ease of deployment - no impact from replacing with newer versions
    * Reduced cost
    * Ease of development - no impact on other parts of systems
    * Reusable
    * Modification of technical complexity - component containers, services
    * Reliability
    * System maintenance and evolution
    * Independent

### What is Props and How to Use it in React<sup>3</sup>

1. What is "props" short for?

    Properties

2. How are props used in React?

    Props are used to pass data from one component to another in a unidirectional flow

3. What is the flow of props?

    1. An attribute and its value are defined
    2. The attribute and value are passed to child component(s)
    3. Props data is rendered

### Footnotes

<sup>1</sup>https://www.youtube.com/watch?v=FRjlF74_EZk

<sup>2</sup>https://www.tutorialspoint.com/software_architecture_design/component_based_architecture.htm

<sup>3</sup>https://itnext.io/what-is-props-and-how-to-use-it-in-react-da307f500da0#:~:text=%E2%80%9CProps%E2%80%9D%20is%20a%20special%20keyword,way%20from%20parent%20to%20child

[Back](/reading-notes/301/301-TOC.html)