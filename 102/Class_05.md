# Design web pages with CSS

## Reading notes

### What is CSS?

Stands for "Cascading Style Sheets".  Is used to really make pages "pop" by adding specific styling.  Whereas HTML structured the page, CSS is what gives a page its look.

<br>

CSS is rule based - you define rules specifying groups of styles that should be appliedto particular elements on you web page.

<br>

> ***CSS is the moneymaker of websites***
>  It is what drives user engagement and clicking of "buy buttons"

<br>

Parts of CSS element:

* Selector - *selects* the HTML element that is going to be styled.
* Declaration (one or more) - take form of property/value pairs.
  * Property - charactersitic whose associated value defines one aspect
  * Value - what the property actuall is (color, size, etc).
  * Example - {color: red} color is property, red is value.

  <br>

### CSS Modules

CSS is broken into modules (i.e. backgrounds and borders)

<br>

### Three ways to insert CSS 
 
 * External CSS - all code written in a single external file which is linked to an HTML page
 
 * Internal CSS - code written in the style element inside the head element on a single HTML page

 * Inline CSS - written inline with individual HTML elements

 <br>

### Multiple Style Sheets

If some properties have been defined for the same selector (element) in different style sheets, the value from the last read style sheet will be used.

### Cascading Order

All styles in a page will "cascade" into a new "virtual" style sheet by the following rules, where number one has the highest priority:

  1. Inline style - inside HTML element
  2. External/internal style sheets (in head section)
  3. Browser default

<br>

### Color property

In CSS, there is a list of standard color names that can be used (i.e. red, blue, gray), otherwise specific colors use a hexadecimal color value with a pound sign - #RRGGBB

<br>

### [Back](/reading-notes/102/102-TOC.html)