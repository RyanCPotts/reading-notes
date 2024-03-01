# Class 10

### Name some key differences between a Syntax Error and a Logic Error.

Syntax Error:

Definition: Syntax errors occur when the code violates the rules of the programming language's syntax.
Cause: These errors are typically caused by misspelled keywords, missing punctuation, incorrect indentation, or using language constructs incorrectly.
Detection: Syntax errors are usually detected by the compiler or interpreter during the parsing phase of code execution.
Effect: The code fails to compile or execute, and an error message pointing to the location of the syntax error is usually displayed.
Logic Error:

Definition: Logic errors occur when the code executes without any syntax errors, but it produces unexpected or incorrect results due to flawed logic or algorithmic mistakes.
Cause: These errors stem from incorrect assumptions, faulty reasoning, or mistakes in the design or implementation of the algorithm.
Detection: Logic errors can be more challenging to detect than syntax errors because the code executes without any immediate indication of an error. They often manifest as incorrect output, unexpected behavior, or program crashes.
Effect: The code may run successfully without raising any errors, but the output or behavior of the program may not match the expected or desired outcome.
In summary, syntax errors involve violations of the language's syntax rules and are detected during the compilation or interpretation process, while logic errors involve flawed reasoning or incorrect algorithmic implementations and can lead to unexpected behavior or incorrect output during program execution.

### List a few types of errors that you have encountered in past lab assignments and explain how you were able to correct them.

Console log errors were usually a result of a syntax errors involving brackets. Logical errors when running loops and such.

### How will this topic continue to influence your long term goals?

As I progress I'm sure I'll run into all kinds of errors and knowing how to fix them will be key.

### How would you describe the JavaScript Debugger tool and how it works to someone just starting out in software development?

Detective Tool: The JavaScript Debugger is like a detective's magnifying glass. It helps you inspect and examine your code closely, just like a magnifying glass helps a detective examine clues.

Finding Clues (Bugs): In your code, there might be mistakes called bugs that cause it to not work correctly. The Debugger helps you find these bugs, just like a detective finds clues in a mystery.

Step-by-Step Investigation: The Debugger lets you go through your code step by step, just like a detective follows clues one by one. You can see what's happening at each step and where things might be going wrong.

Inspecting Variables: Like a detective examines evidence, the Debugger lets you see the values of different parts of your code while it's running. This helps you understand what's happening and spot any inconsistencies or mistakes.

Fixing the Mystery (Bug): Once you've found the bug, the Debugger helps you fix it by showing you exactly where the problem is and what's causing it, just like a detective solves the mystery by finding the culprit.

Overall, the JavaScript Debugger is a powerful tool that helps you investigate and solve problems in your code, just like a detective solves mysteries. It's like having a detective by your side to help you unravel the secrets of your code and make it work perfectly!

### Define what a breakpoint is.

 Imagine you're reading a book, and you want to take a break at a specific point to understand what's happening or to catch your breath. A breakpoint in programming is similar to that pause in the story.

Here's how I'd explain it:

Pausing Point: A breakpoint is like a pause button in your code. It's a special marker that you can set at a specific line in your code where you want the program to stop executing temporarily.

Understanding the Story (Code): When the program reaches a breakpoint, it pauses, allowing you to take a closer look at what's happening in the code at that moment. It's like stopping to re-read a paragraph in a book to understand it better.

Inspecting Variables (Details): At the breakpoint, you can examine the values of different parts of your code, just like you might examine details in a story to understand the plot better.

Finding Issues (Errors): Breakpoints are often used to find and fix problems (bugs) in the code. By pausing the program at specific points, you can see where things might be going wrong and figure out how to fix them.

Continuing the Story (Code): Once you've finished inspecting and understanding the code at the breakpoint, you can resume the program's execution, just like pressing play after taking a break from reading.

In essence, a breakpoint is a tool that helps you pause your code's execution at specific points, giving you the opportunity to examine and understand what's happening before continuing with the rest of the program.

### What is the call stack?

Imagine you're stacking up a bunch of plates in a cafeteria. You start with one plate, then add another on top, and keep stacking them up. The stack of plates grows higher and higher. This is similar to how the call stack works in programming.

Here's a non-technical explanation of the call stack:

Stacking Functions: Every time your program runs a function (a block of code that performs a specific task), it's like adding a new plate to the stack. The function goes on top of the stack.

Tracking Function Calls: The call stack keeps track of all the functions that are currently running in your program. Just like you can see all the plates in the stack, the call stack shows you all the functions that have been called but haven't finished yet.

Last In, First Out (LIFO): When a function finishes running, it's like taking the top plate off the stack. The program goes back to the function that called it and continues running from there. This process continues until all the functions have finished running and the stack is empty.

Managing Function Execution: The call stack helps manage the flow of execution in your program. It ensures that functions are called and executed in the right order, and it keeps track of where the program should go next after each function finishes running.

In summary, the call stack is like a stack of plates where each plate represents a function in your program. It helps keep track of function calls and manage the flow of execution, ensuring that your program runs smoothly from start to finish.


