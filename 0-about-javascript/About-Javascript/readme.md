# Javascript
* JavaScript is a high-level programming language used for web development and it is synchronous and Single  Threaded Language. It was developed by Netscape.
* It is single-threaded, meaning it can only execute one command at a time, and is interpreted, meaning it is not compiled before execution.
* V8 is a high-performance JavaScript engine developed by Google and used in their Chrome browser, as well as other applications.
* It compiles JavaScript code to machine code, improving its performance.

JavaScript is primarily used for client-side scripting, meaning it runs on the user's web browser, and is used to create dynamic and interactive web pages. It is often used in conjunction with HTML and CSS.


## * Everything in Javascript happens inside a Execution Context

JavaScript Execution Context is the environment in which JavaScript code is executed. It contains information about the <strong>variables, functions, and objects </strong> that are available to the code being executed, as well as the <strong>scope chain and the value of the 'this' keyword.</strong>

<img src="https://www.freecodecamp.org/news/content/images/2022/12/1.png">


## * Call stack

A call stack is a mechanism for an interpreter (like the JavaScript interpreter in a web browser) to keep track of its place in a script that calls multiple functions — what function is currently being run and what functions are called from within that function, etc.

1. When a script calls a function, the interpreter adds it to the call stack and then starts carrying out the function.
2. Any functions that are called by that function are added to the call stack further up, and run where their calls are reached.
3. When the current function is finished, the interpreter takes it off the stack and resumes execution where it left off in the last code listing.
4. If the stack takes up more space than it was assigned, a "stack overflow" error is thrown.