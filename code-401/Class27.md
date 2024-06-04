# Class 27 - useState Hook

### Break the UI into a Component Hierarchy:

Start by drawing boxes around every component (and subcomponent) in the mockup.
Identify each component and the hierarchy in which they belong. This helps in understanding the structure and the relationships between different parts of the UI.
Build a Static Version in React:

Build a version of your UI that takes your data model and renders the UI but has no interactivity.
Use props to pass data to components. Avoid using state at this stage.
Identify the Minimal (but Complete) Representation of UI State:

Determine what the minimal set of mutable state your application needs.
Consider each piece of data in your application, and decide whether it should be a state or a prop.
Identify Where Your State Should Live:

For each piece of state in your application, identify which component should own and manage it.
Ensure that the state is placed in a common ancestor component if it is shared between multiple components.
Add Inverse Data Flow:

Add inverse data flow by identifying how components can update the state.
Pass down callback functions to children components to update the state in their parent component.
These steps guide you in structuring and developing your React application in a systematic and organized manner, ensuring that your UI is modular, maintainable, and easy to reason about.

### What is one reason a local variable isn’t sufficient for managing a React component?
One reason a local variable isn’t sufficient for managing a React component is that local variables do not trigger re-renders when their values change. In React, the UI needs to be re-rendered to reflect changes in the component's state. React's useState hook (or class component state) is specifically designed to manage state within a component and ensure that the component re-renders when the state changes. This way, the UI stays in sync with the state of the component.

### What is the argument to the useState hook, and what are the two parts of its return array?
The argument to the useState hook is the initial state value for the state variable. This value can be of any type (number, string, object, array, etc.).

The useState hook returns an array with two elements:

The current state value.
A function to update the state value.

### How can Component A access state from Component B?
In React, if Component A needs to access state from Component B, you typically achieve this through lifting state up to a common ancestor component or using a context.
