SYST10049 Web Development
: Session 2


## Overview
> 1. HTML: Elements, Attributes, and Content
> 2. Minimal HTML5 Document
> 3. Common content organization
> 4. Dealing with Files

## 1. HTML: Elements, Attributes, and Content

[Element](https://www.w3.org/TR/html52/dom.html#element-definitions)
: Each element has a definition that includes the following information: categories, contexts in which this element can be used, content model, &hellip; content attributes, &hellip; DOM interface, &hellip; 

[Global attributes](https://www.w3.org/TR/html52/dom.html#global-attributes)
: are common to and may be specified on all HTML elements:  `accesskey, class, contenteditable, dir, draggable, hidden, id, lang, spellcheck, style, tabindex, title, translate`

[Content models](https://www.w3.org/TR/html52/dom.html#content-models)
: Each element defined in this specification has a content model: a description of the element’s expected contents. An HTML element must have contents that match the requirements described in the element’s content model. The contents of an element are its children in the DOM.


### HTML Basic Syntax
![http://bajcar.dev.fast.sheridanc.on.ca/project_assets/htmlSyntax_diagram.png](http://bajcar.dev.fast.sheridanc.on.ca/project_assets/htmlSyntax_diagram.png)

### HTML Components
* HTML elements (objects)
* [Global attributes](https://www.w3schools.com/tags/ref_standardattributes.asp) and element-specific attributes (properties)
* [HTML doctypes](https://www.w3schools.com/tags/ref_html_dtd.asp)
* [HTML character sets](https://www.w3schools.com/tags/ref_charactersets.asp)
* [HTML language codes](https://www.w3schools.com/tags/ref_language_codes.asp)
* [HTTP messages](https://www.w3schools.com/tags/ref_httpmessages.asp)

### Character encoding (Character sets)
![http://bajcar.dev.fast.sheridanc.on.ca/project_assets/html04.png](http://bajcar.dev.fast.sheridanc.on.ca/project_assets/html04.png)
* [https://www.w3schools.com/tags/ref_charactersets.asp](https://www.w3schools.com/tags/ref_charactersets.asp)
* [https://www.wikiwand.com/en/MIME](https://www.wikiwand.com/en/MIME)
* [https://www.wikiwand.com/en/Character_encoding](https://www.wikiwand.com/en/Character_encoding)

## 2. Minimal HTML5 Document
~~~html
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>meaningful</title>
    <meta charset="utf-8">
  </head>
  <body>
  </body>
</html>
~~~
## 3. Common content organization
#### example 1
~~~html
<body>
  <header><h1>page heading</h1></header>
  <nav>main navigation</nav>
  <main>content unique to the page</main>
  <aside>relevant info or sidebar</aside>
  <footer><address>contact info</address></footer>
</body>
~~~
#### example 2
![http://bajcar.dev.fast.sheridanc.on.ca/project_assets/semElements.gif](http://bajcar.dev.fast.sheridanc.on.ca/project_assets/semElements.gif)

#### Kinds of content (content categories)
[Explore specifications on W3C](https://www.w3.org/TR/html52/dom.html#kinds-of-content)
![http://bajcar.dev.fast.sheridanc.on.ca/project_assets/html06.png](http://bajcar.dev.fast.sheridanc.on.ca/project_assets/html06.png)

## 4. Dealing with Files
> Where should your website live on your computer?  
> An aside on casing and spacing  
> What structure should your website have?  
> File paths

![http://bajcar.dev.fast.sheridanc.on.ca/project_assets/pathnames.jpg](http://bajcar.dev.fast.sheridanc.on.ca/project_assets/pathnames.jpg)


![http://bajcar.dev.fast.sheridanc.on.ca/project_assets/file_naming.png](http://bajcar.dev.fast.sheridanc.on.ca/project_assets/file_naming.png)

---
> SYST10049 Web Development @ Sheridan College
