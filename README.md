
Disadvantages of using callback function
1. Callback Hell :- Callback Hell happens in JavaScript when multiple nested callback functions are written in a way that makes the code hard to read and maintain. It looks like a pyramid or staircase and becomes difficult to debug or manage. This mostly happens when you perform many asynchronous operations one after another.

2. Inversion of Control :- Inversion of Control happens when you give control of your code's execution to another piece of code (like a library or framework). Instead of you calling the code, the code calls you back — you’re no longer in charge of the execution flow. This can lead to confusion or unexpected behavior if you're not careful.

It's often seen with callbacks, event handlers, or frameworks, where you write the logic, but something else decides when to run it.
