# Introduction to Javascript
This repo is for mastering the javascript. All lessons learned from many sources. All 
## 1. Introduction

JavaScript (JS) is a lightweight, interpreted, or just-in-time compiled programming language with first-class functions. While it is most well-known as the scripting language for Web pages, many non-browser environments also use it, such as [Node.js](https://developer.mozilla.org/en-US/docs/Glossary/Node.js), [Apache CouchDB](https://couchdb.apache.org/) and [Adobe Acrobat](http://www.adobe.com/devnet/acrobat/javascript.html). JavaScript is a [prototype-based](https://developer.mozilla.org/en-US/docs/Glossary/Prototype-based_programming), multi-paradigm, single-threaded, dynamic language, supporting object-oriented, imperative, and declarative (e.g. functional programming) styles. 

The standard for JavaScript is ECMAScript. As of 2012, all modern browsers fully support ECMAScript 5.1. Older browsers support at least ECMAScript 3. On June 17, 2015, [ECMA International](https://www.ecma-international.org/) published the sixth major version of ECMAScript, which is officially called ECMAScript 2015, and was initially referred to as ECMAScript 6 or ES6. Since then, ECMAScript standards are on yearly release cycles. This documentation refers to the latest draft version, which is currently [ECMAScript 2020](https://tc39.github.io/ecma262/).

Do not confuse JavaScript with the Java programming language. Both "Java" and "JavaScript" are trademarks or registered trademarks of Oracle in the U.S. and other countries. However, the two programming languages have very different syntax, semantic, and use.

## 2. IDEs for Javascript
Top 3 free IDEs for Javascript.
1. [Visual Studio Code](https://code.visualstudio.com/)
2. [Sublime Text](https://www.sublimetext.com/)
3. [Visual Studio Community Edition](https://visualstudio.microsoft.com/vs/community/)

## 3. Adding Javascript to a webpage
A website has mainly three components. HTML, CSS and JS. We can add JS to an html page in below mentioned ways:

### 3.1 Inside the page

In this method, we write the JS inside the ```<script></script>``` tag.


**File: index.html**
```
<html>
    <head>
        <script>
            // JS here.
        </script>
    </head>
    <body>
    </body>
</html>
```

### 3.2 On a seperate file
In this approach, we write JS in a seperate file. The file has a .js extension. It is linked using the ```<script></script>``` tag. We use the src attribute of ```<script>``` tag to specify the link to the JS file.

**File: header.js**
```
// JS written here
```

**File: index.html**
```
<html>
    <head>
        <script src="header.js">
            // JS here.
        </script>
    </head>
    <body>
        <script src="header.js">
            // JS here.
        </script>
    </body>
</html>
```

**Note: We can add any number of JS files both at top or bottom of the page.**

## References
1. [Mozilla Javascript](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
2. [Javascript Where to](https://www.w3schools.com/js/js_whereto.asp)
