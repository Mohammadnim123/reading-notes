# JavaScript

## CH 10 “Error Handling & Debugging”

* If you understand execution contexts (which have two
stages) and stacks, you are more likely to find the error
in your code.

**_Code Debugging:_**
Programming code might contain syntax errors, or logical errors.
Many of these errors are difficult to diagnose.
Often, when programming code contains errors, nothing will happen. There are no error messages, and you will get no indications where to search for errors.
Searching for (and fixing) errors in programming code is called code debugging.

* Debugging is the process of finding errors. It involves a
process of deduction.

**_JavaScript Debuggers:_**
Debugging is not easy. But fortunately, all modern browsers have a built-in JavaScript debugger.
Built-in debuggers can be turned on and off, forcing errors to be reported to the user.
With a debugger, you can also set breakpoints (places where code execution can be stopped), and examine variables while the code is executing.
Normally, otherwise follow the steps at the bottom of this page, you activate debugging in your browser with the F12 key, and select "Console" in the debugger menu.

* The console helps narrow down the area in which the
error is located, so you can try to find the exact error.

**_Setting Breakpoints:_**
In the debugger window, you can set breakpoints in the JavaScript code.
At each breakpoint, JavaScript will stop executing, and let you examine JavaScript values.
After examining values, you can resume the execution of code (typically with a play button).

* JavaScript has 7 different types of errors. Each creates
its own error object, which can tell you its line number
and gives a description of the error.

**_EvalError:_**
Creates an instance representing an error that occurs regarding the global function eval().

**_InternalError:_** 
Creates an instance representing an error that occurs when an internal error in the JavaScript engine is thrown. E.g. "too much recursion".

**_RangeError:_**
Creates an instance representing an error that occurs when a numeric variable or parameter is outside of its valid range.

**_ReferenceError:_**
Creates an instance representing an error that occurs when de-referencing an invalid reference.

**_SyntaxError:_**
Creates an instance representing a syntax error.

**_TypeError:_**
Creates an instance representing an error that occurs when a variable or parameter is not of a valid type.

**_URIError:_**
Creates an instance representing an error that occurs when encodeURI() or decodeURI() are passed invalid parameters.


* If you know that you may get an error, you can handle
it gracefully using the try, catch, finally statements.Use them to give your users helpful feedback.

**_The debugger Keyword:_**
The debugger keyword stops the execution of JavaScript, and calls (if available) the debugging function.
This has the same function as setting a breakpoint in the debugger.
If no debugging is available, the debugger statement has no effect.
With the debugger turned on, this code will stop executing before it executes the third line.

* Major Browsers' Debugging Tools
Normally, you activate debugging in your browser with F12, and select "Console" in the debugger menu.