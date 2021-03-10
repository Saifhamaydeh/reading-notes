# Error Handling & Debugging
JavaScript can be hard to learn and everyone makes 
mistakes when writing it. This chapter will help you learn 
how to find the errors in your code. It will also teach you how 
to write scripts that deal with potential errors gracefully. 

## ORDER OF EXECUTION
function greetUser () { 
return 'He 11 o ' + getName (); 
 
function getName() { 
var name= 'Molly ' ; 
return name; 
 var greeting= greetUser(); 
alert(greeting); 
1. the first step we call the function
2. in the function we call the secand function
3. last step the alert will compiled

## EXECUTION CONTEXT 

Every statement in a script lives in one of three 
execution contexts: 
1. GLOBAL CONTEXT 
Code that is in the script, but not in a function. 
There is only one global context in any page. 
2. FUNCTION CONTEXT 
Code that is being run within a function. 
Each function has its own function context. 
3. EVAL CONTEXT (NOT SHOWN) 
Text is executed like code in an internal function 
called eval
Each time a script enters a new execution context, there are two phases 
of activity: 
1. PREPARE 
• The new scope is created 
• Variables, functions, and arguments are created 
• The value of the this keyword is determined
2. EXECUTE 
• Now it can assign values to variables 
• Reference functions and run their code 
• Execute statements 
## ERROR OBJECTS 
Error objects can help you find where your mistakes are 
and browsers have tools to help you read them. 
OBJECT 
Error : Generic error - the other errors 
are all based upon this error 
Syntax Error : Syntax has not been followed
Reference Error :Tried to reference a variable that is 
not declared/within scope 
TypeError : An unexpected data type that 
cannot be coerced 

Range Error : Numbers not in acceptable range 
URI Error :encodeURI ().decodeURI(),and similar methods used incorrectly 

Eval Error : eval () function used incorrectly 

### HOW TO DEAL WITH ERRORS
there are two things you can do with the errors!
1. DEBUG THE SCRIPT TO FIX ERRORS 
2. HANDLE ERRORS GRACEFULLY

Get Started with Debugging JavaScript in Chrome DevTools bookmark_border
Table of contents.
Step 1: Reproduce the bug.
Step 2: Get familiar with the Sources panel UI.
Step 3: Pause the code with a breakpoint.
Step 4: Step through the code.
Step 5: Set a line-of-code breakpoint.
Step 6: Check variable values.

### HANDLING EXCEPTIONS 
If you know your code might fail, use try, catch, and finally. 
Each one is given its own code block. 
try { 
II Try to execute this code }
catch (exception) { 
II If there is an exception, run this code }
finally { 
II This always gets executed }