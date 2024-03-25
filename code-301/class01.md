### What is a “component”?
In React, a component is a reusable building block that encapsulates a piece of UI (User Interface) and its behavior. Components are the core building blocks of React applications, allowing developers to create complex UIs by composing smaller, self-contained pieces.

### What are the characteristics of a component?
Reusability: Components are designed to be reusable, meaning they can be used multiple times throughout an application. This promotes modular design and reduces code duplication.

Encapsulation: Components encapsulate both the UI and behavior associated with a particular piece of functionality. This helps in organizing code and keeping it modular and maintainable.

Composability: Components can be composed together to create complex UIs. This allows developers to build UIs by combining smaller, self-contained components.

State Management: Components may manage their own state using the useState hook (for functional components) or by extending React.Component (for class components). State allows components to maintain and update data over time.

Lifecycle Methods (for class components): Class components in React have lifecycle methods such as componentDidMount, componentDidUpdate, and componentWillUnmount. These methods allow components to perform actions at specific points in their lifecycle, such as fetching data when the component mounts or cleaning up resources when it unmounts.

Props: Components can receive data from their parent components via props (properties). Props are immutable and allow components to be configured dynamically.

Event Handling: Components can respond to user interactions and events by defining event handlers. This enables interactivity in the UI and allows users to interact with the application.

Rendering: Components define the structure and appearance of the UI by returning JSX (JavaScript XML) elements. JSX is a syntax extension that allows developers to write HTML-like code within JavaScript.

Testability: Components are testable units of code, making it easier to write unit tests for specific UI elements and functionality.

Overall, components are fundamental building blocks in React applications, and understanding their characteristics is essential for developing modular, maintainable, and scalable UIs.

### What are the advantages of using component-based architecture?
Modularity: Components are self-contained and encapsulate specific functionality, making it easier to understand, maintain, and update code. This modularity promotes code reusability and facilitates collaboration among developers.

Reusability: Components can be reused across different parts of an application or even in multiple applications. This reduces development time and effort by leveraging existing components rather than building everything from scratch.

Scalability: Component-based architectures allow applications to scale more effectively. As new features are added or requirements change, developers can create new components or modify existing ones without impacting the entire application. This modular approach makes it easier to manage and scale large codebases.

Separation of Concerns: Components separate concerns by encapsulating both UI and behavior. This separation makes code easier to understand and maintain, as each component focuses on a specific aspect of functionality.

Encapsulation: Components encapsulate their own state and behavior, reducing coupling between different parts of the application. This improves code maintainability and makes it easier to debug and troubleshoot issues.

Testability: Components are independent units of code, making them easier to test in isolation. This facilitates unit testing, integration testing, and regression testing, ensuring the reliability and stability of the application.

Parallel Development: Component-based architectures enable parallel development by allowing teams to work on different components simultaneously. This accelerates the development process and improves time-to-market for new features and updates.

Consistency: Components promote consistency in UI design and implementation. By reusing components across the application, developers can ensure a consistent look and feel, as well as consistent behavior, leading to a better user experience.

Overall, component-based architecture offers numerous benefits, including modularity, reusability, scalability, separation of concerns, encapsulation, testability, parallel development, and consistency. These advantages make it a popular choice for building modern software applications.

### What is “props” short for?
Properties

### How are props used in React?

In React, props (short for "properties") are used to pass data from parent components to child components. Props allow you to customize and configure child components dynamically by providing them with data or parameters.

### What is the flow of props?

Top-down, unidirectional.
