# HTML Lists, Control Flow with JS, and the CSS Box Model

## HTML Lists

### Three types of HTML Lists:

* Ordered - uses numbers
* Unordered - uses bullets
* Definition - used to define terminology

Lists can be nested inside one another

### Ordered List

```HTML
<ol>
  <li>List item 1</li>
  <li>List item 2</li>
  <li>List item 3</li>
</ol>
```

### Unordered list

```HTML
<ul>
  <li>Any list item</li>
  <li>Any list item</li>
  <li>Any list item</li>
</ul>
```

### Definition list

```HTML
<dl>
  <dt>Term1</dt>
  <dd>Term1 definition</dd>
  <dt>Term2</dt>
  <dd>Term2 defintion</dd>
  <dt>Term3</dt>
  <dd>Term3 definition</dd>
</dl>
```

### Nested list

```HTML
<ul>
  <li>This</li>
  <li>That
    <ul>
      <li>That-a</li>
      <li>That-b</li>
      <li>That-c</li>
    </ul>
  </li>
  <li>Those</li>
</ul>
```

## CSS Boxes

* The nature of CSS is to put each HTML element into a "box"
* CSS can be used to manipulate dimensions of boxes
* Also able to manipulate borders, margins, and padding of boxes
* Elements can be hidden in boxes using display and visibility properties
* Block-level boxes can be made into inline boxes and vice versa
* Controlling width of boxes can improve readability of text
* CSS3 has new features - ability to create image borders and rounded borders

### Border, Margin, Padding

![CSS boxes](http://www.basicsbehind.com/wp-content/uploads/2015/08/css-box-model.png)
> Source: http://www.basicsbehind.com/wp-content/uploads/2015/08/css-box-model.png

## JavaScript

### Switch statements

* starts with `switch` value, each case indicates possible value for this variable and the code that should run if the variable matches that value.

```Javascript
switch (level) {
  case 'One':
  title = 'Level 1';
  break;

  case 'Two':
    title = 'Level 2';
    break;

  case 'Three':
    title = 'Level 3';
    break;

  default:
    title = 'Test';
    break;
}
```

### If/Else vs. Switch

* If/else will check check every `if` statement, even if a match has already been found.

* In switch, once a match is found, code is ran without checking any others.

* If/else does not require `else`, it can run with only an `if`

* Switch has a `default` option that is ran if no matches are found

### Truthy and Falsy

[Back](/reading-notes/201/201-TOC.html)