# Programming with JavaScript

[home](README.md)

## Access Content

- SELECT HTML AREAS element, attribute, text
  - ie. select text inside all `<h1>` elements on page
  - select elements that have a certain class attribute
  - find what was entered as text input who's id attribute has a value of **email**

## Make sites more interactive

- ADD (or remove) element, attribute, text
  - add paragraph text after the **first** `<h>1` element
  - change value of \__class_ elements to trigger new CSS rule
    change size og an `<img> element

## Program Rules

- Specify steps for a browser to follow, allowing access to ghange the content of a page.
  - enlarge an image user clicks
  - mortgage calc - collet inormation, calculate, and display repayments
  - animation could check dimensions and location of bottom to move area of the viewport.

## React to Events

- Specify a script should run when:
  - a button is pressed
  - link clicked (or tapped _on phone_)
  - cursor hover
  - inyterval of time has passed
  - informatin has beeen added to a form
  - a web page finished loading

## - Access - Modify - Program - React

- Slideshow example:
  - **React** script triggered when page loads
  - **Access** Get each slide from slide show
  - **Program** Set a timer
  - **Modify** Change when a slide is shown
  - **React** when a user clicks a button show a new slide
  - **Program** determine what slide to show
  - **Modify** show the requested slide

## HTML & CSS Refresher

- HTML
  - **ELEMENTS** - added to content to show structure - OPENING and CLOSING
  - **TAGS** (some tags are SELF CLOSING (ie. `<img>`))
  - Opening tags can carry **ATTRIBUTES**. Their **VALUE** is usually given in quotes (")

```html
<p class="fruit">peach</p>
```

- CSS
  - **SELECTORS** (before "{" ) indicate what ELEMENTS the rule applies.
  - The DECLARATION BLOCK is made of the:
    - PROPERTY **NAME** (after "{" ) and
    - the PROPERTY **VALUE** (after ": " ) (followed by ";}" ).

```css
.fruit {color: pink;}
```

IE8 caveats - see the book [download](http://javascriptbook.com) for additional help

> Helpful link: [How Do Computers Work](how_computers_work.md)

Scripts are like - recipes, handbooks, manuals.  Step-by-step process.

__Define the GOAL__
What do you want the computer to solve?

__DESIGN the SCRIPT__
Split the gola into s series of tasks
What info is needed for each task

__CODE Each Step__
write in appropriate coding language

__Tasks__ needed to complete, broken into series of __STEPS__ <-- lines of code

__VOCABLULARY__ words computers understand
__SYNTAX__ how the words are put together
___PROGRAMATICALLY__ - follow instructions one after the other.  START with known information and build.

Height EXAMPLE - Find height of tallest person

1. find hight of FIRST person
1. Assume that is tallest person
1. Look at height of remaining people, compare to "tallest person".  
1. If greater than current tallest, that is the new "tallest person"
1. Once checked all people, tell me who is tallest.

Script - series of short instructions, each to solve problem at hand

## Expressions

Evaluates (results in) a SINGLE VALUE.

1. Expressions that assign a VALUE to a VARIABLE
    1. variables need values to be useful 
    1. __var color = 'beige':__
1. Expressions that use TWO OR MORE VALUES to RETURN A SINGLE VALUE
    1. Perform OPERATIONS on individual values to determine a single value
    1. __var area = 3 * 2;__

## Operators

EXPRESSIONS rely on __OPERATORS__ - allow creation of single value from multiple values

- ASSIGNMENT Operators - assign a value to a variable 
    - > __color = "beige";__
- COMPARISON Operators - compare two values to return TRUE or FALSE 
    - > __buy = 3 > 5;__
- ARITHMETIC Operators - perform basic math
    - > __area = 3 * 2__

NAME | OPERATOR | Purpose & Notes | Example | Results
--- | --- | --- | --- | --- 
Addition | + | Adds values | 10 + 5 | 15 |
Subtraction | - | Subtracts values | 10 - 5 | 5
Division | / | Divides values | 10 / 5 | 2
Multiplication | 
Increment |
Decrement |
Modulus |


- LOGICAL Operators - __Combine expressions__ and return TRUE or FALSE
    - > __buy - (5 > 3) && (2 > 4);__
- STRING Operators - __Combine two strings__
    - > __greeting = 'Hi' + 'Molly';__

