LearnJavaScript: A list of resources
====================================

This list was inspired by (a now defunct) [discussion](http://www.linkedin.com/groupItem?view=&gid=121615&item=5909742634301140992&type=member&commentID=5909826380652113920&trk=eml-ntf-hero-like-my-discussion-cmt&midToken=AQG2dgaKId8xLA&fromEmail=fromEmail&ut=2sQj9Dud2coCo1#commentID_5909826380652113920) on LinkedIn's Javascript group.

![Alt text](./img/When-in-Rome.jpg "When in Rome Image")
*(Quote by the lovely [MPJ](https://twitter.com/mpjme?lang=en))*

---

### Table of Contents (work in progress)  

- [1. Learning](#learning)
- [2. Suggested Coding Rules & Best Practices](#2-suggested-coding-rules-and-best-practices)
- [3. Resources](#3-resources)
	- [3.1 Beginner Resources](#31-beginner-resources--updated)
		- [3.1.1 Courses](#311-courses--updated)
		- [3.1.2 Testing Code](#312-testing-code)
		- [3.1.3 APIs](#313-apis)
	- [3.2 General Resources](#32-general)
	- [Functional Programming](#functional-programming-reading)
		- [Reading](#functional-programming-reading)
		- [Video](#functional-programming-video)
		- [Video](#functional-programming-libraries)
	- [3.3 Node.JS](#33-nodejs)
	- [3.4 Frameworks & Libraries](#34-frameworks-and-libraries)
		- [3.4.1 Backbone.js](#backbonejs)
		- [3.4.2 jQuery](#)
		- [3.4.3 Angular & AngularJS](#)
		- [3.4.4 Ember](#)
		- [3.4.5 Knockout.js](#)
		- [3.4.6 React.js & Redux](#reactjs)
	- [3.5 Books](#35-books)
	- [3.6 Online Books](#36-online-books)
	- [3.7 Video & Audio](#37-video--audio)	
	- [3.8 Newsletters](#38-newsletters)
	- [3.9 Developers](#39-developers)
	- [work in progres...](#)
	- [3.10 Tools](#310-tools)
	- [3.11 JS Compiled Languages](#311-javascript-compiled-languages)

- [Maintainers](#maintainers)
- [Contributors](#contributors)

[![pages-build-deployment](https://github.com/kostasx/LearnJavascript/actions/workflows/pages/pages-build-deployment/badge.svg)](https://github.com/kostasx/LearnJavascript/actions/workflows/pages/pages-build-deployment)

---

<!-- L E A R N I N G -->

### LEARNING

* Understand [type coercion](https://github.com/getify/You-Dont-Know-JS/blob/2nd-ed/types-grammar/ch2.md)
* Get a good understaning of `Functions`, [`Scope` and `Hoisting`](http://justinchmura.com/2014/08/20/become-a-better-javascript-developer/) 

  - Understand exactly how non-primitive types are [passed to functions as arguments](http://dmitrysoshnikov.com/ecmascript/chapter-8-evaluation-strategy/#call-by-value).

  - Here are some really good resources explaining scope and hoisting:
    * [JavaScript Visualized: Hoisting](https://dev.to/lydiahallie/javascript-visualized-hoisting-478h), By [Lydia Hallie](https://github.com/lydiahallie)
    * [JavaScript Visualized: Scope (Chain)](https://dev.to/lydiahallie/javascript-visualized-scope-chain-13pd), By [Lydia Hallie](https://github.com/lydiahallie)
    * [**Scope in JavaScript** - HTTP 203](https://www.youtube.com/watch?v=5LEuJNLfLN0)
 
* Understand how `undefined` and `null` behave and how [they differ](https://2ality.com/2021/01/undefined-null-revisited.html). 
- Study `Objects`,  
  * [`Prototypal Inheritance` and `OOP`](http://manuel.kiessling.net/2012/03/23/object-orientation-and-inheritance-in-javascript-a-comprehensive-explanation/)  
  * [**OLOO**: Objects Linked to Other Objects](https://github.com/getify/You-Dont-Know-JS/blob/1st-ed/this%20%26%20object%20prototypes/ch6.md)
  * [**JavaScript Visualized: Prototypal Inheritance**](https://dev.to/lydiahallie/javascript-visualized-prototypal-inheritance-47co)
  * [**Marcus Phillips: Secrets and Lies about JavaScript classes** (Low-quality video but definitely worth watching)](https://www.youtube.com/watch?v=_JJgSbuj5VI)
* Make sure to understand **callbacks**, **IIFEs** and [**asynchronicity**](https://github.com/kostasx/LearnJavascript#async) as they are some of the most commonly encountered and crucial concepts in JS 
  * Callbacks in JavaScript:
    * [Callbacks in JavaScript](https://zellwk.com/blog/callbacks/)
    * [Callback function (MDN)](https://developer.mozilla.org/en-US/docs/Glossary/Callback_function)
    * [JavaScript: What the heck is a Callback?](https://codeburst.io/javascript-what-the-heck-is-a-callback-aba4da2deced)
  * Immediately Invoked Function Expression (IIFEs):
    * [IIFE (MDN)](https://developer.mozilla.org/en-US/docs/Glossary/IIFE)
    * [Immediately Invoked Function Expression - Beau teaches JavaScript](https://www.youtube.com/watch?v=3cbiZV4H22c)
    * [The IIFE Pattern (Video by Kyle Simpson)](https://frontendmasters.com/courses/javascript-foundations/iife-pattern/)
  * Asynchronous Programming in JavaScript:
    * [**Asynchronous Programming** (Excellent post)](https://eloquentjavascript.net/11_async.html)
    * [**JavaScript Visualized: Promises & Async/Await** (Excellent post)](https://dev.to/lydiahallie/javascript-visualized-promises-async-await-5gke)
* Study the source code of popular libraries: [jQuery](http://jquery.com/), [underscore](http://underscorejs.org/), etc. 

  Here are 2 great videos on the subject by Paul Irish: 
  * [10 Things I Learned from the jQuery Source](http://www.youtube.com/watch?v=i_qE1iAmjFg)
  * [11 More Things I Learned from the jQuery Source](http://www.youtube.com/watch?v=ARnp9Y8xgR4)
* Read (_or preferably buy_) every single book of the excellent [**You Don't Know JS**](https://github.com/getify/You-Dont-Know-JS) series by [Kyle simpson](https://twitter.com/getify) **[MUST READ]**
* Watch every video by [Douglas Crockford](https://www.youtube.com/results?search_query=douglas+crockford).
* Take the full course ['JavaScript The Good Parts'](http://frontendmasters.com/courses/javascript-the-good-parts/#toc) by Douglas Crockford on [Front End Masters](http://frontendmasters.com)
* Get a really good understanding of [closures](https://kostasx.github.io/LearnJavascript/external/JavaScript-Garden/index.html#function.closures) and [this](https://kostasx.github.io/LearnJavascript/external/JavaScript-Garden/index.html#function.this) 
  * [**JavaScript Closures are Super Simple!** (YouTube Video: 16 min)](https://www.youtube.com/watch?v=2cRjcXwsG0I)
  * [**JavaScript the Hard Parts: Closures, Scope, and Execution Context** (Student Approved Resource)](https://www.youtube.com/watch?v=ZVXrJ4dnUxM)
  * [**Understanding Functions and 'this'** By Bryan Hughes](https://www.youtube.com/watch?v=AOSYY1_np_4)

* Study performance and code optimization

  Here is a good article by Nicholas Zakas: 
  * [10 Javascript Performance Boosting Tips](http://jonraasch.com/blog/10-javascript-performance-boosting-tips-from-nicholas-zakas)
  * [**The cost of JavaScript in 2019** By Addy Osmani](https://v8.dev/blog/cost-of-javascript-2019)

* Check every tip on the [A Drip of JavaScript](http://designpepper.com/js-drip-archive/) list and subscribe to it.
* Check the _(archived version)_ of an old but good resource: [JavaScript Garden](https://kostasx.github.io/LearnJavascript/external/JavaScript-Garden/index.html).

	**JavaScript Garden** *is a growing collection of documentation about the most quirky parts of the JavaScript programming language. It gives advice to avoid common mistakes and subtle bugs, as well as performance issues and bad practices, that non-expert JavaScript programmers may encounter on their endeavours into the depths of the language.*

* Read some books. You can find some great books for JS on the BOOKS section of this list.
* Learn how to debug your JS code. Here are some good links as a starting point:

  * [Debugging JavaScript](https://developer.chrome.com/devtools/docs/javascript-debugging)
  * [Chrome DevTools Command Line API Reference](https://developer.chrome.com/devtools/docs/commandline-api)

* Study general Software Design Patterns along with JavaScript-specific Patterns and Anti-Patterns:

  * [Learning JavaScript Design Patterns, Addy Osmani](http://addyosmani.com/resources/essentialjsdesignpatterns/book/)
  * [Javascript Patterns, moderated by *Shi Chuan*](http://shichuan.github.io/javascript-patterns/)
  * [Frontend architecture: Decoupling apps from frameworks (DevFest 2019)](https://www.youtube.com/watch?v=jmcx3b78V8s)

* Understand the Single Threaded Process & Event Loop. 

  * [Concurrency model and Event Loop, MDN](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/EventLoop)
  * [The JavaScript Event Loop: Explained, By Erin  Swenson-Healey](http://blog.carbonfive.com/2013/10/27/the-javascript-event-loop-explained/)
  * [Understanding the node.js event loop, by *Mixu*](http://blog.mixu.net/2011/02/01/understanding-the-node-js-event-loop/)
  * [Introduction to Javascript Processes, by *Nico Valencia *](http://quickleft.com/blog/introduction-to-javascript-processes)
  * [How JavaScript Timers Work, By John Resig](http://ejohn.org/blog/how-javascript-timers-work/)
  * [Philip Roberts: Help, I'm stuck in an event-loop: How JavaScript actually works](http://vimeo.com/96425312)

* Study some of the modern APIs: [WebRTC](https://developer.mozilla.org/en-US/docs/Web/Guide/API/WebRTC), [File API](https://developer.mozilla.org/en-US/docs/Web/API/File), [Blob API](https://developer.mozilla.org/en-US/docs/Web/API/Blob), etc. 
* [Master `Regular Expressions`](#regex). 
* Get in the habit of testing. **(Crucial!)**. [QUnit](http://qunitjs.com/) is a good starting point. 
* Subscribe to these great YouTube channels and watch every video you can:

  * [CascadiaJS](https://www.youtube.com/user/cascadiajs)
  * [JSConf](https://www.youtube.com/user/jsconfeu/videos)
 
* Learn some framework or library like [jQuery](http://jquery.com/), [React](https://reactjs.org/), [Angular](https://angular.io/), [Vue.JS](https://vuejs.org/), [SVELTE](https://svelte.dev/), [Backbone.JS](http://backbonejs.org/), [underscore](http://underscorejs.org/), [AngularJS](https://angularjs.org/), [Ember](http://emberjs.com/), [Knockout.JS](http://knockoutjs.com/), etc. 
* [Try building a ToDo App using one of these libraries](http://todomvc.com/)
* Get to know [Node.JS](http://nodejs.org/) and start building apps. 
  * Try running server-side JS code usign `Node.JS` on [Runnable.com](http://runnable.com/)
  * Install [Node.JS](http://nodejs.org/) locally and start experimenting.
* Subscribe to Newsletters and stay up to date with JS and Node. *(See section `3.8 NEWSLETTERS`)*
* Become familiar with a Task Manager like [Grunt](http://gruntjs.com/) or [Gulp](#gulp) and/or learn how to use [npm scripts](https://www.freecodecamp.org/news/introduction-to-npm-scripts-1dbb2ae01633/).
* Learn how to use Module Bundlers like [WebPack](https://webpack.js.org/), [Parcel](https://parceljs.org/), [Browserify](http://browserify.org/) and [other](#build_tools).
* Start building cross-platform Desktop Applications using HTML/CSS/JavaScript in [Electron.JS](https://electronjs.org/) or [Node-Webkit](https://nwjs.io/).
* Follow some of the masters on Twitter. *(See `section 3.6` of the RESOURCES section)*
* Code using a [Style Guide](https://github.com/airbnb/javascript). 
* [And, of course, you definitely need to learn **TypeScript**!](#3112-typescript--updated)

### 2. SUGGESTED CODING RULES AND BEST PRACTICES

* Always use `let` or `const` when declaring variables. Avoid using `var`.
* [Code using `"use strict"`](http://justinchmura.com/2014/08/20/become-a-better-javascript-developer/) 
* If you are using [VSCode Editor](https://code.visualstudio.com/) add the `//@ts-check` comment at the top of your code for an extra layer of checks via  [TypeScript Linter](https://raw.githubusercontent.com/kostasx/LearnJavascript/master/img/ts-check.jpg)
* [Always use semicolons.](https://kostasx.github.io/LearnJavascript/external/JavaScript-Garden/index.html#core.semicolon) // [**Not using semicolons??? Lonely Island uses them everyday**](https://www.youtube.com/watch?v=M94ii6MVilw)
  * [Here's a little bit of **advice for the semicolon haters** (by Ben Alman)](http://benalman.com/news/2013/01/advice-javascript-semicolon-haters/)
* [Prefer using `===` over `==`](https://kostasx.github.io/LearnJavascript/external/JavaScript-Garden/index.html#types.equality) 
* Always use curly braces 
* Comment your code
* [Avoid/Reduce global variables](http://justinchmura.com/2014/08/20/become-a-better-javascript-developer/) 
* Avoid using `with()` 
* [Avoid using `eval()`](https://dev.to/spukas/everything-wrong-with-javascript-eval-35on)
* Pass functions instead of strings to setTimeout or setInterval, as this triggers eval() internally. 
* Use [JSHint](http://www.jshint.com/) / [JSLint](http://www.jslint.com/)
  * If you are using [VSCode](https://code.visualstudio.com/) you can add the following comment at the top of your code to enable type checking: `//@ts-check` ([See screenshot](https://github.com/kostasx/LearnJavascript/blob/master/README.md#tscheck))  
  * [Inline lint highlighting for the Sublime Text 2 editor](https://github.com/SublimeLinter/SublimeLinter-for-ST2)
  * [Interactive code linting framework for Sublime Text 3](https://github.com/SublimeLinter/SublimeLinter3)
* [Study and apply Software Principles such as **DRY**, **SOLID**, **KISS**, etc.](https://dev.to/pluralsight/my-5-favorite-software-design-principles-4ech)

*The difference between JavaScript and JavaScript with __use strict__*
![Alt text](./img/usestrict.jpg "Make a difference by coding with use strict")

<details>
	<summary><strong>ECMASCRIPT 6 | ES2015 [ UPDATED ]</strong></summary>
	<p><a href="https://scrimba.com/g/ges6"><strong>Learn modern JavaScript</strong> | Scrimba Interactive Screencasts | 54min</a></p>
	<p><a href="https://scrimba.com/g/gintrotoes6"><strong>Introduction to ES6+</strong> | Scrimba Interactive Screencasts | 67min</a></p>
	<p><a href="https://ponyfoo.com/articles/es6"><strong>ES6 Overview in 350 Bullet Points</strong></a></p>
	<p><a href="https://github.com/lukehoban/es6features"><strong>Overview of ECMAScript 6 features</strong></a></p>
</details>

### 3. RESOURCES

#### 3.1 BEGINNER RESOURCES [ UPDATED ]

* [**Introduction to JavaScript** \| Scrimba Interactive Screencasts \| 69min ](https://scrimba.com/g/gintrotojavascript)
* [**Just JavaScript** Course By Dan Abramov and Maggie Appleton](https://justjavascript.com/)
* [**JavaScript First Steps** \| MDN](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/First_steps)
* [**What Is JavaScript Made Of?**](https://overreacted.io/what-is-javascript-made-of/)
* [JavaScript the Right Way](https://github.com/braziljs/js-the-right-way)
* [**JavaScript Basics** A quick introduction to basic and important concepts of JavaScript](https://fkling.github.io/jsbasics/)
* [JavaScript For Cats, *by Max Ogden*](http://jsforcats.com/)
* [JavaScript Guide, MDN](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide)
* [Introduction to JavaScript - 24 Interactive Screencasts](https://scrimba.com/g/gintrotojavascript)
* [Learn modern JavaScript - ES6 through Interactive Screencasts](https://scrimba.com/g/ges6)
* [Introduction to ES6+ - 23 Interactive Screencasts](https://scrimba.com/g/gintrotoes6)
* [JavaScript and Node Fundamentals: A Collection of Essential Basics, *by Azat Mardan*](https://pepa.holla.cz/wp-content/uploads/2016/07/JavascriptAndNodeFundametals.pdf)
* [5 Tips to Become a Better JavaScript Developer, *by JUSTIN CHMURA*](http://justinchmura.com/2014/08/20/become-a-better-javascript-developer/)
* [JS 101](http://www.teaching-materials.org/javascript/)
* [Things Every Javascript Developer Should Know, by Lubomir Vitol](http://www.devbattles.com/en/sand/post-1427-Things+Every+Javascript+Developer+Should+Know)
* [JavaScript Idiosyncrasies](https://github.com/miguelmota/javascript-idiosyncrasies)
* [JavaScript Questions](https://github.com/lydiahallie/javascript-questions)
* [What the f*ck JavaScript?](https://github.com/denysdovhan/wtfjs)
* [Airbnb JavaScript Style Guide](https://github.com/airbnb/javascript)
* [Context or the "This" Keyword in JavaScript, *by Adam Breindel*](https://thenewcircle.com/s/post/1564/context_or_the_this_keyword_in_javascript_tutorial)
* [45 Useful JavaScript Tips, Tricks and Best Practices](https://modernweb.com/45-javascript-tips-tricks-practices/)
* [JavaScript DevDocs](http://devdocs.io/javascript/)
* [**How to Become a Great JavaScript Developer***](http://blog.ustunozgur.com/javascript/programming/books/videos/2015/06/17/how_to_be_a_great_javascript_software_developer.html)
* [FAQ for comp.lang.javascript](http://pointedears.de/scripts/faq/cljs/)
* **Archived Resources** _(links that are no longer available and only accessible via archive.org)_:
  * [7 JavaScript Basics Many Developers Aren't Using (Properly)](https://web.archive.org/web/20150314040207/https://tech.pro/tutorial/1453/7-javascript-basics-many-developers-aren-t-using-properly) 
  * [Javascript: BEST PRACTICES PART 1, *by Christian Heilmann*](https://web.archive.org/web/20200615000455/https://www.thinkful.com/learn/javascript-best-practices-1/) / [Part 2](https://web.archive.org/web/20200802075107/https://www.thinkful.com/learn/javascript-best-practices-2/)

##### 3.1.1 COURSES [ UPDATED ]

* [**Deep Dive Into Modern Web Development** \| Full Stack course by The University of Helsinki ](https://fullstackopen.com/en/)
* [CodeCombat: Learn to Code by Playing a Game](http://codecombat.com/)
* [Javascript for Beginners, Udemy **PAID COURSE**](https://www.udemy.com/beginning-javascript/)

##### 3.1.2 TESTING CODE

* [JSBin](http://jsbin.com/)
* [JSFiddle](http://jsfiddle.net/)
• [16 ONLINE JS EDITORS](http://codecondo.com/16-online-javascript-editors-for-web-developers/)

##### 3.1.3 APIs

* [**Web APIs**](https://developer.mozilla.org/en-US/docs/Web/API)
* [A presentation about several HTML5 APIs](http://eventloop.gr/frontend/html5/apis.html#/) (Contains useful links, code and resources in the slides)
* [Screen Orientation API](http://www.sitepoint.com/introducing-screen-orientation-api/)

#### 3.2 GENERAL

* [**Learn Javascript resources on MDN**](https://developer.mozilla.org/en/learn/javascript)
* [Essential JavaScript Links,A curated list by Eric Elliott and friends](https://gist.github.com/ericelliott/d576f72441fc1b27dace/0cee592f8f8b7eae39c4b3851ae92b00463b67b9)
* [JavaScript Garden](https://kostasx.github.io/LearnJavascript/external/JavaScript-Garden/index.html)
* [Learn JavaScript Essentials (for all skill levels), by Eric Elliott](https://medium.com/javascript-scene/learn-javascript-b631a4af11f2)
* [JavaScript, The Right Way](https://www.jstherightway.org/)
* [Dos and Donts: Best Practices When Learning JavaScript](https://www.youtube.com/watch?v=zILmbcIYnfw)
* [The site of Dr. Axel Rauschmayer](https://www.2ality.com/)
* [David Walsh's Blog](https://davidwalsh.name/)
* [Understand JavaScript Closures With Ease](http://javascriptissexy.com/understand-javascript-closures-with-ease/)
* [JavaScript and the Browser: Under the Hood, *by Ariya Hidayat*](https://speakerdeck.com/ariya/javascript-and-the-browser-under-the-hood)
* [JSdo It: Share JavaScript, HTML5 and CSS.](http://jsdo.it/)
* [Explore JavaScript: Popular and new libraries, top authors and trending discussions](https://kandi.openweaver.com/explore/javascript)
* [DailyJS](https://medium.com/dailyjs)

> ES6 (EcmaScript 2015)

* [A tutorial to JavaScript Arrow Functions **(Flavio Copes)**](https://flaviocopes.com/javascript-arrow-functions/)
* [Arrow functions, the basics **(JavaScript.info)**](https://javascript.info/arrow-functions-basics)
* [Arrow functions revisited **(JavaScript.info)**](https://javascript.info/arrow-functions) 

> PERFORMANCE

* [JavaScript Performance Analysis: Keeping the Big Picture, *by Ariya Hidayat*](http://calendar.perfplanet.com/2013/javascript-performance-big-picture/)
* [Speeding up JavaScript: Working with the DOM](https://developers.google.com/speed/articles/javascript-dom)
* [Javascript optimization – high performance JS apps](http://www.mellowmorning.com/2008/05/18/javascript-optimization-high-performance-js-apps/)
* [Writing Efficient JavaSc