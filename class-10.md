# JS, Ch. 10, “Error Handling & Debugging” p450-486
When debugging, consider the order of execution.  JavaScript processes one line of code at a time.  It stacks functions that need data from other functions on top of them.  

Two phases of activity during an execution context:
1. prepare: scope, variables, functions and arguments created
2. execute: values assigned to variables, runs function code, executes statements. 

hoisting means that youc an call functions before they are declared (only if they are function declarations, not function expressions) and assign values to variables before they are declared.

variables obkect- contains details of the variables, functions and paramenters for the execution context. 

functions have lexical scope- they are linked to the object they were defined within.  so fo each execution context, the scope is the current execution context's variables object plus that of the parent's.

ideally you create variables inside the functions that use them.

If a JS statement generates an error, it throws an exception and looks for exception handling code.  You can handle the error with a set of statements if you anticipate something in your code may cause an error.

error objects help you find where your mistakes are. Among the info you'll get on p. 459-461.

When debugging, try to narrow down the area where the problem is or might be.  you can write console statements to see how far your script is running. Create breakpoints to see if the variables around them have the values you would expect them to.  If not, look earlier in the script.  Break things down into pieces.  write values of variables to the console, call functions to the console to see if they're returning the values you expect, check if objects exist and have the properties/methods you think they do.  Then check the items in an array, or the parameters in a function.  Repeat if necessary!  use browse dev tools and the javascript console!  
