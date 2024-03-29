# HTML Block and Inline Elements



* Every HTML element has a default display value, depending on what type of element it is.
* There are two display values:
    *  Block 
    

    *  Inline.

## Block-level Elements


* A block-level element always starts on a new line, and the browsers automatically add some space (a margin) before and after the element.
* A block-level element always takes up the full width available (stretches out to the left and right as far as it can).
* Two commonly used block elements are:
    *  < p > 
    *  < div >.

* The < p > element defines a paragraph in an HTML document.
* The < div > element defines a division or a section in an HTML document.

**Example:**
```
<p>Hello World</p>
<div>Hello World</div> 
```

* Here are the block-level elements in HTML:

```


<address>
<article>
<aside>
<blockquote>
<canvas>
<dd>
<div>
<dl>
<dt>
<fieldset>
<figcaption>
<figure>
<footer>
<form>
<h1>-<h6>
<header>
<hr>
<li>
<main>
<nav>
<noscript>
<ol>
<p>
<pre>
<section>
<table>
<tfoot>
<ul>
<video>

```

## Inline Elements

* An inline element does not start on a new line.
* An inline element only takes up as much width as necessary.
* This is a < span > element inside a paragraph.

**Example:**
```
 <span>Hello World</span> 
 ```

**Main point:**
* An inline element cannot contain a block-level element!


Here are the inline elements in html
```

<a>
<abbr>
<acronym>
<b>
<bdo>
<big>
<br>
<button>
<cite>
<code>
<dfn>
<em>
<i>
<img>
<input>
<kbd>
<label>
<map>
<object>
<output>
<q>
<samp>
<script>
<select>
<small>
<span>
<strong>
<sub>
<sup>
<textarea>
<time>
<tt>
<var>
```


## The < div > Element

* The < div > element is often used as a container for other HTML elements.
* The < div > element has no required attributes, but style, class and id are common.
* When used together with CSS, the < div > element can be used to style blocks of content:


**Example:**
```
<!DOCTYPE html>
<html>
<style>
div{
    background-color:black;
    color:white;
    padding:20px;
}
</style>
<head>
</head>
<body>

<div>
  <h2>London</h2>
  <p>London is the capital city of England. It is the most populous city in the United Kingdom, with a metropolitan area of over 13 million inhabitants.</p>
  <p>Standing on the River Thames, London has been a major settlement for two millennia, its history going back to its founding by the Romans, who named it Londinium.</p>
</div> 

</body>
</html>
```

## The < span > Element

* The < span > element is an inline container used to mark up a part of a text, or a part of a document.
* The < span > element has no required attributes, but style, class and id are common.
* When used together with CSS, the < span > element can be used to style parts of the text:

```
<!DOCTYPE html>
<html>
<body>

<h1>The span element</h1>

<p>My mother has <span style="color:blue;font-weight:bold">blue</span> eyes and my father has <span style="color:darkolivegreen;font-weight:bold">dark green</span> eyes.</p>

</body>
</html>
```


## Inline Block elements:

* Compared to display: inline, the major difference is that display: inline-block allows to set a width and height on the element.
* Also, with display: inline-block, the top and bottom margins/paddings are respected, but with display: inline they are not.
* Compared to display: block, the major difference is that display: inline-block does not add a line-break after the element, so the element can sit next to other elements.

**Example:**

```
<!DOCTYPE html>
<html>
<head>
<style>
span.a {
  display: inline; /* the default for span */
  width: 100px;
  height: 100px;
  padding: 5px;
  border: 1px solid blue;  
  background-color: yellow; 
}

span.b {
  display: inline-block;
  width: 100px;
  height: 100px;
  padding: 5px;
  border: 1px solid blue;    
  background-color: yellow; 
}

span.c {
  display: block;
  width: 100px;
  height: 100px;
  padding: 5px;
  border: 1px solid blue;    
  background-color: yellow; 
}
</style>
</head>
<body>

<h1>The display Property</h1>

<h2>display: inline</h2>
<div>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vestibulum consequat scelerisque elit sit amet consequat. Aliquam erat volutpat. <span class="a">Aliquam</span> <span class="a">venenatis</span> gravida nisl sit amet facilisis. Nullam cursus fermentum velit sed laoreet. </div>

<h2>display: inline-block</h2>
<div>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vestibulum consequat scelerisque elit sit amet consequat. Aliquam erat volutpat. <span class="b">Aliquam</span> <span class="b">venenatis</span> gravida nisl sit amet facilisis. Nullam cursus fermentum velit sed laoreet. </div>

<h2>display: block</h2>
<div>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vestibulum consequat scelerisque elit sit amet consequat. Aliquam erat volutpat. <span class="c">Aliquam</span> <span class="c">venenatis</span> gravida nisl sit amet facilisis. Nullam cursus fermentum velit sed laoreet. </div>

</body>
</html>

```


## References:

* [MDN](https://developer.mozilla.org/en-US/docs/Web/HTML/Inline_elements)
* [w3schools](https://www.w3schools.com/html/html_blocks.asp)


