# Class 10

### What is a ‘call’?

In the context of JavaScript callbacks, a 'call' refers to the act of invoking or executing a function. When you call a function, you're instructing JavaScript to run the code defined within that function's body.

### How many ‘calls’ can happen at once?
In JavaScript, only one function call can happen at a time in a single execution context. JavaScript is single-threaded, meaning it can only execute one piece of code at a time within a single thread of execution. This is often referred to as the event loop model.

### What does LIFO mean?
LIFO stands for Last In, First Out. It is a principle or methodology used in various contexts, including data structures and resource management.

In LIFO, the last element added to a collection or system is the first one to be removed. This means that the most recently added item is the one that gets processed or accessed first, and the oldest item is processed last.

The concept of LIFO is often visualized as a stack, where elements are added or removed from the top of the stack. Think of it as a stack of plates in a cafeteria: when you add a new plate, you place it on top of the stack, and when you remove a plate, you take the one from the top.

### Draw an example of a call stack and the functions that would need to be invoked to generate that call stack.
(insert here)

### What causes a Stack Overflow?
A Stack Overflow occurs when the call stack of a program exceeds its maximum size or capacity. This situation typically arises when there are too many function calls nested within each other, leading to an infinite recursion or an excessively deep chain of function calls. 

### What is a ‘reference error’?
ReferenceError is a runtime error, meaning it occurs during the execution of the code rather than during parsing or compilation. When a ReferenceError occurs, it usually halts the execution of the script unless it is caught and handled using try-catch blocks or other error-handling mechanisms.

### What is a ‘syntax error’?
A "syntax error" is a type of error that occurs in programming when the syntax (structure or grammar) of the code violates the rules of the programming language. Syntax errors prevent the code from being parsed or compiled correctly, resulting in a failure to execute the program.

### What is a ‘range error’?
A "RangeError" is a type of error that occurs in JavaScript when a value is not within the range of acceptable values as defined by the language specification. Range errors typically occur when attempting to perform operations that result in values outside the allowable range or when using methods or functions with arguments that are out of bounds.

### What is a ‘type error’?
A "TypeError" is a type of error that occurs in JavaScript when an operation is performed on a value of an inappropriate type. In other words, it happens when there is a mismatch between the expected data type and the actual data type of a value being used in an operation or when a method or property is called on a value that does not support it.

### What is a breakpoint?
A breakpoint is a tool used in software development environments, particularly in Integrated Development Environments (IDEs) and debugging tools, to pause the execution of a program at a specific point during its execution.

When a breakpoint is set, the program will stop executing when it reaches the line of code or instruction specified by the breakpoint. This allows developers to inspect the state of the program at that moment, including variable values, the call stack, and other runtime information.

### What does the word ‘debugger’ do in your code?
The word "debugger" typically refers to a software tool or utility that is used by developers to identify and resolve issues, errors, or bugs in their code. A debugger allows developers to inspect the behavior of their code, track the flow of execution, and analyze the state of variables and objects during runtime.

In your code, if you include the term "debugger," it typically indicates that you are instructing the JavaScript runtime environment to pause execution at that point and launch the debugger tool. When the code reaches the "debugger" statement during execution, it will halt, and control will be transferred to the debugger tool, allowing you to interactively inspect and debug the code.
