# JavaScript

## Class Notes

CSS Recap

- `*{border: solid black 1px}` adds border to everything
- `boxsizing: border-box` includes border in box size
- float/relative position hard. flexbox and grid coming in 201/301 and will be easier!

Javascript Intro

- HTML is bones (Content Layer), CSS is skin (Presentation Layer), Java is muscle (Behavior Layer)
- JavaScript - can store variables, iterate through arrays. More of programming language
- Java = compiled language. JavaScript = interpreted langauge
- Variable = temporary storage of something (think of different Amazon homepages for everyone)

## Reading Notes Pgs. 43 - 69

- Progressive Enhancement - 3 layer system
- Keeping JS separate - page can still run if browser has JS turned off
- "calling" method of an object
- `document.write('Good afternoon!');`
- document object reps entire webpage
- period is member operator
- each object has several members
- `write()` allows new content to be written into the page where `<script>` element sits
- parameters - when method requires some info in order to work - in this case the Good afternoon!
- when broswer comes across `<script>` element in HTML file, it stops to load Javascript file and then checks to see if needs to do anything - location is important
- Statement = each individual step or instruction. End with ;
- js is case sensitive
- {} indicate end of code block, not followed by a ;
- each statement starts on a new line
- to write multi line comments `/* comment */`
- to write single line comment use `//` on that line
- variable - temporary bits of information
- declare variable = giving it a name
- var is keyword for variable
- if variable name is more than one word, written in camelCase
- when declaring variable, don't need to specify type
- = is an assignment operator to give variable a value
- variable with no value is unassigned
- Data types:

1. numeric data type (0.75)
2. String data type - letters and enclosed in quotes. must always be on one line
3. Boolean data type - true or faluse

- escaping quotation characters - use backwards slash before any quote marks that appears within string to tell interpreter that the following character is part of the string rather than the end of it
- can change value of variable later in script

Rules for naming variables:

1. name must beign with a letter, dollar sign, or underscore. NO NUMBER
2. name can contain letters, numbers, dollar signs or underscores but No dash - or period . in variable name
3. can't use keywords or reserved words like var
4. case sensitive
5. use name that describes kind of info variable stores ex firstName
6. use camel case for multi words or underscore between words

To navigate back to the main page click [here](https://hmay1415.github.io/reading-notes/)
