# Class 7

## What is control flow?
n JavaScript, "control flow" refers to the order in which statements are executed within a program. Control flow determines the path that the program takes based on conditions and decisions made during its execution.

Control flow in JavaScript is typically managed using various control structures, including:

Conditional Statements: Conditional statements allow you to execute different blocks of code based on specified conditions. The most common conditional statements in JavaScript are if, else if, and else.

if (condition1) {
  // Code block to execute if condition1 is true
} else if (condition2) {
  // Code block to execute if condition2 is true
} else {
  // Code block to execute if none of the conditions are true
}
Loops: Loops allow you to repeat a block of code multiple times until a specified condition is met. JavaScript provides several types of loops, including for, while, and do...while loops.

// Example of a for loop
for (let i = 0; i < 5; i++) {
  // Code block to execute repeatedly
}

// Example of a while loop
let i = 0;
while (i < 5) {
  // Code block to execute repeatedly
  i++;
}
Switch Statements: Switch statements allow you to perform different actions based on the value of a variable or expression. They are often used as an alternative to long chains of if...else statements.

switch (expression) {
  case value1:
    // Code block to execute if expression matches value1
    break;
  case value2:
    // Code block to execute if expression matches value2
    break;
  default:
    // Code block to execute if expression does not match any case
}
Exception Handling: Exception handling allows you to handle errors and unexpected situations gracefully within your code. JavaScript provides try, catch, and finally blocks for exception handling.

try {
  // Code that may throw an error
} catch (error) {
  // Code to handle the error
} finally {
  // Code to execute regardless of whether an error occurred or not
}
Control flow is essential in programming as it allows you to create dynamic and interactive applications that respond to user input and changing conditions. Understanding control flow mechanisms enables developers to write more efficient and organized code.

## What is a JavaScript function?
In JavaScript, a function is a block of code that performs a specific task or calculates a value. Functions allow you to encapsulate reusable pieces of code, making your programs more modular, readable, and maintainable.

Here are the key characteristics of JavaScript functions:

Declaration: You can declare a function using the function keyword followed by the function name, parameters (if any), and the function body enclosed in curly braces {}.

function functionName(parameter1, parameter2) {
  // Function body
}
Parameters: Parameters are variables listed in the function definition and are placeholders for values that the function will receive when it is called. They are optional, and a function can have zero or more parameters.

Function Body: The function body contains the statements that define what the function does when it is called. This is the actual code that executes when the function is invoked.

Return Statement: Functions can optionally return a value using the return statement. When a function encounters a return statement, it immediately exits, and the value specified after return is passed back to the caller.

Here's an example of a simple JavaScript function:


function add(a, b) {
  return a + b;
}

// Calling the function
let result = add(3, 5);
console.log(result); // Output: 8
In this example:

The add function takes two parameters a and b.
Inside the function body, it returns the sum of a and b.
When the function is called with add(3, 5), it returns 8, which is then assigned to the variable result.
Functions in JavaScript are first-class citizens, meaning they can be assigned to variables, passed as arguments to other functions, and returned from other functions. This allows for powerful and flexible programming paradigms such as functional programming and callbacks.


## What does it mean to invoke - or call - a function?
In JavaScript, to "invoke" or "call" a function means to execute the code inside the function's body with a specific set of arguments, if any.

When you invoke a function, you're essentially telling the JavaScript engine to execute the statements within that function's body, potentially passing in values (arguments) for the function to work with.

Here's the general syntax for invoking a function:

functionName(argument1, argument2, ...);

## What are the parenthesis () for when you define a function?
avaScript, parentheses () are used in function declarations and function expressions to specify the parameters (inputs) that the function accepts.

When you define a function, you can include a list of parameters inside the parentheses to specify what values the function expects to receive when it's called. These parameters act as placeholders for the actual values (arguments) that will be passed to the function when it is invoked.

Here's the syntax for defining a function with parameters:

function functionName(parameter1, parameter2, ...) {
  // Function body
}
