# Javascript

## Duckett Intro + Scripts 1-24
* JS makes web pages more interactive
    * JS can be used to select / access any element, attribute, or text from an HTML
    * JS can be used to modify content to the page
    * JS can be used to program rules like a *recipe*
    * JS can allow for a reaction of events, something should run when an event has occurred

*refresh*
- HTML uses opening and closing tags and its content, some have no closing tag like < img >
- opening tags can have attributes <p class = >
- CSS  has a selector, property name and value to describe the contents of the webpage

**Concepts of Computer Programming**

### What is a script and how do I create one?
### How do computers fit in with the world?
### How do I write a script for a web page?

***What is a script and how do I create one?***
- a script is a series of instructions that a computer can followe to achieve a goal, like a recipe
- uses step-by-step instructions (the more specific the better)
- a browser may use different parts of script depending on how user interacts with webpage
- scripts can also run different sections of the code in response
*Writing a script*
    - you need to first state your goal and then list the tasks that need to be completed to achieve it
    - start with big picture, then break it down into smaller steps
1. define the goal
2. design the script
    - series of tasks in reaching the goal
3. Code each of the tasks!
*Designing a script: tasks*
- flowcharts may be helpful
- listing the steps then translating them into lines of code
- important to understand the vocabulary, syntax, programmatic approaches, and debugging
- thinking like a computer by running through the instructions and finding gaps

ex. from Duckett book
```bash
Customers can have a name added to the plaque; each letter costs $5. When a user enters a name, show the how much it will cost.

Next, break it into a series of tasks that have to be performed in order to achieve the goals:

1. The script is triggered when the button is clicked. 
2. It collects the name entered into the form field. 
3. It checks that the user has entered a value.
4. If the user has not entered anything, a message will appear telling them to enter a name.
5. If a name has been entered, calculate the cost ofthe sign by multiplying the number of letters by the cost per letter.
6. Show how much the plaque costs.
```
- flowcharts will be helpful if you use labels like generic steps, events, inoput or output, and decisions

## Expressions and Operators 74 -79

- an *expression* evaluates results in a single value
1. Expressions that assign a value to a variable
    var color = brown
2. expressions that use two+ values to return to a single value
    var area = 3 * 2
- *operators* allow single values to be made from one or more values
    - assignment operators (value to a variable), arithmetic operators (basic math), string operators (combining strings), comparison operators (comparing two values and return true or false), and logical operators (combine expressions and return true or false &&)

*arithmetic operators*
name | operator
---- | ------
addition | +
subtraction | -
division | /
multiplication | *
increment | ++ (adds one to current number)
decrement | --
modulus % | divides two values and returns remainder

- order of execution
    - mulitplication and divison performed before addition and subtraction

*string operators*
- only uses the +, bringing two or more strings together is called concatentation

## Functions 88-94
- functions let you group a series of statements togeher to perform a task!
- a function needs a label, parameters, and the ngives a return value

```bash
functionkeyword functionname() {
    document.write('Hello!');
}
```
- declaring a function uses the the function keyword which is function keyword, the function name, and the code block
- calling a function you can use functionname()
- functions may need info... giving it parameters to perform its task



function askUserForName(){
    var userName = prompt("Please enter your name: ");
    alert("Hello"+ userName);
    return userName;
}
askUserForName();






[<= Back](README.md)
