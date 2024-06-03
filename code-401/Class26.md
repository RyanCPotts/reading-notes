# Class 26 - React

### What are the building blocks of a React app?
Components: Reusable, self-contained pieces of UI that can be either functional or class-based.
JSX: JavaScript XML, a syntax extension that allows you to write HTML within JavaScript.
Props: Short for properties, these are inputs to components that allow data to be passed from parent to child components.
State: An object that holds dynamic data and determines the component's behavior and rendering.
Lifecycle Methods: Methods that allow components to run code at specific times during the component's existence (e.g., componentDidMount).
Hooks: Functions like useState and useEffect that let you use state and other React features in functional components.
Context: A way to pass data through the component tree without having to pass props down manually at every level.

### What is the difference between an HTML element and a React component?
In summary, HTML elements are static building blocks of web pages, while React components are dynamic, reusable units of UI that can encapsulate logic, state, and interactivity.

### What is JSX and why do we use it?
JSX improves code readability and maintainability by providing a clear and concise way to define UI components in React.

### Describe the process of embedding JavaScript expressions in JSX.
Imagine Building Blocks:

Think of creating a digital greeting card using blocks. The blocks represent parts of the card, like the title or message.
Mixing Content:

Normally, you write the card message directly, like "Hello, Alice!".
With JSX, you can mix in dynamic content, like changing the name based on who opens the card.
Using Curly Braces:

To insert a special note or calculation in the card, you use curly braces {}. It’s like saying, "Hey, put something special here."
For example, if the message block says Hello, {name}!, and the name is Alice, it shows "Hello, Alice!".
Real-Life Analogy:

Imagine you have a magic recipe card that updates ingredients automatically. Instead of writing "3 eggs", you write {substitute for 3 eggs}, and it changes based on what you have.
Similarly, JSX updates parts of the webpage based on data or user actions.

### Does React or JSX have any special features for iteration or conditional logic?
Iteration: Use JavaScript’s map function to loop over arrays and render elements.
Conditional Logic: Use JavaScript conditional operators like the ternary operator (? :) and logical AND (&&) to conditionally render elements.
These techniques allow you to create dynamic and responsive UIs in React with JSX.

### How does React know to respond to a user’s inputs?
React responds to user inputs by using event listeners to handle events, state management to keep track of changes, and the virtual DOM to efficiently update the actual DOM. This ensures that the UI remains responsive and performant.

### What word indicates that a React component manages data with a Hook?
The prefix "use" in a function name indicates that the function is a Hook in React, which is used to manage state, side effects, and other functionalities within functional components.

### How can two react components share data?
Two React components can share data using props, context, state lifting, or Redux. Props allow parent components to pass data down to child components. Context provides a way to pass data through the component tree without manually passing props. State lifting involves lifting shared state up to a common ancestor and passing it down as props. Redux is a state management library that provides a global store for components to share data through actions and subscriptions. Each method offers a different approach depending on the complexity and requirements of the application.
