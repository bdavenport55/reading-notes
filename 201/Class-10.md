# Read 10

## JavaScript

### Error Handling & Debugging <sup>1</sup>

* understanding execution contexts and stacks will help you find bugs
* debugging - process of finding errors done by deduction
* console helps locate the error
* JS7 has 7 error types, creates its own error object, and tells which line error is on
* if errors expected, can use `try`, `catch`, and `finally` statements

#### Execution Context

* global context - code in script but not in a function, only one global context in any page
* function context - code within a function, each function has its own context
* eval context (not shown) - text executed like code in an internal function called `eval()`
* variable scope
  * global scope - variable declared outside of a function can be used anywhere else
  * function-level scope - variable declared in a function can only be used in that function

#### The Stack

JavaScript interpreter processes one line of code at a time, when a statement needs data from another function it *stacks* (or piles) the new function on top of current task

* hoisting - functions can be called before they are declared if they are created using function declarations, not function expressions
  * also, values can be assigned variables not yet declared

#### Scope

* lexical scope - functions are linked to the object they were defined *within*

![lexical scope](img/lexical%20scope.png)

#### Understanding Errors

* if a statement generates an error, then it throws an **exception**, interpreter stops and looks for exception-handling code
* javascript creates an object that holds details about the error and logs it in the console
* several different error types and corresponding objects that get logged

#### Dealing with errors

* debug - track down source of error and fix it
* have a debugging workflow
  * where is the problem
  * what is it

##### Footnotes

<sup>1</sup> Duckett, J. (2011). "JavaScript & JQuery: interactive front-end web development". Chapter 10. Wiley.

[Back](/reading-notes/201/201-TOC.html)