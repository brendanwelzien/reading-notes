# Class 1 Review

Github
- Create a repository
  - add markdown to the README.md (the readme is what rendersthe page)
  - deployed/published by going into settings and went to 'github pages' and selected branch as 'master'
  
  Markdown
  - table
  - inserted an image
  - linked a file
  - quotation
  - order and unordered list
  
# Class 2 Review

**Git**
- HEAD = the label meaning..
> you are here 
>
- you can also assign messages to commits
- you use Git to take snapshots of your code at points in time

**GitHub**
> your code in the cloud
>
- a way to share code with others
- an online place to store your code
- uses Git to help manage team's work
  - version tracking, reviewing changes, keeping changes separate until you want to add them in at different times
 ***do not make changes directly on github anymore as it makes errors through terminal***
 
**git clone** (link url) to copy url into terminal
**git add** (file name) to add back to github
**git status**
**git commit** -m "change capitalizations and add some descriptive text"
**git push** origin master
documents/projects/codefellows/code102
code 102 ls

# Class 4 Notes

- Git is our version control (what changes we made along the way)
- Github is the storage facility as well as the collaboration side

**Git flow**
- get info from Github to local computer

```bash
 git clone link_from_git_hub
```
Get info from local computer to Github

```bash
#(A)dd(C)ommit(P)ush
git add .
git commit -m "Made changes to text files"
git push origin master
```
# Class 5 Notes

**Semantic are tags that possess properties that are easy to understand**
- sec vs div... makes accessbility more present

**Wireframing is essential for organization for your coding**


# Java Script Review Notes

- Declaring Variables
  var label;
  var label = 'name'; ---> string
  var labelAge= 45; ---> number
  var labelAge= '45';
  5 +5 = 10
  '5' +'5' = '55'

  boolean is true or false
  array types = [1, 2, 3, 4]

- prompting user for info
  - prompt('Message to User');
  - confirm('Messaage to User');

- conditional statements
  - does something = something else
  - is something > than something
  - is something < than something 
  - is something equal or not equal to something

- Teaching a robot how to wear a hoodie, the importance of details

  - grab hoodie
  - if it is a zipper hoodie, make sure to unzip it first, if not skip this step
  - hold with both hands out in front of you
  - turn around with front side facing away from you and is upright
  - if it is a zipper hoodie, make sure to unzip it first, if not skip this step
  - begin by grabbing the bottom of the hoodie on each side with your hands and prepare to insert from the top of your body
  - put only yopur head and body through the hoodie, excluding the arms
  - do this until your head and neck goes through the hooded section of the hoodie
  - check to see if your head and neck are inside this section, verify that your vision is not obstructed and that your head and neck are inside of the hoodie
  - insert your right your arm from the bottom of the hoodie while holding your left on the bottom left side of the hoodie
  - make sure your right arm is inserted fully into arm section
  - do this by sliding your right arm up first, and doing one arm at a time
  - make sure your right arm is fully through the arm section by verifying that your hand has fully gone through the arm section and that your hand is visibly present
  - then move onto your left arm.
  - hold your right arm at the base of the hoodie and make and then slide your left arm through the hoodie as explained for the right arm
  - then pull down the hoodie over torso until made comfortable

# Class 9 Review 

* for loops / while loops

* *For loop*
  - known amount of time(s) that we want loop to run

  
*While loop*
  - unknown amount of time(s)... We want some condition to be met


# Final Review 101

## HTML

- h1 should be only 1 on a page
- h2-h6 should be unlimited

## The bare minimum for a website

```bash
- <!DOCTYPE html)
- <html>
    <head>
      <title> title goes here </title>
    </head>
    <body>
    </body>
  </html>
  ```
## CSS
- float: is for moving / wrapping
- id = "id2" (in html) for labeling a design block (can only be used once)
-   in css - #id2 {
  border: black;
  vertical-align: auto;
  etc.
}

- how to target all tags of one type of code... for example for <p>
- p {
  display: inline;
}

    - if only making a change of a p tag inside something else like <article>, you would have to give every p a tag of a class.. Or 
article > p {
  display: inline;
}

## Javascript
- declaring a function (what happens in the function stays in the function)

```bash
function NameofFunction(){
var userNameinsideoffunction= 'brendan'
}
```

- using userName outside of the function will not work unless i do *return* inside the function... (return gives the data) 
so

```bash
function NameofFunction(){
  var userNameinsideoffunction= 'brendan'
  return userNameinsideoffunction // this returns 'brendan'
}
    // 'brendan'
var userNameoutsideoffunction= nameoffunction();
```

- loops
- for loop
  ( var i = 0; i<=10; i= i++){
    console.log(i);
  }
- a single = is an assignment operator
- a double = compares value and not type (try to stay away from it)
- a triple = is an equal operator (compares value and type)
