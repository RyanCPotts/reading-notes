# Class 09

### What is functional programming?
Functional programming is a programming paradigm — a style of building the structure and elements of computer programs — that treats computation as the evaluation of mathematical functions and avoids changing-state and mutable data 

### What is a pure function and how do we know if something is a pure function?
A pure function is a function that always produces the same output for the same input and has no side effects. 

### What are the benefits of a pure function?
Pure functions offer several benefits, which make them an important concept in functional programming and software development in general. Here are some of the key benefits of pure functions:

Predictability: Pure functions always produce the same output for the same input, making them predictable and reliable. This property simplifies reasoning about the behavior of the code and debugging, as there are no hidden surprises or unexpected behaviors.

Testability: Because pure functions have no side effects and produce deterministic results, they are easy to test. Unit testing pure functions involves providing inputs and asserting the expected outputs, without the need for complex setup or mocking of external dependencies.

Reasoning and Understanding: Pure functions encapsulate their behavior within their parameters and return value, making it easier to understand and reason about the code. Developers can focus on the function's logic without worrying about unintended interactions with external state.

Reusability: Pure functions are inherently reusable because they depend only on their inputs and produce outputs without modifying external state. They can be composed together and reused in different contexts, promoting modular design and code reuse.

Concurrency and Parallelism: Pure functions are inherently thread-safe and can be safely executed in parallel or concurrent environments without the risk of race conditions or other synchronization issues. This property simplifies concurrent programming and enables better utilization of multicore processors.

Memoization: Pure functions are suitable candidates for memoization, a technique that caches the results of expensive function calls to improve performance. Since pure functions always produce the same output for the same input, the result can be cached and reused for subsequent calls with the same input.

Optimization and Refactoring: Pure functions are easier to optimize and refactor because their behavior is self-contained and free of side effects. Developers can confidently refactor pure functions without worrying about unintended consequences or breaking other parts of the codebase.

Overall, pure functions promote code quality, maintainability, and reliability by adhering to principles such as referential transparency and separation of concerns. Incorporating pure functions into your codebase can lead to cleaner, more maintainable, and more robust software systems.

### What is immutability?

Immutability is a concept in programming that refers to the state of an object or data structure being unable to be modified after it has been created. In other words, immutable objects cannot be changed once they are instantiated. Instead of modifying the existing object, any operation that appears to modify the object actually creates a new object with the desired changes.

### What is Referential transparency?
Referential transparency is a property of expressions in a programming language where an expression can be replaced with its value without changing the behavior of the program. In other words, if an expression always evaluates to the same result for the same inputs, and if it has no side effects, then it is referentially transparent.
