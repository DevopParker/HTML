# HTML: HyperText Markup Language

HTML (HyperText Markup Language) is the most basic building block of the Web. It defines the meaning and structure of web content. Other technologies besides HTML are generally used to describe a web page's appearance/presentation (CSS) or functionality/behavior (JavaScript).

HTML uses "markup" to annotate text, images, and other content for display in a Web browser. HTML markup includes special "elements"

[HTML Docs](https://developer.mozilla.org/en-US/docs/Web/HTML)

The W3C Markup Validation Service is an online tool provided by the World Wide Web Consortium (W3C), which is a standards organization for the World Wide Web. The purpose of the website is to validate the markup validity of web documents. In simpler terms, it allows you to check whether the HTML or XHTML code of a web page conforms to the defined standards and rules set by the W3C.

[W3C Markup Validation Server](https://validator.w3.org/)

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

With elements such as `<html>` you can add _Attributes_ which lie inside of the element.
- For example `<html lang="en-US">`
- This html element now has the attribute lang that provides the language "en-US" as the websites standard.

The standard for most web pages requires element such as:
```
<!DOCTYPE html>
<meta charset="UTF-8">
<meta name="author" content="Devop Parker">
<meta name="description" content="This page contains information to learn HTML">
```
- These elements provide details about your webpage, such as the "html" Documentation Type and the meta data that can be used to locate particular details about your website.

### Common Attributes

```<a href="URL or FileLocation">```

- The href attribute specifies the URL of the page the link goes to.
- You can use href="#top" or href="#" to link to the top of the current page.
- Adding the download tag inside of an anchor tag allows the user to download the contents of that href inside of the anchor tag.
- Another useful tag for the anchor element is ```target="_blank"``` this allows you to open the href into a new browser tab.

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

### Lists

```
<ol> - Ordered Lists
<ul> - Unordered Lists
<li> - List items
<dl> - Description List
<dt> - Description Term
<dd> - Description Details
```
For lists you can start it with the ol, ul, or dl elements. Inside that block you will add items such as li to start the items in that list. ```<dl>``` sits flush with the left side of the page, unlike ```<ol>``` and can use terms and details to create a more detailed type of list.

### Images

The ```<img>``` element is used to implement images onto a webpage. The img element has multiple attributes that are essential to create a healthy image on the page. The most import attribute would be the src="" attribute. This allows the element to find the source of the image in the websites file system. Most common practice would be to create an img folder to have all of your images in one place, and easily accessible.

Example:
```<img src="img/html_logo.png" alt="HTML5 Logo" title="HTML5" width="300" height="300">```

- The alt attribute is used for screen readers and when the image fails to load, it will be replaced by the text inside.
- The title attribute is the text displayed when hovering over the image.
- The width and height attributes (in pixels) will crop the image to the size given, this doesn't always crop nicely, it should mostly be used with the identical size of the original image.

There is also a attribute type ```loading=""```.
By default, this is set to "eager" which loads all images on the page immediately.
The term "lazy" refers to a useful value that delays the loading of images until certain criteria are met, such as when they are beyond the current page's scope and will be loaded in only when the user scrolls down. This allows better perfomance on the webpage if you have many pictures that don't instantly load into the page when the user opens it.

An element that goes well with images, is the ```<figure>``` element. This allows you to create captions with the item or object inside of the figure's codeblock. Inside of the figure element, you can use ```<figcaption>``` to create a caption right below or above the item.

### Image Sources
- [Loremipsum](https://loremipsum.io/) - This has tons of placeholders to help when designing a website, including image placeholders
- [Unspalsh](https://unsplash.com/) - This site contains free images that are allowed to be used on your website.
- [Pexels](https://www.pexels.com/) - Same as Unsplash
- [IrfanView](https://www.irfanview.com/) - An application with tons of image editing features to resize, crop and many more.

### HTML5 Hierarchy

Semantic HTML refers to the use of HTML tags that convey the meaning or semantics of the content contained within them.
By adding semantic HTML tags to your pages, you provide additional information that helps define the roles and relative importance of the different parts of your page. Semantic 

HTML includes:

```
- <header>
- <nav>
- <main>
- <article>
- <figure>
- <p>
- <section>
- <aside>
- <footer>
```

![image](img/Semantics.png)

These elements are all very useful in defining the Heirarchy of the HTML5 page.
While some elements are still commonly used in the practice such as ```<div> and <span>``` they provide very little semantics to the site.

### References to useful information about HTML:
- [HTML: HyperText Markup Language](https://developer.mozilla.org/en-US/docs/Web/HTML)
- [HTML elements reference](https://developer.mozilla.org/en-US/docs/Web/HTML/Element)
- [Named character references](https://html.spec.whatwg.org/multipage/named-characters.html#named-character-references)
- [Semantics in HTML](https://developer.mozilla.org/en-US/docs/Glossary/Semantics)
- [HTML Semantic Elements](https://www.w3schools.com/html/html5_semantic_elements.asp)
- [Document and website structure](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/Document_and_website_structure)
- [HTML table basics](https://developer.mozilla.org/en-US/docs/Learn/HTML/Tables/Basics)
- [HTML table advanced features and accessibility](https://developer.mozilla.org/en-US/docs/Learn/HTML/Tables/Advanced)
- [Web forms — Working with user data](https://developer.mozilla.org/en-US/docs/Learn/Forms)
- [The Form element](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/form)