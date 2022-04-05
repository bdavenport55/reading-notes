# HTML Text, CSS Introduction, and Basic JavaScript Instructions

## **HTML Text**

Elements are used to describe structure of page (headings, subheadings, paragraphs, etc.)

Elements can also provide semantic information, or information about what is in the element itself (e.g. `<header>` is the block at the top of a page, `<main>` is the main part of a page).

### Headings

* `<h1>` through `<h6>`
  * The larger the number, the deeper the level the heading, the smaller it is

### `<p>` tags

* Identify paragraphs, blocks of text

### Other tags

* `<b>` - bold
* `<i>` - italic
* `<sup>` - superscript
* `<sub>` - subscript
* `<br />` - line break
* `<hr />` - horizontal rule
* `<strong>` - shown as bold in browsers
* `<em>` - 'emphasis', shown as italic in browsers
* `<blockquote>` - used for longer quotes that take up to an entire paragraph.
* `<q>` - shorter quote
* `<abbr>` - abbreviation
* `<cite>` - referencing a work
* `<dfn>` - definition
* `<address>` - contact details for author of page
* `<ins>` - show content that has been inserted, usually underlined
* `<del>` - show content to be removed, usually with a line through it
* `<s>` - something that is no longer accurate, shown with a line through it

## CSS

* CSS individually affects each HTML element and uses rules to indicate how that element should look

* Selectors specify which HTML elements a rule will apply to, and declarations specify what customization is being done

* Different selectors target different elements

* Declarations are made up of the property of the element to be customized, and the way in which the element is to be customized

* CSS can be written on a separate page and linked into an HTML document or written 'in-line' of HTML text

```CSS
p {font-family: Arial;}
```
In the above case, `p` is the selector and everything between the curly braces is the declaration

`font-family` is the property, `Arial` is the value

* CSS rules 'cascade', meaning styles apply to HTML elements in a certain order of precedence
  * The last and most specific rule takes precedence
  ```CSS
  i { color: green;}
  b { color: blue;}
  i { color: red;}
  ```
  The second `i` takes precedence since it is last

## JavaScript

### Basic JavaScript Instructions

* A script is a combination of statements, and statements are individual instructions, like steps in a recipe.

* Scripts contain very precise instructions

* Variables are used to store pieces of information that can be referred to later in script

* Arrays are a type of variable that can store numerous pieces of information `[1, 2, 3]`, `[a, b, c]`

* JavaScript is written with numbers (0-9), strings-text('hello', 'the temperature is...'), and Boolean values (true/false).

* Expressions evaluate, with the use of operators, into a single value

* JS is 'loosely-typed', it does not require explicit specification of variables and objects

* JS is 'dynamic', meaning data types of variables can be changed after they are declared

 ```javascript
 let a = 'hello';
 let b = ' world';
 console.log(a + b); // ---> 'hello world'
 ``` 


### Decisions and Loops

* Conditional statements allow code to make decisions about what to do next

* Comparison operators compare two operands

* Logical operators allow for combination of more than one set of comparison operators

* if/else statements allow one set of code to run if a condition is true or false

* Switch statements allow comparison of a value against possible outcomes

[Back](/reading-notes/201/201-TOC.html)