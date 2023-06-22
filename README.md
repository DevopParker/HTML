# HTML: HyperText Markup Language

HTML (HyperText Markup Language) is the most basic building block of the Web. It defines the meaning and structure of web content. Other technologies besides HTML are generally used to describe a web page's appearance/presentation (CSS) or functionality/behavior (JavaScript).

HTML uses "markup" to annotate text, images, and other content for display in a Web browser. HTML markup includes special "elements"

[HTML Docs](https://developer.mozilla.org/en-US/docs/Web/HTML)

[W3C Markup Validation Server](https://validator.w3.org/)

The W3C Markup Validation Service is an online tool provided by the World Wide Web Consortium (W3C), which is a standards organization for the World Wide Web. The purpose of the website is to validate the markup validity of web documents. In simpler terms, it allows you to check whether the HTML or XHTML code of a web page conforms to the defined standards and rules set by the W3C.

With elements such as <html> you can add _Attributes_ which lie inside of the element.
- For example <html lang="us-EN"> 
- This html element now has the attribute lang that provide the language "us-EN" as the websites standard.

The standard for most web pages requires element such as:
```
<!DOCTYPE html>
<meta charset="UTF-8">
<meta name="author" content="Devop Parker">
<meta name="description" content="This page contains information to learn HTML">
```
## Key Elements to Know
```
<head>
<title>
<body>
<header>
<footer>
<article>
<section>
<p>
<div>
<span>
<img>
<aside>
<audio>
<canvas>
<datalist>
<details>
<embed>
<nav>
<output>
<progress>
<video>
<ul>
<ol>
<li> 
```

### Common Attributes

```<a href="URL">```

- The href attribute specifies the URL of the page the link goes to.
- You can use href="#top" or href="#" to link to the top of the current page

```
<link rel="icon" href="html5.png" type="image/x-icon">
<link rel="stylesheet" href="main.css" type="text/css">
```
The link element can be used with href to add icons to the title, and even "link" your css stylesheet to your index.html file.

_"White space"_ refers to empty or blank values in the code which the browser reads and renders. Html has a special feature of collapsing these white spaces. If you put extra/consecutive white spaces or newlines in the code it will regard it as one white space this is known as collapsing of white spaces.

The ```<br>``` tag allows us to "break" the link in for example a paragraph.

Every HTML element has a default display value, depending on what type of element it is.

There are two display values: block and inline.

### Block-level Elements

A block-level element always starts on a new line, and the browser automatically add some space (margin) before and after the element.

Two common block elements are:
``` <p> and <div> ```

### Inline Elements

An inline element does not start on a new line. An inline element only takes up as much width as necessary
For example a ```<span>, <em> or <strong>``` element inside a paragraph.

### HTML Entitys

These entities are used to represent special characters or symbols that have special meanings in HTML, ensuring they are displayed correctly in the browser.

```
&amp; - Represents the ampersand character '&'.
&lt; - Represents the less-than symbol '<'.
&gt; - Represents the greater-than symbol '>'.
&quot; - Represents the double quotation mark '"'.
&apos; - Represents the apostrophe character ''', though not widely supported in HTML.
&nbsp; - Represents a non-breaking space.
&copy; - Represents the copyright symbol '©'.
&reg; - Represents the registered trademark symbol '®'.
&trade; - Represents the trademark symbol '™'.
&euro; - Represents the euro currency symbol '€'.
```