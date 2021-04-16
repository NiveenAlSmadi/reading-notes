## Error Handling & Debugging

### S debugging
Debugging is solving puzzles and creating instructions that allow the computer to solve the problem.

### Order of execution
Order of executions are not as simple as 123. Tasks run in different orders depending on the code. One code may not run if the code before needs to complete, or if the code after is run.

### Execution Context
- Global; Code in script but not in function.
- Function Context; Code running inside a function.
- Eval Context; Code in an internal function.

### Variable Scope
- Global Scope; Outside function variables can be used anywhere.
- Function-Level Scope; var declared in a function.
#
### The console/ dev tools
- Tools inside a browser used to find problems in code.

#
### Execution context and hoisting
- Prepare phase is when we create a var or function.
- Execute is when we call statements, run code, reference functions.
#
### Lexical scope
- Functions are linked to the object they were defined in.
- Objects and it's parents. Objects can get information from the parent but not the other way around.
#

### Errors
Js will look for error handling codes when it has found an error. I it doesn't find an error handling code it will terminate the script and create an error object.

#
### Property Description 
- Name
- message
- filenumber
- linenumber

#
### Error objects
- Error; Generic error.
- syntaxerror; syntax has not been followed.
- ReferenceError; var not declared.
- TypeError; Unexpected data that cannot be coerced.
- RangeError; Number not acceptable range.
- URIError; encodeURI (), decodeURI () methods used incorrectly. 
- eval() function used incorrectly.
#
### Dealing with errors
Use dev tools in browser to find errors and fix them. Talk the problem out loud. What is the error code pointing to? what should be happening. Ask a fellow programmer. Once an area is found with an error, break that area down into small pieces and test functionality. Call functions in the console or write var in the console. Try again. Fine toothed comb approach. 
#
We can use something called break points in the console to stop the script from running at the place of the error message. We can then hover over values and examine. We can also set a break point if certain conditions in the code are met. 
#
### Try, Catch, Finally
- Try Specify the code.
- If try code throws exception, catch will run alternative code.
- This will run at the end of either try or catch.
#
### Throwing errors
Creating your own errors to the what may be the cause of the actual error.
- throw new error(message).
