#Front-end Job Interview Questions

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
  -
* What excites or interests you about coding?
  -
* What is a recent technical challenge you experienced and how did you solve it?
  -
* What UI, Security, Performance, SEO, Maintainability or Technology considerations do you make while building a web application or site?
  -
* Talk about your preferred development environment.
  -
* Which version control systems are you familiar with?
  -
* Can you describe your workflow when you create a web page?
  -
* If you have 5 different stylesheets, how would you best integrate them into the site?
  -
* Can you describe the difference between progressive enhancement and graceful degradation?
  -
* How would you optimize a website's assets/resources?
  -
* How many resources will a browser download from a given domain at a time?
  -
  * What are the exceptions?
    -
* Name 3 ways to decrease page load (perceived or actual load time).
  -
* If you jumped on a project and they used tabs and you used spaces, what would you do?
  -
* Describe how you would create a simple slideshow page.
  -
* If you could master one technology this year, what would it be?
  -
* Explain the importance of standards and standards bodies.
  -
* What is Flash of Unstyled Content? How do you avoid FOUC?
  -
* Explain what ARIA and screenreaders are, and how to make a website accessible.
  -
* Explain some of the pros and cons for CSS animations versus JavaScript animations.
  -
* What does CORS stand for and what issue does it address?
  - Cross Origin Resourse Sharing - prevents code from one website from accessing credential-restricted content on another site. Ajax requests are by default sent with any auth cookies granted by the target site. By building on top of the XMLHttpRequest object, CORS allows developers to work with the same idioms as same-domain requests.

#### HTML Questions:

* What does a `doctype` do? 
  - instruction to browser about which version of HTML to render with.
* What's the difference between standards mode and quirks mode? 
  - Standards uses full HTML/CSS standards, quirks implements older HTML from Navigator 4 and Internet Explorer 5.
* What's the difference between HTML and XHTML? 
  - XHTML mandates DOCTYPE, html, head, title and body tags, and elements must be properly nested, closed, be in lowercase, and have only one root element. Attribute values must be quoted, and lowercase. HTML is more relaxed in these areas.
* Are there any problems with serving pages as `application/xhtml+xml`? 
  - IE 6 & 7 break, and must therefore serve the correct MIME type to text/html. Otherwise, certain browsers will display xml parse errors if the page contains invalid code. 
* How do you serve a page with content in multiple languages? 
  - The primary language of the page should correspond with the human language of the page. I.e. <html xmlns="http://www.w3.org/1999/xhtml" lang="en" xml:lang="en"> sets the primary language as "english." If you have other languages within the same page, you should specify in the element attributes which language the elements and all child elements are (i.e. <blockquote lang="fr"></blockquote> for french).
* What kinds of things must you be wary of when design or developing for multilingual sites? 
  - DB design patterns change for different languages, because people from different countries need different content. Therefore, it can be better to have completely different sites for different languages.
* What are `data-` attributes good for?
  -
* Consider HTML5 as an open web platform. What are the building blocks of HTML5?
  -
* Describe the difference between a `cookie`, `sessionStorage` and `localStorage`.
  -
* Describe the difference between `<script>`, `<script async>` and      `<script defer>`.
  -
* Why is it generally a good idea to position CSS `<link>`s between `<head></head>` and JS `<script>`s just before `</body>`? Do you know any exceptions?
  -
* What is progressive rendering?
  -
* Have you used different HTML templating languages before?
  -

#### CSS Questions:

* What is the difference between classes and ID's in CSS?
  -
* What's the difference between "resetting" and "normalizing" CSS? Which would you choose, and why?
  -
* Describe Floats and how they work.
  -
* Describe z-index and how stacking context is formed.
  -
* Describe BFC(Block Formatting Context) and how it works.
  -
* What are the various clearing techniques and which is appropriate for what context?
  -
* Explain CSS sprites, and how you would implement them on a page or site.
  -
* What are your favourite image replacement techniques and which do you use when?
  -
* How would you approach fixing browser-specific styling issues?
  -
* How do you serve your pages for feature-constrained browsers?
  -
  * What techniques/processes do you use?
    -
* What are the different ways to visually hide content (and make it available only for screen readers)?
  -
* Have you ever used a grid system, and if so, what do you prefer?
  - Yes; Materialize or Bootstrap
* Have you used or implemented media queries or mobile specific layouts/CSS?
  -
* Are you familiar with styling SVG?
  -
* How do you optimize your webpages for print?
  -
* What are some of the "gotchas" for writing efficient CSS?
  -
* What are the advantages/disadvantages of using CSS preprocessors?
  -
  * Describe what you like and dislike about the CSS preprocessors you have used.
    -
* How would you implement a web design comp that uses non-standard fonts?
  -
* Explain how a browser determines what elements match a CSS selector.
  -
* Describe pseudo-elements and discuss what they are used for.
  - 
* Explain your understanding of the box model and how you would tell the browser in CSS to render your layout in different box models.
  -
* What does ```* { box-sizing: border-box; }``` do? What are its advantages?
  -
* List as many values for the display property that you can remember.
  -
* What's the difference between inline and inline-block?
  -
* What's the difference between a relative, fixed, absolute and statically positioned element?
  -
* The 'C' in CSS stands for Cascading.  How is priority determined in assigning styles (a few examples)?
  -
  * How can you use this system to your advantage?
    -
* What existing CSS frameworks have you used locally, or in production?
  -
  * How would you change/improve them?
    -
* Have you played around with the new CSS Flexbox or Grid specs?
  -
* How is responsive design different from adaptive design?
  -
* Have you ever worked with retina graphics? If so, when and what techniques did you use?
  -
* Is there any reason you'd want to use `translate()` instead of *absolute positioning*, or vice-versa? And why?
  -

#### JS Questions:

* Explain event delegation
  - allows you to avoid adding event listeners to specific nodes;  instead, the event listener is bound to the parent element. That event listener analyzes bubbled events to find a match on child elements.
  `// Get the element, add a click listener...
  document.getElementById("parent-list").addEventListener("click", function(e) {
  	// e.target is the clicked element!
  	// If it was a list item
  	if(e.target && e.target.nodeName == "LI") {
  		// List item found!  Output the ID!
  		console.log("List item ", e.target.id.replace("post-"), " was clicked!");
  	}
  });`
* Explain how `this` works in JavaScript
  - Every line of JavaScript code is run in an “execution context.” The JavaScript runtime environment maintains a stack of these contexts, and the top execution context on this stack is the one that’s actively running.
    
    There are three types of executable code: Global code, function code, and eval code. 
    
    The object that this refers to is redetermined every time control enters a new execution context and remains fixed until control shifts to a different context. The value of this is dependent upon two things: The type of code being executed (i.e., global, function, or eval) and the caller of that code.
* Explain how prototypal inheritance works
  - .prototype is a property of Function() objects. Defining properties of a function.prototype is how you pass inheritance of those properties to objects based off those functions through either Object.create or the "new" function. The prototype's value is the constructor that created the object. Prototypes share their properties with their objects. A prototype is just an object, while a constructor is the pointer to the function that created the object.
* What do you think of AMD vs CommonJS?
  - When we say an application is modular, we generally mean it's composed of a set of highly decoupled, distinct pieces of functionality stored in modules.
   Asynchronous Module Definition - format provides a solution for modular JavaScript where both the module and dependencies can be asynchronoously loaded. 
    - Uses 'define' as a function wrapper.
    - Supports objects, functions, constructors, strings, JSON and many other types of modules, running natively in the browser.
   CommonJS module proposal - specifies a simple API for declaring modules server-side and unlike AMD attempts to cover a broader set of concerns such as io, filesystem, promises and more. At a high-level they basically contain two primary parts: a free variable named exports which contains the objects a module wishes to make available to other modules and a require function that modules can use to import the exports of other modules. 
    - This is more synchronous.
    - Only supports Objects as modules
   The way some developers are approaching choosing which format to use is opting for CJS when a module can be used in a server-side environment and using AMD if this is not the case.
* Explain why the following doesn't work as an IIFE: `function foo(){ }();`
  - Immediately-Invoked Function Expression - When the parser encounters the function keyword in the global scope or inside a function, it treats it as a function declaration (statement), and not as a function expression, by default. If you don’t explicitly tell the parser to expect an expression, it sees what it thinks to be a function declaration without a name and throws a SyntaxError exception because function declarations require a name.
  * What needs to be changed to properly make it an IIFE?
    - The most widely accepted way to tell the parser to expect a function expression is just to wrap it in parentheses, because in JavaScript, parentheses can’t contain statements. At this point, when the parser encounters the function keyword, it knows to parse it as a function expression and not a function declaration.
      - `(function foo(){ })();` or `(function foo(){ }())`
* What's the difference between a variable that is: `null`, `undefined` or undeclared?
  - Undeclared: A variable is undeclared when it does not use the var keyword. It gets created on the global object (that is, the window), thus it operates in a different space as the declared variables. Will not work in strict mode and is not good practice.
  - Undefined: Something is undefined when it hasn’t been defined yet. typeof undefinedVariable; // "undefined"
  - null: variable defined to have a null value. typeof nullVaraible; // "object"
  * How would you go about checking for any of these states?
    - use the typeof userVariable to determine "undefined" or "null". Undeclared will result in a runtime error when used in strict mode.
* What is a closure, and how/why would you use one?
  - Closures are functions that refer to independent (free) variables. In other words, the function defined in the closure 'remembers' the environment in which it was created. A good example is in the underscore _.once and _.memoize. The function will remember the value of an inner variable which will save on processing time for complex functions.
* What's a typical use case for anonymous functions?
  - when you pass the as arguments for other named functions.
  `setTimeout(function() {
    alert('hello'); 
  }, 1000);`
  - popular in frameworks is to create closures with anonymous functions:
  `(function() {
     alert('foo'); 
   })();`
* How do you organize your code? (module pattern, classical inheritance?)
  - 
* What's the difference between host objects and native objects?
  - Native objects are inherent to JS and are available to us as long as we are using JS. But, Host objects are everything the environment gives us. For the browser, this includes objects like window. Host objects can differ by environment (or host), so that Node wouldn’t have access to window (which makes sense since there’s no DOM for Node), but could have its own host objects like NodeLists.
* Difference between: `function Person(){}`, `var person = Person()`, and `var person = new Person()`?
  -
* What's the difference between `.call` and `.apply`?
  - Both take a context as a parameter. They execute a function in the context, or scope, of the first argument that you pass to them.
  - call takes individual arguments
  - apply takes an array as an argument
* Explain `Function.prototype.bind`.
  - bind is used to bind "this" context to a function so that values inside the function can use "this".
   `Function.prototype.myBind = function (context) {
      var self = this;
      return function() {
        context.self
      }
    }`
* When would you use `document.write()`?
  - You should really only use it in an unready open document, meaning before it has loaded. Once it's loaded, the document is "closed" and you shouldn't use document.write() anymore. Any attempt after loading will cause the document contents to be erased and replaced with whatever you pass into document.write().
* What's the difference between feature detection, feature inference, and using the UA string?
  - feature detection - check to see if a browser suports a feature. If not, you write code to cover your bases. Use feature detection if you're working with a feature that isn’t available across all browsers. When the browsers upgrade your code will be able to take advantage of the upgrade and your code will still work. When the browsers upgrade your code will be able to take advantage of the upgrade and your code will still work. 
  - feature interference - When you make an assumption that because one feature is present (or not) another one will also be present (or not).
  - UA - user agent
* Explain AJAX in as much detail as possible.
  - Asynchronous JavaScript and XML
  - Used to send requests (GET, POST) and handle responses from the server without disrupting the current display.
  - requires a URL to send request to.
  - Has "success" and "error" callbacks.
  - Does not allow requesting data from another server.
* Explain how JSONP works (and how it's not really AJAX).
  - JSON with Padding - used when requesting data from another domain.
  - Since AJAX doesn't allow requesting data from another domain, JSONP is a workaround using script tags. You set the script source to be the URL you're hitting and pass in a callback, which handles the data retrieved from the requested domain server.
  - `<script type="text/javascript">
      function  myCallback (data) {};
    </script>
    <script type="text/javascript" src="http://server.com?callback=myCallback"></script>`
* Have you ever used JavaScript templating?
  - yes. I'd love to use Moustache/Handlebars
  * If so, what libraries have you used?
    - Underscore _.template("Hello, <%= name %>", { name: "Jack" }) 
* Explain "hoisting".
  - Hoisting is JavaScript's default behavior of moving declarations to the top. In JavaScript, a variable can be declared after it has been used. In other words; a variable can be used before it has been declared.
* Describe event bubbling.
  - When an event is triggered by a low-level element, the event bubbles up the DOM until it encounters an event handler. Required functionality for event delegation.
* What's the difference between an "attribute" and a "property"?
  - JS DOM objects have properties. These properties are kind of like instance variables for the particular element. As such, a property can be different types (boolean, string, etc.). Properties can be accessed using jQuery’s prop method (as seen below) and also by interacting with the object in vanilla JS. (e.g. href, class, text, style, name, id).
  - Attributes are in the HTML itself, rather than in the DOM. They are very similar to properties, but not quite as good. When a property is available it’s recommended that you work with properties rather than attributes. An attribute is only ever a string, no other type. 
  `<input type="checkbox" checked=true/>
   $('input').prop('checked'); // returns true
   $('input').attr('checked'); // returns "checked"`
   - Also, prop will return current state of a property, whereas attr will return the default value.
* Why is extending built-in JavaScript objects not a good idea?
  - If, in future, a browser decides to implement its own version of your method, your method might get overridden (silently) and the browser’s implementation (which is probably different from yours) would take over. So not extending in the first place is future proofing your code.
  - On the flip side, if you decide to overwrite the browsers definition, any future developer working on your code won’t know about the change. They'll have a harder time getting up to speed.
  - Generally it’s safer to move your particular changes into a library (as with underscore.js). That way your particular methods are clearly marked and there’s no chance of conflict.
* Difference between document load event and document ready event?
  - $(document).ready() fires when the HTML has finished loading. You can’t interact with the DOM before the HTML has finished loading, so we keep all our JS interactions wrapped up in the ready handler.
  - window.onload fires when all of the content (images, scripts, CSS, the whole lot) has finished loading. This can be really slow, so we try not to keep too much here.
* What is the difference between `==` and `===`?
  - == type converts. 1 == "1" //true;
  - === is strict equals; both type and content must be the same.
* Explain the same-origin policy with regards to JavaScript.
  - The same-origin policy helps prevent malicious attacks by stopping code from another site executing on your site. An attacks like this is known as a Cross Site Scripting attack.
  - The “origin” is the same if three things are the same: the protocol (http vs. https), the domain (subdomain.yoursite.com vs. yoursite.com vs. google.com), and the port (:80 vs. :4567). If all three of these line up, then JS views the sites as the same, and code is executed. If any of them are different then the code is marked as potentially malicious and is not run.
* Make this work:
```javascript
duplicate([1,2,3,4,5]); // [1,2,3,4,5,1,2,3,4,5]
```
  -
* Why is it called a Ternary expression, what does the word "Ternary" indicate?
  - Ternary means there are three parts to the expression: (testCondition) ? (executedIfTrue) : (executedIfFalse); 
* What is `"use strict";`? what are the advantages and disadvantages to using it?
  - If you put "use strict"; at the top of your code (or function), then the JS is evaluated in strict mode. Strict mode throws more errors and disables some features in an effort to make your code more robust, readable, and accurate.
* Create a for loop that iterates up to `100` while outputting **"fizz"** at multiples of `3`, **"buzz"** at multiples of `5` and **"fizzbuzz"** at multiples of `3` and `5`
  - 
* Why is it, in general, a good idea to leave the global scope of a website as-is and never touch it?
  -
* Why would you use something like the `load` event? Does this event have disadvantages?
  -
  * Do you know any alternatives, and why would you use those?
    -
* Explain what a single page app is and how to make one SEO-friendly.
  -
* What is the extent of your experience with Promises and/or their polyfills?
  -
* What are the pros and cons of using Promises instead of callbacks?
  -
* What are some of the advantages/disadvantages of writing JavaScript code in a language that compiles to JavaScript?
  -
* What tools and techniques do you use debugging JavaScript code?
  -
* What language constructions do you use for iterating over object properties and array items?
  - Arrays: for/ loop: for (var i = 0; i < collection.length; i++) {}
  - Objects: for-in loop: for (var key in collection) {};
* Explain the difference between mutable and immutable objects.
  -
  * What is an example of an immutable object in JavaScript?
    -
  * What are the pros and cons of immutability?
    -
  * How can you achieve immutability in your own code?
    -
* Explain the difference between synchronous and asynchronous functions.
  -
* What is event loop?
  -
  * What is the difference between call stack and task queue?
    -

#### Testing Questions:

* What are some advantages/disadvantages to testing your code?
  -
* What tools would you use to test your code's functionality?
  -
* What is the difference between a unit test and a functional/integration test?
  -
* What is the purpose of a code style linting tool?
  -

#### Performance Questions:

* What tools would you use to find a performance bug in your code?
  -
* What are some ways you may improve your website's scrolling performance?
  -
* Explain the difference between layout, painting and compositing.
  -

#### Network Questions:

* Traditionally, why has it been better to serve site assets from multiple domains?
  -
* Do your best to describe the process from the time you type in a website's URL to it finishing loading on your screen.
  -
* What are the differences between Long-Polling, Websockets and Server-Sent Events?
  -
* Explain the following request and response headers:
  * Diff. between Expires, Date, Age and If-Modified-...
    -
  * Do Not Track
    -
  * Cache-Control
    -
  * Transfer-Encoding
    -
  * ETag
    -
  * X-Frame-Options
    -
* What are HTTP actions? List all HTTP actions that you know, and explain them.
  -

#### Coding Questions:

*Question: What is the value of `foo`?*
```javascript
var foo = 10 + '20';
```
  -

*Question: How would you make this work?*
```javascript
add(2, 5); // 7
add(2)(5); // 7
```
  -

*Question: What value is returned from the following statement?*
```javascript
"i'm a lasagna hog".split("").reverse().join("");
```
  -

*Question: What is the value of `window.foo`?*
```javascript
( window.foo || ( window.foo = "bar" ) );
```
  -

*Question: What is the outcome of the two alerts below?*
```javascript
var foo = "Hello";
(function() {
  var bar = " World";
  alert(foo + bar);
})();
alert(foo + bar);
```
  -

*Question: What is the value of `foo.length`?*
```javascript
var foo = [];
foo.push(1);
foo.push(2);
```
  -

*Question: What is the value of `foo.x`?*
```javascript
var foo = {n: 1};
var bar = foo;
foo.x = foo = {n: 2};
```
  -

*Question: What does the following code print?*
```javascript
console.log('one');
setTimeout(function() {
  console.log('two');
}, 0);
console.log('three');
```
  -

#### Fun Questions:

* What's a cool project that you've recently worked on?
  -
* What are some things you like about the developer tools you use?
  -
* Do you have any pet projects? What kind?
  -
* What's your favorite feature of Internet Explorer?
  -
* How do you like your coffee?
  - I don't. Tea, no milk or sugar.


#### Contributors:

This document started in 2009 as a collaboration of [@paul_irish](https://twitter.com/paul_irish) [@bentruyman](https://twitter.com/bentruyman) [@cowboy](https://twitter.com/cowboy) [@ajpiano](https://twitter.com/ajpiano)  [@SlexAxton](https://twitter.com/slexaxton) [@boazsender](https://twitter.com/boazsender) [@miketaylr](https://twitter.com/miketaylr) [@vladikoff](https://twitter.com/vladikoff) [@gf3](https://twitter.com/gf3) [@jon_neal](https://twitter.com/jon_neal) [@sambreed](https://twitter.com/sambreed) and [@iansym](https://twitter.com/iansym).

It has since received contributions from over [100 developers](https://github.com/h5bp/Front-end-Developer-Interview-Questions/graphs/contributors).
