# Error Handling & Debugging

*Reference: Jon Duckett JavaScript book, Ch. 10, “Error Handling & Debugging”*

It's ok if your Javascript code isn't writtern perfectly the first time. Programming is like problem solving, you are given a puzzle to solve, and you also have to write the instructions that allow the computer to solve it too. 

The Console & Dev tools: Tools built into the browser that help you hunt for errors

The order in which statements are executed can be complex, some tasks aren't complete until another statement or function has been run. 

Ever script in a statement lives in one of three execution contexts: Global Context, Function Context, Eval Context

**Variable Scope**

Global Scope: When a variable is declared outside of a function
Function-level Scope: When a variable is declared within a function, it can only be used within that function. 

The JavaScript interpreter processses one line of code at a time. When a statement needs data from another function, it stacks or pile the new function on top of the current task. 

**Error Objects**

Error objects can help you find where your mistakes are and browsers have tools to help you read them.

An error object includes the following:

- name
- message
- fileNumber
-l ineNumber

What are the several types of built-in error objects in JavaScript?

- Error: this is a generic other all other errors are base on
- SyntaxError: you get this when syntax hasn't been followed
- ReferenceError: you get this when you try to reference a variable that is NOT declared/within scope 
- TypeError: An unexpected data type that cannot be coerced
- RangeError: Numbers not in acceptable range
- UriError: encodeURI(), decodeURI(),and similar methods used incorrectly
- EvalError: eval()function used incorrectly

**How to deal with errors?**

1. Debug to fix the errors. 
2. Use try, catch, throw, or finally statements. 

**Debugging Workflow**

1. Look at the error message
2. Check how far the script is running
3. Use breakpoints where things are going wrong
- Once you have set breakpoints you can see if the variables around the, have the values you would expect them to.
4. Break down/break out parts of the code to test smaller pieces of functionality.
5. Check # of parameters for a function, or the # of items in an array, repeat process until problems are GONE!

You can just type code into the console and it will show you a result

**Console Methods**

- console.info(): used for general info
- console.warn(): used for warnings
- console.error(): used to hold errors

**If you set multiple breakpoints you can step through them 1 by 1**

**You can create a breakpoint in your code using just the debugger keyword.**

