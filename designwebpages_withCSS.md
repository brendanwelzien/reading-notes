# CSS

- The design of the website
- create style sheets for multiple   pages
    - this makes the website more uniform


## Chapter 10

- "The key to understanding how CSS works is to imagine that there is an invisible box around every HTML element"

- some characteristics to note...
    - box width and height, borders and color, background color, positions, size, font type
- CSS works by using two parts **selector and declaration**
    - p {font-family: Arial;}
    - you can add more properties: values; like this

- the < link > element is used to tell the browser where to find the file and does not need a closing tag
    - <link href = "" type="text/css" rel=/>

- *< style >* usually sits inside the head element and uses type = text / css

## Chapter 11 - Color

* In picking colors, there are *3* main ways to pick your choice
    - *Color terminology, contrast, and background colors*

***color***

- specified as shown--
    - property {color:name;}
    - property {color:hexcode;}
    - property {rgb(x,y,z);}
    ***background color***
    - use property and then {background-color: label}

***contrast and opacity***
 - ex. 
    p.one {
    background-color: rgb(0,0,0);
    opacity: 0.5;}
    - opacity can be between 0.0 - 1.0

- < hsl > and < hsla > colors are new and include variables such as *hue*, *saturation*, and *lightness*
    - hue expressed as an angle (0 - 360 degress)
    - saturation (%)
    - lightness is percentage as 0%=white, 50%=normal, & 100%=black
    
```bash
    body {
background-color: #C8C8C8;
background-color: hsl(0,0%,78%);}
    p {
background-color: #ffffff;
background-color: hsla(0,100%,100%,0.5);}
```
- *alpha* is expressed as 0-1.0 for transparency

EXAMPLE of COLOR ADDED

```bash
<!DOCTYPE html>
<html>
<head>
 <title>Color</title>
 <style type="text/css">
 body {
 background-color: silver;
 color: white;
 padding: 20px;
 font-family: Arial, Verdana, sans-serif;}
 h1 {
 background-color: #ffffff;
 background-color: hsla(0,100%,100%,0.5);
 color: #64645A;
 padding: inherit;}
 p {
 padding: 5px;
 margin: 0px;}
 p.zero {
 background-color: rgb(238,62,128);}
 p.one {
 background-color: rgb(244,90,139);}
 p.two {
 background-color: rgb(243,106,152);}
 ```

**rules**

- < body > sets a default color for all text and background, both use color names
- < h1 > sets the color of the heading use a hex code
    - there are two values for background-color property as 1. uses fallback color as a hex code
    2. HSLA value for browsers that support this method (angle, saturation, lightness, alpha) ?


[<= Back](README.md)