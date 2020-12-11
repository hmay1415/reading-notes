# Programming with JavaScript

## Class Notes

- variable - store piece of info
- datatypes: string ('hello'), number (45)
- string of '45' does not equal 45
- = assignment operator
- == equpals
- === strickly equals, compares value AND data type
- '45' == 45 is true, 'fortyfive' = 45 is not true
- '45' === 45 is not even true
- boolean type - true or false
- arrays and objects - will cover in 201
- when asking for user input, need to work out how to make sure different versions of the same answer are recogized as the same (yes, yessss, y) - toUppercase, toLowercase are examples of this. Just take 1st letter is an option
- || is or operator, && is and operator
- HTML runs top to bottom. Will run until hits JS and then pauses for
command

## Intro and Scripts (pg 1 -24)

Uses of JavaScript:

- ACCESS content (all txt with x properties)
- MODIFY elements, attributes and text to page or remove them
- PROGRAM rules - zoom in of image, in page calculator, etc.
- REACT to events - click, hover, time out

Can modify content of webpage while it's been viewed in browser
API is Application Programming Interface

Script - a series of instructions a computer can follow to achieve a goal
To write script - first state goal and then list tasks that need to be completed to achieve it (flowchart!)
Computer can't learn - need to provide enough detail to perform task every time as if it were the first
Computers solve problems programmatically - series of sequential instructions

## Expressions and Operations (pg 74-79)

Expression - results in a single value. Two types:

1. just assigns a value to a variable `var color = 'beige':`
2. use two or more values to return a single value `var area = 3 * 2:`

Operators - create single value from one or more values
Assignment operators - assign value to a variable
Arithmetic operators - perform basic math
String operators - combine 2 strings `greeting = 'Hi' + 'Molly';`
Comparison operators - compare 2 values and return true or false `buy = 3 < 5;` value of buy is falst
Logical operators - combine expressions and return true or false `buy = (5>3) && (2<4);` value of buy is true
++ increment - adds 1 to current number
-- decrement - subtracts 1 from current number
% modulus - divides two values and returns remainder
mult/div before add/subt
Only 1 string operator + - concatenation is joining 2 or more strings
quotes around number makes it a string - can't perform addition on strings:`'7' + '9' = 79`
Nan = not a number

## Functions (pg 88-94)

Reminder - for code block do not write a semicolon after closing curly brace like you do after a statement
Parameters - pieces of information passed to a function
Return value - answer from function
Declare a function using keyword "function"
Function name is followed by parentheses `sayHello()`
Calling a function - executing statements between curly braces with 1 line of code
Arguments can be values `getArea(3,5)` or variables `getArea(wallWidth, wallHeight)`
Parameters are variables, arguments are actual values
Return - used to return a value to the code that called the function

To navigate back to the main page click [here](https://hmay1415.github.io/reading-notes/)
