# Javascript

- Javascript gives your site functionality
- Object-oriented language
    - uses variables, loops, functions, and data to perform things
    -
## Duckett pages 43-69

- html is content layer .html
- css is presentation layer .css
- javascript is behavior layer .js

*How to Use Objects and Methods*

- document.write('Good afternoon!');
- consists of an object, member operator, and method with parameters
- javascript runs where found in the html
    - < script > element causes JS to stop and check if it needs to do anything, it tells the browser to load the JS file

**Statements**

- a *script* is a series of instructions that a computer can follow, each step is a **statement**
- JS is *case-sensitive*
- a statement is individual instruction and each one should start on a new line and end with a ;
    - statements surrounded by curly braced are *code blocks*
    - these contain a statement and may be grouped together

- write **comments** to explain code
- multi line comments are pink, to comment = /* */
- single-line comments are gray, to comment = //
- javascript code is green

-a script will have to store information to do its job, use *variables* to do so

***Variables and how to declare them***

- var quantity;
    - var is the keyword and the quantity is the variable name
    - once assigned a variable, you can tell it information or assign value

    - var quantity;
    - quantity= 3;

**Data types**

- numeric data (no comma and there is decimals)
- string data (letters and other characters closed by single or double quotes)
- boolean data (ewither true or false or on and off)
    - miscelleaneous--> arrays, objects, undefined, and null
    -*escaping* is done by using a backwards slash \ before any quote mark appears within a string... It tells the interpreter that the character is part of the string not the end

**shorthands for creating variables**
1. variables declared then values are assigned in statement
```bash
var price =5;
var quantity =14;
var total =price*quantity;
```

2. three variables are declared on the same line, then values are assigned to each

```bash
 var price, quantity, total; 
price =5;
quantity= 14;
total =price * quantity;
```

3. two variables are declared and assigned values on the same line. Then one is declared and assigned a value on the next line

```bash
var price =5, quantity =14;
var total = price * quantity;
```

***Changing the value of a variable***
- you do not need to use *var* to assign a new value
    - just use the variable name, the = sign, and the new value

    OLD--> instock= true;
    NEW --> instock=false;

## Important Rules for Naming Variables

1. the name must start with a letter, $, or _, and it *cannot start with a number*
2. the name *can contain* these afterwords, but you must not use a - or . in a variable name.
3. you cannot use **keywords or reserved** words.
4. all variables are case sensitive
5. use a name that describes the kind of info that the variable stores
to add  js file into html  --><script src="app.js"></script>

[<= Back](README.md)
