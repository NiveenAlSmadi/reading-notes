### call Stack
A mechanism for an interpreter to keep track of its place in a script. Keeps track of functions and the order in which they were called. An order is made and added to a calls stack. Then orders are carried out. When functions are run it's first come first out. As soon as one is called it is the turn for the next function. Once a function is run and it's order has been completed it is taken out of the call stack.

Functions run one at a time once they are called. They are ordered in function hierarchy and execution. Last in first out.

#### Asynchronous Jv
1)callback function
2)event loop
3)task queue

#### Stack overflow
Function calls itself without an exit causing an error.
- JS error messages
First it indicates that something is wrong with the code.
Reference errors
These pop up when when a variable was not declared; not defined.
#### What causes a stack overflow?
A stack overflow occurs when there is a recursive function (a function that calls itself) without an exit point. The browser (hosting environment) has a maximum stack call that it can accomodate before throwing a stack error.
- Syntax Err
These happen due to parsing errors. Misspellings or a comma in the wrong place can cause these.

- Range Err
Manipulating an object with an invalid length.

- Type err
Useing types that are not compatible with each other.

- Console.log
We can use this to check variables in inspect or nodemon terminal. We can debug line per line to find where the issue is.

##### The key takeaways from the call stack are:
1. It is single-threaded. Meaning it can only do one thing at a time.
2. Code execution is synchronous.
3. A function invocation creates a stack frame that occupies a temporary memory.
4. It works as a LIFO — Last In, First Out data structure.