# Read:06 Summary
## Node, Express, and APIs
> Node.js is a JavaScript runtime built on Chrome’s V8 JavaScript engine.

> Node.js is an event-based, non-blocking, asynchronous I/O runtime that uses Google’s V8 JavaScript engine and libuv library.

* ` The V8 engine` is the open-source JavaScript engine that runs in Google Chrome
* It was designed with performance in mind and is responsible for compiling JavaScript directly to native machine code that your computer can execute.
* the V8 engine is enhanced with various features, such as a file system API, an HTTP library, and a number of operating system–related utility methods.

***Node.js is a program we can use to execute JavaScript on our computers. In other words, it’s a JavaScript runtime.***

* ` npm` : is a (node package manager) that comes bundled with Node.
* `nvm` : (node version manager) a program that allows you to install multiple versions of Node and switch between them at will.
* it negates potential permission issues when using Node with npm and lets you set a Node version on a per-project basis.
* Node has excellent support for ECMAScript 2015 (ES6) and beyond.this means that you can write your JavaScript using the latest and most modern syntax. It also means that you don’t generally have to worry about compatibility issues 
* `npm` is also the world’s largest software registry. There are over 1,000,000 packages of JavaScript code available to download.
* You can check that Node is installed on your system by opening a terminal and typing `node -v`
* for installing a Package Globally you can Open your terminal and type `npm install -g package name`
* for Installing a Package Locally Create a folder and open a terminal in that directory. Next type this:`npm init -y`
* Node and npm used for anything from bundling your JavaScript files and dependencies into static assets, to running tests, or automatic code linting and style checking.
* if you want to start developing apps with any modern JavaScript framework (for example, React or Angular), you’ll be expected to have a working knowledge of `Node` and `npm`(or maybe `Yarn`) to create a sensible development environment.
* one of the biggest use cases for `Node.js `— running JavaScript on the server. 
* Node now plays a critical role in the technology stack of many high-profile companies.
* `Node.js,` however, is single-threaded. It’s also `event-driven`, which means that everything that happens in Node is in reaction to an event.
* Node uses the `libuv library` to implement this asynchronous (that is, non-blocking) behavior.
* `Node’s execution model` causes the server very little overhead, and consequently it’s capable of handling a large number of simultaneous connections.
* `Node.js` even has a built-in module to help you implement a cloning strategy on a single server.

***Node is important to handle errors correctly***


### What Kind of Apps Is Node.js Suited To?
* Node is particularly suited to building applications that require some form of real-time interaction or collaboration — for example, chat sites, or apps such as CodeShare, where you can watch a document being edited live by someone else. It’s also a good fit for building APIs where you’re handling lots of requests that are I/O driven (such as those needing to perform operations on a database), or for sites involving data streaming, as Node makes it possible to process files while they’re still being uploaded.

-------------------------------------------------------------------------------------------------------
> Express having established itself as the front runner.

***Node’s big pluses is that it speaks JSON***

> **JSON** is probably the most important data exchange format on the Web, and the lingua franca for interacting with object databases (such as MongoDB). JSON is ideally suited for consumption by a JavaScript program, meaning that when you’re working with Node, data can flow neatly between layers without the need for reformatting. You can have one syntax from browser to server to database.

* `Node.js` can be used as a scripting language to automate repetitive or error prone tasks on your PC.
* `Node.js` can be used to write your own command line tool
* `Node.js` can be used to build cross-platform desktop apps and even to create your own robots









