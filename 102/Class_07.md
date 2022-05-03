# Programming with JavaScript

## Control Flow

* the order in which the computer executes statements
* code is run from first line down to last, changing only at the command of structures within the code that tell it so (conditionals, loops, etc.)

## Functions

* a block of code designed to perform a particular task
* in JS, a function executes when something calls it (invokes it), or causes it to happen
* defined with keyword `function`, followed by a name, followed by parenthesis, then curly brackets
* __arguments: giving a function information__
* __parameter: information a function gets__


``` javascript

function name(parameter1, parameter2, parameter3) {
    // code to be executed
}

```

### Function Return

When JS reaches a `return` statement, the function will stop executing and a 'return value' is returned to the function caller

```javascript

let x = myFunction(4, 3);   // Function is called, return value will end up in x

function myFunction(a, b) {
  return a * b;             // Function returns the product of a and b
}

//x will be 12

```

### Functions Used as Variables

Functions can be used as the value of a variable

```javascript

let x = toCelsius(77);
let text = "The temperature is " + x + " Celsius";

let text = "The temperature is " + toCelsius(77) + " Celsius";

```

### Local Variables

Variables declared within a JS function can only be used inside of that function 

```javascript

// code here can NOT use carName

function myFunction() {
  let carName = "Volvo";
  // code here CAN use carName
}

// code here can NOT use carName

```

### Operators

```javascript

// '+' operator adds or 'concatenates'
let x = 'hello ';
let y = 'world';
let z = x + y;
console.log(z); // --> 'hello world'
console.log('hello ' + 'world'); // --> 'hello world'
console.log(4 + 5); // --> 9

// '=' operator, 'assignment' operator, assigns value to variable
let x = 10;
let phrase = 'hello world';

// '*' 'multiplication' operator, multiplies numbers
console.log(2 * 2); // --> 4

```

### [Back](/reading-notes/102/102-TOC.html)
