# HTML: HyperText Markup Language

HTML (HyperText Markup Language) is the most basic building block of the Web. It defines the meaning and structure of web content. Other technologies besides HTML are generally used to describe a web page's appearance/presentation (CSS) or functionality/behavior (JavaScript).

HTML uses "markup" to annotate text, images, and other content for display in a Web browser. HTML markup includes special "elements"

[HTML](https://developer.mozilla.org/en-US/docs/Web/HTML)

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

### Common Attributes

```<a href="URL">```

- The href attribute specifies the URL of the page the link goes to.
- You can use href="#top" or href="#" to link to the top of the current page

The ```<link rel="icon" href="html5.png" type="image/x-icon">``` element can be used to add an icon to the title of the webpage, using the href attribute to specify the location of the icon picture.

