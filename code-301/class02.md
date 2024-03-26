#Class 02

### What types of things can you pass in the props?
primitive data types, arrays, functions, objects, react elements, children

### What is the big difference between props and state?
While both props and state are used to manage data in React, props are used for passing data from parent to child components, whereas state is used for managing internal component data that can change over time. Understanding when to use each is crucial for building React applications effectively.

### When do we re-render our application?
In React, re-rendering occurs when the state or props of a component change. React automatically re-renders components when it detects changes in their state or props. This is one of the core features of React that enables efficient and responsive UI updates.

### What are some examples of things we can store in state?

In React, state is used to manage data that is internal to a component and may change over time in response to user actions, events, or other factors. Here are some examples of things that you could store in state:

Form Input Values:

State can be used to store values of form inputs such as text fields, checkboxes, radio buttons, and select dropdowns. As users type or select values, the state is updated to reflect the current input.
UI State:

State can be used to manage UI-related information such as whether a modal is open or closed, the active tab in a tabbed interface, or the visibility of certain elements.
Toggle State:

State can be used to manage toggle states, such as whether a sidebar or dropdown menu is open or closed.
Counter Values:

State can be used to store counter values that need to be incremented or decremented based on user interactions.
Loading State:

State can be used to track whether data is loading from an API or server. This is useful for displaying loading spinners or messages to the user.
Error State:

State can be used to track whether an error has occurred during data fetching or form submission. This allows you to display error messages to the user.
Authentication State:

State can be used to manage authentication-related information, such as whether a user is logged in or not, and details about the current user.
Filtered Data:

State can be used to store filtered or sorted data displayed in a list or table. As users apply filters or sorting options, the state is updated to reflect the current view.
Cart State:

State can be used to manage the contents of a shopping cart in an e-commerce application. As users add or remove items from the cart, the state is updated accordingly.
Game State:

State can be used to manage game-related information such as scores, game levels, player positions, and game settings.
These are just a few examples of the types of data that can be stored in state in a React component. In general, state should be used to manage data that is specific to a component and may change over time as a result of user interactions or other events.
