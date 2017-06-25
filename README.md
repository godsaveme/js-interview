# Front-end Job Interview Questions

This file contains a number of front-end interview questions that can be used when vetting potential candidates. It is by no means recommended to use every single question here on the same candidate (that would take hours). Choosing a few items from this list should help you vet the intended skills you require.

**Note:** Keep in mind that many of these questions are open-ended and could lead to interesting discussions that tell you more about the person's capabilities than a straight answer would.

## Table of Contents

  1. [General Questions](#general-questions)
  1. [HTML Questions](#html-questions)
  1. [CSS Questions](#css-questions)
  1. [JS Questions](#js-questions)
  1. [Testing Questions](#testing-questions)
  1. [Performance Questions](#performance-questions)
  1. [Network Questions](#network-questions)
  1. [Coding Questions](#coding-questions)
  1. [Fun Questions](#fun-questions)

## Getting Involved

  1. [Contributors](#contributors)
  1. [How to Contribute](https://github.com/h5bp/Front-end-Developer-Interview-Questions/blob/master/CONTRIBUTING.md)
  1. [License](https://github.com/h5bp/Front-end-Developer-Interview-Questions/blob/master/LICENSE.md)

#### General Questions:

* What did you learn yesterday/this week?
```
ES6 and arrow functions. Interesting things about 'this' context.
```

* What excites or interests you about coding?
```
Makes me think better and I like the satisfaction after resolving a bug
```

* What is a recent technical challenge you experienced and how did you solve it?
```
About how to jump to a new javascript framework and do task with estimated time, I've resolved with a 
meeting with my co-workers, investigation at home, taking advices from colleagues and subscribe to people 
developing the same technology.
```

* What UI, Security, Performance, SEO, Maintainability or Technology considerations do you make while building a web application or site?
```
Behance, responsive chrome addons for UI, OWASP for security, check google dev tools for performances or 
makewebfaster
```

* Talk about your preferred development environment.
```
From phisically space to software environment, I like a pillow for my back, confortable chair, bluetooth 
headphones, english keyboard, a mac with display or any external monitor, a window to see the exterior, 
natural light, a book to take notes, moving to software... I like to use Visual Studio Code, Chrome and 
iTerm. I think that completes the circle.
```

* Which version control systems are you familiar with?
```
npm
```

* Can you describe your workflow when you create a web page?
```
I started with a meeting with the client, listen their necessities and check what is his target, after 
that I like to prepare some mockups on illustrator, showing boxes, titles, image spaces and the 
complete flow of the web page, once the client accept it I start with the design, checking references, 
asking the client for the manual logo if there is any or taking notes about his favorites colors. Then
I have another meeting with him to approved the design. Given these points, for me, the main objective
in this first implementation is to check over the internet wich kind of technology can fit better on 
the project (If i do not have so much time, I should reduce the technology options for the only ones
that I know better) Once I have the technology, first, I started with the arquitecture and the name
conventions, folder structure, git repository, constants classes, helpers, basic navigation, 
responsive options by the same token process of build automation, test environment and cross browsing.
second, building main modules, components, and flows coupled with css styles and unit test, third,
making some main e2e test, cross browsing, testing on mobile devices and check is some code needs 
refactor. In one word, there are some much steps :) 
```

* If you have 5 different stylesheets, how would you best integrate them into the site?
```
I would like to review first the content in each stylesheet, in the final analysis I can determine the 
structure or make some modifications, but I think If you have 5 differents files the most common reason 
is to separate base variables, layouts, modules, components and some reset file, So I will put the base 
variables, reset file and layout on the core or commons of the application and modules and componente 
stylesheet in each folder that belongs.
```

* Can you describe the difference between progressive enhancement and graceful degradation?
```
prograssive enhancements is the way that you code your website thinking about old browers and graceful 
degradation is the way that you code your website putting your all magic on there forgeeting about if 
its gonna looks good on IE8 or older version of any browser. In progressive enhancement you can add 
layer of implementations like other CSS in order to see you web working with all the fancy stuffs and 
in graceful degration you can add modernzr or pollyfils too to see your webpage working on older 
browsers.
```

* How would you optimize a website's assets/resources?
```
minify js, css and html, using an sprite to images, using svg instead of png, getting some resources 
from some public cdn, adding cachebust or similar, putting all this resources in another server.
```

* How many resources will a browser download from a given domain at a time?
  * What are the exceptions?

* Name 3 ways to decrease page load (perceived or actual load time).
```
1. Load on demand 
2. Adding cache to the server configuration
3. Enable compression
```

* If you jumped on a project and they used tabs and you used spaces, what would you do?
```
I will say to myself, I was wrong all the time, Nop, I mean I understand the question, I will first
start with a litle talk with one or two colleagues on the team to understand the reason, just listen 
and give one or two advices only if its necessary.
```

* What is Flash of Unstyled Content? How do you avoid FOUC?
```
If the proccess that the browser use to load your page with the default styles before jump to to your 
styles. You can avoid this minizing your stylesheets or applying load on demand.
```

* Explain what ARIA and screenreaders are, and how to make a website accessible.
```
I dont have so much information about this but what i know is ARIA and screenreaders are helpers to 
blind users and the implementation of this makes the website accessible for more people.
```

* Explain some of the pros and cons for CSS animations versus JavaScript animations.
```
CSS animations use your video card and Javascript animations use the CPU memory.
```

* What does CORS stand for and what issue does it address?
```
CORS is a security protocol that allows you to do request from one domain to another. By default, 
browsers dont allow this communications and you need to enabled. You can specify request types 
like get, post, put and where it request came from adding the domain to your backend.

```

#### HTML Questions:

* What does a `doctype` do?
```
Indicates the type of HTML that is gonna used.
Example of html4
<!DOCTYPE HTML PUBLIC "-//W3C//DTD HTML 4.01//EN" "http://www.w3.org/TR/html4/strict.dtd">
```

* What's the difference between full standards mode, almost standards mode and quirks mode?
```
PENDING
```

* What's the difference between HTML and XHTML?
```
HTML is based on SGML and XHTML is based on XML, the differents are in the way that you
write the tags or attributes depending of the rules for each kind.
```

* Are there any problems with serving pages as `application/xhtml+xml`?
```
PENDING
```

* How do you serve a page with content in multiple languages?
```
Using the lang attribute on each div or as the main html tag to wrapp all the content inside.
```

* What kind of things must you be wary of when design or developing for multilingual sites?
```
PENDING
```

* What are `data-` attributes good for?
```
For cconvention meaning because other coders will know that it is custom attribute
```

* Consider HTML5 as an open web platform. What are the building blocks of HTML5?
```
video and audio, new data storage with more features to store objects, load elements on demand.
```

* Describe the difference between a `cookie`, `sessionStorage` and `localStorage`.
```
cookie
------
- 4kb
- HTML4
- It is accesible for any window
- Storage location: Browser and server
- Send to the server on the request

sessionStorage
--------------
- 5mb
- HTML5
- It is accesible just for the same tab
- Storage location: Browser
- It can not be send it

localStorage
------------
- 10mb
- HTML5
- It is accesible for any window
- Storage location: Browser
- It can not be send it
```

* Describe the difference between `<script>`, `<script async>` and `<script defer>`.
* Why is it generally a good idea to position CSS `<link>`s between `<head></head>` and JS `<script>`s just before `</body>`? Do you know any exceptions?
```
Because the browser reads from the top to the bottom and renders in that direction,
maybe some javascripts needs the complete DOM tag to work with the them.
```

* What is progressive rendering?
```
Its a way to find better ways to rendering things on demand, like lazy loading images
```

* Have you used different HTML templating languages before?
```
PENDING
```


#### CSS Questions:

* What is the difference between classes and IDs in CSS?
* What's the difference between "resetting" and "normalizing" CSS? Which would you choose, and why?
* Describe Floats and how they work.
* Describe z-index and how stacking context is formed.
* Describe BFC(Block Formatting Context) and how it works.
* What are the various clearing techniques and which is appropriate for what context?
* Explain CSS sprites, and how you would implement them on a page or site.
* What are your favourite image replacement techniques and which do you use when?
* How would you approach fixing browser-specific styling issues?
* How do you serve your pages for feature-constrained browsers?
  * What techniques/processes do you use?
* What are the different ways to visually hide content (and make it available only for screen readers)?
* Have you ever used a grid system, and if so, what do you prefer?
* Have you used or implemented media queries or mobile specific layouts/CSS?
* Are you familiar with styling SVG?
* How do you optimize your webpages for print?
* What are some of the "gotchas" for writing efficient CSS?
* What are the advantages/disadvantages of using CSS preprocessors?
  * Describe what you like and dislike about the CSS preprocessors you have used.
* How would you implement a web design comp that uses non-standard fonts?
* Explain how a browser determines what elements match a CSS selector.
* Describe pseudo-elements and discuss what they are used for.
* Explain your understanding of the box model and how you would tell the browser in CSS to render your layout in different box models.
* What does ```* { box-sizing: border-box; }``` do? What are its advantages?
* List as many values for the display property that you can remember.
* What's the difference between inline and inline-block?
* What's the difference between a relative, fixed, absolute and statically positioned element?
* The 'C' in CSS stands for Cascading.  How is priority determined in assigning styles (a few examples)?  How can you use this system to your advantage?
* What existing CSS frameworks have you used locally, or in production? How would you change/improve them?
* Have you played around with the new CSS Flexbox or Grid specs?
* How is responsive design different from adaptive design?
* Have you ever worked with retina graphics? If so, when and what techniques did you use?
* Is there any reason you'd want to use `translate()` instead of *absolute positioning*, or vice-versa? And why?

#### JS Questions:

* Explain event delegation
* Explain how `this` works in JavaScript
* Explain how prototypal inheritance works
* What do you think of AMD vs CommonJS?
* Explain why the following doesn't work as an IIFE: `function foo(){ }();`.
  * What needs to be changed to properly make it an IIFE?
* What's the difference between a variable that is: `null`, `undefined` or undeclared?
  * How would you go about checking for any of these states?
* What is a closure, and how/why would you use one?
* What's a typical use case for anonymous functions?
* How do you organize your code? (module pattern, classical inheritance?)
* What's the difference between host objects and native objects?
* Difference between: `function Person(){}`, `var person = Person()`, and `var person = new Person()`?
* What's the difference between `.call` and `.apply`?
* Explain `Function.prototype.bind`.
* When would you use `document.write()`?
* What's the difference between feature detection, feature inference, and using the UA string?
* Explain Ajax in as much detail as possible.
* What are the advantages and disadvantages of using Ajax?
* Explain how JSONP works (and how it's not really Ajax).
* Have you ever used JavaScript templating?
  * If so, what libraries have you used?
* Explain "hoisting".
* Describe event bubbling.
* What's the difference between an "attribute" and a "property"?
* Why is extending built-in JavaScript objects not a good idea?
* Difference between document load event and document DOMContentLoaded event?
* What is the difference between `==` and `===`?
* Explain the same-origin policy with regards to JavaScript.
* Make this work:
```javascript
duplicate([1,2,3,4,5]); // [1,2,3,4,5,1,2,3,4,5]
```
* Why is it called a Ternary expression, what does the word "Ternary" indicate?
* What is `"use strict";`? what are the advantages and disadvantages to using it?
* Create a for loop that iterates up to `100` while outputting **"fizz"** at multiples of `3`, **"buzz"** at multiples of `5` and **"fizzbuzz"** at multiples of `3` and `5`
* Why is it, in general, a good idea to leave the global scope of a website as-is and never touch it?
* Why would you use something like the `load` event? Does this event have disadvantages? Do you know any alternatives, and why would you use those?
* Explain what a single page app is and how to make one SEO-friendly.
* What is the extent of your experience with Promises and/or their polyfills?
* What are the pros and cons of using Promises instead of callbacks?
* What are some of the advantages/disadvantages of writing JavaScript code in a language that compiles to JavaScript?
* What tools and techniques do you use debugging JavaScript code?
* What language constructions do you use for iterating over object properties and array items?
* Explain the difference between mutable and immutable objects.
  * What is an example of an immutable object in JavaScript?
  * What are the pros and cons of immutability?
  * How can you achieve immutability in your own code?
* Explain the difference between synchronous and asynchronous functions.
* What is event loop?
  * What is the difference between call stack and task queue?
* Explain the differences on the usage of `foo` between `function foo() {}` and `var foo = function() {}`

#### Testing Questions:

* What are some advantages/disadvantages to testing your code?
```
Advantages
----------
- Implementing good practices on the team and on the software development
- Decrease Bugs on the code
- Make trust code on each integration phase
- Increase the time on developing phase

Disadvantages
-------------
- It takes more time to estimate a task even if you update some code
```

* What tools would you use to test your code's functionality?
```
Karma, Jasmine and Protractor
```

* What is the difference between a unit test and a functional/integration test?
```
Unit test ensures that your application has everything to start up correctly and
functional/integration test ensures that the flows in your applications has a 
correct behavior.
```

* What is the purpose of a code style linting tool?
```
- That all the programmers in the team are aligned to a standard way to write code.
- Good practices.
```

#### Performance Questions:

* What tools would you use to find a performance bug in your code?
* What are some ways you may improve your website's scrolling performance?
* Explain the difference between layout, painting and compositing.

#### Network Questions:

* Traditionally, why has it been better to serve site assets from multiple domains?
* Do your best to describe the process from the time you type in a website's URL to it finishing loading on your screen.
* What are the differences between Long-Polling, Websockets and Server-Sent Events?
* Explain the following request and response headers:
  * Diff. between Expires, Date, Age and If-Modified-...
  * Do Not Track
  * Cache-Control
  * Transfer-Encoding
  * ETag
  * X-Frame-Options
* What are HTTP methods? List all HTTP methods that you know, and explain them.

#### Coding Questions:

*Question: What is the value of `foo`?*
```javascript
var foo = 10 + '20';
```

*Question: How would you make this work?*
```javascript
add(2, 5); // 7
add(2)(5); // 7
```

*Question: What value is returned from the following statement?*
```javascript
"i'm a lasagna hog".split("").reverse().join("");
```

*Question: What is the value of `window.foo`?*
```javascript
( window.foo || ( window.foo = "bar" ) );
```

*Question: What is the outcome of the two alerts below?*
```javascript
var foo = "Hello";
(function() {
  var bar = " World";
  alert(foo + bar);
})();
alert(foo + bar);
```

*Question: What is the value of `foo.length`?*
```javascript
var foo = [];
foo.push(1);
foo.push(2);
```

*Question: What is the value of `foo.x`?*
```javascript
var foo = {n: 1};
var bar = foo;
foo.x = foo = {n: 2};
```

*Question: What does the following code print?*
```javascript
console.log('one');
setTimeout(function() {
  console.log('two');
}, 0);
console.log('three');
```

#### Fun Questions:

* What's a cool project that you've recently worked on?
* What are some things you like about the developer tools you use?
* Who inspires you in the front-end community?
* Do you have any pet projects? What kind?
* What's your favorite feature of Internet Explorer?
* How do you like your coffee?


#### Contributors:

This document started in 2009 as a collaboration of [@paul_irish](https://twitter.com/paul_irish) [@bentruyman](https://twitter.com/bentruyman) [@cowboy](https://twitter.com/cowboy) [@ajpiano](https://twitter.com/ajpiano)  [@SlexAxton](https://twitter.com/slexaxton) [@boazsender](https://twitter.com/boazsender) [@miketaylr](https://twitter.com/miketaylr) [@vladikoff](https://twitter.com/vladikoff) [@gf3](https://twitter.com/gf3) [@jon_neal](https://twitter.com/jon_neal) [@sambreed](https://twitter.com/sambreed) and [@iansym](https://twitter.com/iansym).

It has since received contributions from over [100 developers](https://github.com/h5bp/Front-end-Developer-Interview-Questions/graphs/contributors).
