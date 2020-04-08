# Read:10 Summary
## Call stack

> A call stack is a mechanism for an interpreter to keep track of its place in a script that calls multiple functions.

* When a script calls a function, the interpreter adds it to the call stack and then starts carrying out the function.
* Any functions that are called by that function are added to the call stack further up, and run where their calls are reached.
* When the current function is finished, the interpreter takes it off the stack and resumes execution where it left off in the last code listing.
* If the stack takes up more space than it had assigned to it, it results in a "stack overflow" error.

***In `Asynchronous` JavaScript, we have a callback function, an event loop, and a task queue. The callback function is acted upon by the call stack during execution after the call back function has been pushed to the stack by the event loop.***

***Manage function invocation (call): The call stack maintains a record of the position of each stack frame.***

###  What causes a stack overflow?

* A stack overflow occurs when there is a recursive function(a function that calls itself)without an exit point


## JavaScript error messages && debugging
### Types of error messages

* Reference errors
* Syntax errors
* Range errors
* Type errors
### Debugging

* To debug the JS code, the easiest and maybe the most common way its to simply 'console.log()'

### Handling errors
* with a try…catch which would make an error be thrown
## Tools to avoid runtime errors

* quokka
* eslint




