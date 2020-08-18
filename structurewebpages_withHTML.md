# HTML
* Structure of the website
    * head, body, text
* gives you control, but slows down authoring
* ex...
     ```
    <div> </div> 
    ```

**if you do not have a close tag the web page will not render**

***<html>*** **duckett**

## *Chapter 18- Process and Design*

* Every site should be designed for target audience, so consider the characteristics of this audience

- ex. education, marital status, occupation, 

* Now consider why people are visiting!
 - what are there key motivations and/or goals and what information would they need from the website?
 - they may visit often so constant updates may be required

**TERMS**

Term | Definition
---- | ----------
site map | diagram of the pages
card sorting | placing each piece of info on a paper then organizing into related groups


**Wireframes**
- a simple sketch of they key information needed for each page.
- may include logos, links, policies, conditions,
- all must be prioritized in a specific order into blocks and chunks for visual reference

**Visual Hierarchy**
*elements*
- size, color, style, consistency, headings

*grouping and similarity*
- proximity, closure, continuance, white space, color, borders

## *Chapter 1- Structure*
* To start a webpage, go to *textedit* and begin

Term | Usage
---- | ----------
<body> </body> | everything in this element is shown inside main browser
<head> </head> | before body element, contains about and <title>
<title> </title> | included with <head>

## *Chapter 17- HTML5 Layout*

* most content is inside <div> element
* <header> main header
* <footer> for the bottom

example

```bash
<header>
<h1>Yoko's Kitchen</h1> 
<nav>
<ul>
<li><a href="" class="current">home</a></li> <li><a href="">classes</a></li>
<li><a href="">catering</a></li>
<li><a href="">about</a></li>
<li><a href="">contact</a></li>
</ul> 
</nav>
</header>
```

* the <nav> </nav> element is to contain the navigational blocks on the site

* the <article> </article> element acts as a container for sections of a page that can stand alone (if a page has several articles then one would separate them by using this element)

* <aside> </aside> element has two purposes whether it is inside *<article>* or not

    - when <aside> is inside an *<article>, it contains info related to article but not essential to overall meaning
    - when <aside> is not inside an *<article>, it is a container for content related to the page (contains links to other sections of the site, related posted, search box, etc.)

* <section> </section> groups related content together and each would have its own heading

```bash
<section class="popular-recipes">
<h2>Popular Recipes</h2>
<a href="">Yakitori (grilled chicken)</a>
<a href="">Tsukune (minced chicken patties)</a> <a href="">Okonomiyaki (savory pancakes)</a> <a href="">Mizutaki (chicken stew)</a>
</section>
<section class="contact-details">
<h2>Contact</h2> <p>Yoko's Kitchen<br />
27 Redchurch Street<br /> Shoreditch<br />
London E2 7DP</p>
</section>
```

* <hgroup> </hgroup> is to group together a set of one or more <h1> to <h6> elements so they are one single heading

* <figure> or <figcaption> for images, videos, graphs, diagrams, etc in referencing them

* section elements by using <div>

```bash
<div class="wrapper"> 
<header>
<h1>Yoko's Kitchen</h1> 
<nav>
<!-- nav content here -->
 </nav>
</header>
<section class="courses">
<!-- section content here --> 
</section>
<aside>
<!-- aside content here --> 
</aside>
<footer>
<!-- footer content here --> 
</footer>
</div><!-- .wrapper -->
```

* <a> allows authors to place an element around a block level element that contains child elements



## *Chapter 8- Extra Markup*

* due to several versions of html, each web page should start with <!DOCTYPE html> to tell the browser which version to use

* if you want to add a comment to code it is <!-- comment here -->
* ID attributes is allows for style and no two elements can have the same attribute
* class attribute is used to identify several elements
* block elements start a new line including <h1>, <p>, <ul>, <li>
* inline elements for keep words organized? <a>, <b>, <em>, <img>
* grouping text and elements in a block <div>

```bash
<div id="header">
<img src="images/logo.gif" alt="Anish Kapoor" /> <ul>
<li><a href="index.html">Home</a></li>
<li><a href="biography.html">Biography</a></li> <li><a href="works.html">Works</a></li>
<li><a href="contact.html">Contact</a></li>
</ul>
</div><!-- end of header -->
```

* grouping text and elements inline is <span> (differentiates a text counterpart)
* <iframe> is a window in a page where you can see another page like for displaying maps

* <meta> displays information about your page
[<= Back](README.md)