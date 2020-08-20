## Duckett Pages 150-151, 156, 157, 170-173, 176

## Comparison Operators: Evaluating Conditions:

* == is comparing two values to see if they are the same
* != is comparing to see if they are not the same
* === compares two values to check both data type and value are the same... '3'=== 3 returns false because they are not the same data type or value
* !== compares two values to check that both data type are not the same... '3'!== 3 returns true
* ( > ) checks if left is greater than right
* ( < ) checks if left is less than the right
* ( >= ) is greater than or equal to
* ( >= ) is less than or equal to

## Logical Operators:

- comparison operators usually return *single* values of *true* and *false*... **logical operators** allow you to compare results of more than one comparison operator

```bash
((4<2) && (2>=3))
```
- the && is the logical and operator
    - it checks to see whether both expressions on either side return true
    - if one of the expressions are *false* then it will return *false*

- || is the logical or operator

    - if either expression is true, then it will return *true*
    - if *both* are *false*, it will return *false*
- ! is the logical not operator
    - takes a single boolean value and inverts it
        - !(2 < 1) returns true
    - this reverses the expression
    - !true returns *false*
    - !false returns *true*

- logical expressions are read from left to right

## Loops
- loops check a *condition*, if it returns *true*, then the code block will run!
    - it will repeat until condition returns *false*
- **3 common types of loops**
1. **for**
    - for running a code a certain amount of times
2. **while**
    - if you do not know how many times the code should run, use the while loop
3. **do while**
    - the *do...while* loop is similar to while, but will run statements in curly braces at least once, even if the condition returns *false*

```bash
for (var i = 0; i <10; i++) {
    document.write(i);
}
```
- if the variable i is less than ten, the code inside the curly braces executes, then the counter is incremented

## Counter

- A **for** loop uses a counter as a condition which instructs the code to run a specific amount of times
(for the condition above)

- ***Initializaton***
    - creates a variable and set it to 0. This variable is commonly called i and acts as the counter
    - var i = 0;
    - the variable is only created the first time when the loop runs, may be declard before the condition
- ***Condition***
    - the loop should continue to run until the counter reaches a specified number
    - i <10 ;
    - the value is set to 0 and runs 10 times before stopping
    - you can also hold *rounds* for var rounds to how many go-arounds a loop may go
        - var rounds = 3;
            i < (rounds);
- ***Update***
    - every time the loops has run the statements in curly braces, it adds one to the counter
    - i++
    - one is added using (++) operator
    - read as 'take the variable i, and add one using the ++ operator"
    - you can use (--) to count downward as well


[<= Back](README.md)