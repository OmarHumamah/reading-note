# NODE.JS

## An Introduction to Node.js on sitepoint.com

- What is node.js?
  - Node.js� is a JavaScript runtime built on Chrome�s V8 JavaScript engine.
  - Node.js is an event-based, non-blocking, asynchronous I/O runtime that uses Google�s V8 JavaScript engine and libuv library.
- In your own words, what is Chrome�s V8 JavaScript Engine?
  - The V8 engine is the open-source JavaScript engine that runs in Google Chrome and other Chromium-based web browsers, including Brave, Opera, and Vivaldi. It was designed with performance in mind and is responsible for compiling JavaScript directly to native machine code that your computer can execute.
- What does it mean that node is a JavaScript runtime?
  - That it achieves low latency and high throughput by taking a �non-blocking� approach to serving requests. In other words, Node.js wastes no time or resources on waiting for I/O requests to return.
- What is npm?
  - It is stands for node packaging manager.
- What version of node are you running on your machine?
  node -v => v14.17.0
- What version of npm are you running on your machine?
  npm -v => 6.14.13
- What command would you type to install a library/package called �jshint�?

  - Open your terminal and type the following:

  `npm install -g jshint`
  This will install the jshint package globally on your system. We can use it to lint the index.js file from the previous example:

  `jshint index.js`
  You should now see a number of ES6-related errors. If you want to fix them up, add `/* jshint esversion: 6 */` to the top of the index.js file, re-run the command and linting should pass.

- What is node used for?
  - Node allows developers to write JavaScript code that runs directly in a computer process itself instead of in a browser. Node can, therefore, be used to write server-side applications with access to the operating system, file system, and everything else required to build fully-functional applications.

_[source-01](https://www.sitepoint.com/an-introduction-to-node-js/)_
_[source-02](https://www.codecademy.com/articles/what-is-node)_
_[source-03](https://www.infoworld.com/article/3210589/what-is-nodejs-javascript-runtime-explained.html)_

## 6 Reasons for Pair Programming.

- What are the 6 reasons for pair programming?

  1.  Greater efficiency
  2.  Engaged collaboration
  3.  Learning from fellow students
  4.  Social skills
  5.  Job interview readiness
  6.  Work environment readiness

- In your experience, which of these reasons have you found most beneficial?
  - Learning from fellow students, when I worked with my team for 201 project I realized many ways and technuiqe to solve problems.
- How does pair programming work?
  - Pair programming commonly involves two roles: the Driver and the Navigator. The Driver is the programmer who is typing and the only one whose hands are on the keyboard. Handling the mechanics of coding, the Driver manages the text editor, switching files, version control, and of course writing code. The Navigator uses their words to guide the Driver but does not provide any direct input to the computer. The Navigator thinks about the big picture, what comes next, how an algorithm might be converted in to code, while scanning for typos or bugs. The Navigator might also utilize their computer as a second screen to look up solutions and documentation, but should not be writing any code.

_[source](https://www.codefellows.org/blog/6-reasons-for-pair-programming/)_

**[Back to: Homepage](https://omarhumamah.github.io/reading-note/).**
