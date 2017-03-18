# seminar-js-intro

## [A Pretty Brief History of JavaScript](https://auth0.com/blog/a-brief-history-of-javascript/)
- Netscape, Brendan Eich 
- In 1995
- Mocha -> LiveScript -> JavaScript
- JScript developed by Microsoft in 1996
- ECMAScript, ECMA-262, TC39, 1st in 1997
- 3rd in 1999, widely spread version.

## Objectives
- To become the web more dynamic
- Small scripting language to interact with the DOM
  - ex) VBA for MS Excel
- For designers, non-developers 

## Features
- Java-like Syntax
- Functions as First-Class Objects 
- Prototype-based Object Model
- Multi paradigm Language
- Host environment needed
  - Browser: window, NodeJs: global
- Single Thread
  - Asynchronous programming, callback
- Easy to learn but hard to master

## JavaScript != Java
- Sun wants Netscape to develop Java for Web.
- No time, developed for just 2 weeks
- Java-like Syntax
- **But** Scheme and Self => **A move of God**
- Sun and Netscape deal, JavaScript

## [Browser Wars](https://en.wikipedia.org/wiki/Browser_wars)
- 1st war: Netscape Navigator VS IE(1996-2001)
- Great revolution but many inconsistences, HTML and CSS
- 2nd war: IE vs Safari vs Firefox vs Chrome(2004-present)
- HTML5, CSS3, ECMAScript6
- JavaScript Engine Race: SpiderMonkey, V8, Nitro, Chakra 

```javascript
// IE
var xhr = new ActiveXObject("Microsoft.XMLHTTP");
// Other browsers
var xhr = new XMLHttpRequest();
```

## Renaissance: Ajax
- Asynchronous JavaScript and XML
- XMLHttpRequest introduced by Microsoft in IE5
- Perform an asynchronous HTTP request against a server
- Allow pages to be updated on-the-fly
- Google suggestions, Gmail, Google Maps 
- JavaScript library Race
  - prototype.js, jQuery, YUI, ExtJs, Dojo, Mootools etc.
  - **Winner is jQuery**

## Present
- HTML5, CSS3
- V8, NodeJS, NPM
- Single Page Application(SPA), MEAN Stack
- Backbone, Angular, React, Polymer
- RESTful API based on JSON
- Data Visualization D3.js
- AMP + Progressive Web App
- RxJS, Asynchrous Programming
- Redux Architecture(Unidirectional Data Flow)
- [JavaScript Fatigue](https://hackernoon.com/how-it-feels-to-learn-javascript-in-2016-d3a717dd577f#.xkzyt0nsk)

## ECMAScript 2016
- ECMAScript v4 **abandoned**
- ECMAScript v6, ECMA2015, ECMA2016(v7)
- class, block scope, module system etc.
- Transpiler
  - Babel, Traceur, TypeScript, CoffeeScript
- Module Bundler
  - Webpack, JSPM, Rollup, Browserify
- Shim, Polyfill
  - core-js

## Web Application example
- Simple Contacts App
- Classical example
  - Vanilla JS
  - jQuery 

## The Future of JavaScript
- JavaScript looks like Machine Language for browser.
- Web Assembly([demo](https://s3.amazonaws.com/mozilla-games/ZenGarden/EpicZenGarden.html))
- Web component
