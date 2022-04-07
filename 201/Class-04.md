# HTML

## Ch. 4 Links <sup>1</sup>

* Links are created using `<a>` element
* `<a>` uses `href` attribute to indicate page being linked to
* Relative links are best used for linking within a site versus qualified URLs
* You can create links to open email programs with an email address in the "to" field
* You can use the `id` attribute to target elements within a page that can be linked to

![Link Anatomy](img/link%20anatomy.jpg)

![Relative Links](img/Relative%20Links.jpg)

## Ch. 15 Layout <sup>2</sup>

### Building Blocks

CSS treats each HTML element as if it's in its own box, which will either be block-level or inline

![Block-level elements](img/block-level%20elements.jpg)

![Inline Elements](img/inline%20elements.jpg)

* If one block-level element sits inside another block-level element then the outer box is known as the *containing* or *parent* element

![Containing Elements](img/Containing%20elements.jpg)

### Controlling position of elements

CSS has **positioning schemes** that allow for control of page layout: normal flow, relative postioning, and absolute positioning. Done with `position` property in CSS. Can also *float* elements with `float` property.

![Positioning Schemes](img/positioning%20schemes.jpg)

*Box offset* may need to be used to tell browser how far from top, bottom, left, or right of page a box should be placed.

# JavaScript

## Ch. 3 Functions, Methods, and Objects <sup>3</sup>

### Functions

Group of statements that allow for performing of specific task

* stored in a structure that keep the from running until 'called' or 'invoked'
* keeps code DRY (don't repeat yourself)
* reusable
* prevent bugs, helps find bugs

#### 2 step process

* define/declare
* run/invoke

```javascript
function (paramaters) {
  statements
}

function(parameters);

function sayHello() {
  document.write('Hello!')
}

sayHello();
```

### Function Declaration

* Simply declaring a function, setting its value so that it can be called upon later  

```javascript
function a(param1, param2) {
  return param1 + param2;
};

var b = a(1,2);
```

### Anonymous functions

* Functions with no names, in the below example on is shown in a function expression

```javascript
var a = function(param1, param2) {
  return param1 + param2;
};

var b = a(1, 2);
```

### 



## Article ["6 Reasons for Pair Programming"](https://www.codefellows.org/blog/6-reasons-for-pair-programming/)

##### Footnotes

<sup>1</sup> Duckett, J. (2011). "HTML & CSS: design and build websites". Chapter 4. Wiley.

<sup>2</sup> Duckett, J. (2011). "HTML & CSS: design and build websites". Chapter 15. Wiley.

<sup>3</sup> Duckett, J. (2011). "JavaScript & JQuery: interactive front-end web development". Chapter 3. Wiley.

[Back](/reading-notes/201/201-TOC.html)