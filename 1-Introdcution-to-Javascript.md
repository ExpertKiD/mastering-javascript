# Introduction to Javascript
This repo is for mastering the javascript. All lessons learned from many sources. All 
## 1. Introduction

JavaScript (JS) is a lightweight, interpreted, or just-in-time compiled programming language with first-class functions. While it is most well-known as the scripting language for Web pages, many non-browser environments also use it, such as [Node.js](https://developer.mozilla.org/en-US/docs/Glossary/Node.js), [Apache CouchDB](https://couchdb.apache.org/) and [Adobe Acrobat](http://www.adobe.com/devnet/acrobat/javascript.html). JavaScript is a [prototype-based](https://developer.mozilla.org/en-US/docs/Glossary/Prototype-based_programming), multi-paradigm, single-threaded, dynamic language, supporting object-oriented, imperative, and declarative (e.g. functional programming) styles. 

The standard for JavaScript is ECMAScript. As of 2012, all modern browsers fully support ECMAScript 5.1. Older browsers support at least ECMAScript 3. On June 17, 2015, [ECMA International](https://www.ecma-international.org/) published the sixth major version of ECMAScript, which is officially called ECMAScript 2015, and was initially referred to as ECMAScript 6 or ES6. Since then, ECMAScript standards are on yearly release cycles. This documentation refers to the latest draft version, which is currently [ECMAScript 2020](https://tc39.github.io/ecma262/).

Do not confuse JavaScript with the Java programming language. Both "Java" and "JavaScript" are trademarks or registered trademarks of Oracle in the U.S. and other countries. However, the two programming languages have very different syntax, 
semantic, and use.

## 2. IDEs for Javascript
Top 3 free IDEs for Javascript.
1. [Visual Studio Code](https://code.visualstudio.com/)
2. [Sublime Text](https://www.sublimetext.com/)
3. [Visual Studio Community Edition](https://visualstudio.microsoft.com/vs/community/)

## 3. Adding Javascript to a webpage
A website has mainly three components. HTML, CSS and JS. We can add JS to an html page in below mentioned ways:

### 3.1. Inside the page

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

### 3.2. On a seperate file
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

## 4. Comments in JS
You can write comment in below mentioned ways:

### 4.1. Single line comments
You can write single line comments using //.
```
// this is a comment
```

### 4.2. Multi-line comments
You can write single line comments using /* comments */.
```
/*
This way we can
comment
multiple line
using a single format.
*/
```

## 5. Variables and Constants

Variables and constants are containers for storing values in JS. The value of a variable can change over time, but constants will stay the same forever.

### 5.1. Declaring variables and constants
We can declare a variable in JS using the ```var``` or the ```let``` keyword and for constant, we use the ```const``` keyword.

```
var price;
var unitOfWork = 30;

let age = 35;
const PI = 3.14;
```

**NOTE: USE let TO DECLARE VARIABLES AS var CAN GIVE FUNKY BEHAVIOURS FOR BEGINNERS.**

### 5.2. Naming conventions for variables and constants
All JavaScript variables must be identified with unique names. These unique names are called identifiers. Identifiers can be short names (like x and y) or more descriptive names (age, sum, totalVolume).

The general rules for constructing names for variables (unique identifiers) are:

* Names can contain letters, digits, underscores, and dollar signs.
* Names must begin with a letter
* Names can also begin with $ and _
* Names are case sensitive (y and Y are different variables)
* Reserved words (like JavaScript keywords) cannot be used as names

**Note: JS identifiers are case sensitive.**

### 5.3. Types in JS
JavaScript variables can hold many data types: numbers, strings, objects and more. In JS, we have the following types:
1. String
2. Number
3. Boolean
4. null and undefined
5. Object
6. Symbol

#### 5.3.1. String
A JavaScript string is zero or more characters written inside quotes. You can use single or double quotes.
```
var name = 'Suman'
let message = "Hello world!";
```

For more: 
* [JS Strings](https://www.w3schools.com/js/js_strings.asp)
* [JS String methods](https://www.w3schools.com/js/js_string_methods.asp)

#### 5.3.2. Number
JavaScript has only one type of number. Numbers can be written with or without decimals.
```
var x = 3.14;    // A number with decimals
var y = 3;       // A number without decimals
```
Extra large or extra small numbers can be written with scientific (exponent) notation:
```
var x = 123e5;    // 12300000
var y = 123e-5;   // 0.00123
```

**Note: JavaScript Numbers are Always 64-bit Floating Point. Unlike many other programming languages, JavaScript does not define different types of numbers, like integers, short, long, floating-point etc. JavaScript numbers are always stored as double precision floating point numbers, following the international IEEE 754 standard. This format stores numbers in 64 bits, where the number (the fraction) is stored in bits 0 to 51, the exponent in bits 52 to 62, and the sign in bit 63.**

For more: 
* [JS numbers](https://www.w3schools.com/js/js_numbers.asp)
* [JS Number Methods](https://www.w3schools.com/js/js_number_methods.asp)

#### 5.3.3. Boolean
A JavaScript Boolean represents one of two values: true or false.

```
let userExists = false;
let weWon = (score > 1000);
```
For more: [JS Booleans](https://www.w3schools.com/js/js_booleans.asp)

#### 5.3.4. null and undefined
A variable has two step process of definition: First it is declared, then the value is initialized. If a variable is declared only and not initialized, then it is undefined. But if the variable is declared and initialized, but has no value, then it is null.

```
typeof null // Object
typeof undefined // undefined
```

For More:
* [JS Comparision Table](https://dorey.github.io/JavaScript-Equality-Table/)
* [JS - Double Euqals vs Triple Equals](https://codeburst.io/javascript-double-equals-vs-triple-equals-61d4ce5a121a)

#### 5.3.5. Object

#### 5.3.6. Symbol

## References
1. [Mozilla Javascript](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
2. [Javascript Where to](https://www.w3schools.com/js/js_whereto.asp)
3. [Javascript Variables](https://www.w3schools.com/js/js_variables.asp)

