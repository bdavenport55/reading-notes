# Read 03

## Lists and Keys<sup>1</sup>

1. What does .map() return?
  A new array from each index iterated over from an original array.

2. If I want to loop through an array and display each value in JSX, how do I do that in React?
  Return an `<li>` element first, assign the resulting array to be the list items

  ```js
    const numbers = [1, 2, 3, 4, 5];
    const listItems = numbers.map((number) =>
    <li>{number}</li>
  );
  ```

3. Each list item needs a unique ____.
  Key

4. What is the purpose of a key?
  Keys help React identify which items have changed, are added, or are removed.

## The Spread Operator<sup>2</sup>

1. What is the spread operator?
  Javascript syntax used to expand an iterable object into the list of arguments

2. List 4 things that the spread operator can do.

* Copying an array
* Concatenating or combining arrays
* Adding to state in React
* Using an array as arguments

3. Give an example of using the spread operator to combine two arrays.

```js  
const myArray = [`🤪`,`🐻`,`🎌`]
const yourArray = [`🙂`,`🤗`,`🤩`]
const ourArray = [...myArray,...yourArray]
console.log(...ourArray) // 🤪 🐻 🎌 🙂 🤗 🤩
```

4. Give an example of using the spread operator to add a new item to an array.

```js  
const fewFruit = ['🍏','🍊','🍌']
const fewMoreFruit = ['🍉', '🍍', ...fewFruit]
console.log(fewMoreFruit) //  Array(5) [ "🍉", "🍍", "🍏", "🍊", "🍌" ]
```

5. Give an example of using the spread operator to combine two objects into one.

```js  
const objectOne = {hello: "🤪"}
const objectTwo = {world: "🐻"}
const objectThree = {...objectOne, ...objectTwo, laugh: "😂"}
console.log(objectThree) // Object { hello: "🤪", world: "🐻", laugh: "😂" }
const objectFour = {...objectOne, ...objectTwo, laugh: () => {console.log("😂".repeat(5))}}
objectFour.laugh() // 😂😂😂😂😂
```

## How to Pass Functions Between Components<sup>3</sup>

1. In the video, what is the first step that the developer does to pass functions between components?
  Writes the increment function

2. In your own words, what does the `increment` function do?
  Increments, or adds, a count by a specified amount for the argument (person) passed into it.

3. How can you pass a method from a parent component into a child component?
  

4. How does the child component invoke a method that was passed to it from a parent component?

### Footnotes

<sup>1</sup><https://reactjs.org/docs/lists-and-keys.html>

<sup>2</sup><https://medium.com/coding-at-dawn/how-to-use-the-spread-operator-in-javascript-b9e4a8b06fab>

<sup>3</sup><https://www.youtube.com/watch?v=c05OL7XbwXU>

[Back](/reading-notes/301/301-TOC.html)
