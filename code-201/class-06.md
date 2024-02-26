# Class 6

### How would you describe an object to a non-technical friend you grew up with?
"Hey, imagine you're playing poker. A JavaScript object is like a hand you're dealt. It holds cards, right? Well, in JavaScript, an object holds different info, like player names and their chip counts. Each piece of info, like a player's name, is a property, just like a card in your hand. You can use these properties to keep track of stuff, just like you use your cards to play poker."

### What are some advantages to creating object literals?
Imagine you have a box. In this box, you can put different things like toys, books, or snacks. Each thing you put in the box has a name, like "teddy bear," "storybook," or "apple."

Now, think of an object literal in JavaScript as a special kind of box. But instead of putting physical things inside, you put pieces of information. This information can be anything you want to keep track of, like your name, age, or favorite color.

Just like you label your toys or books so you know what's inside the box, with an object literal, you give names to the pieces of information you're putting inside. These names are called "properties."

So, an object literal is like a virtual box where you can store different pieces of information, each labeled with a property name. It's a handy way to organize and keep track of data in your JavaScript code.

### How do objects differ from arrays?
Think of an array like a list of things. It's like a line of people waiting for ice cream. Each person (or item) has a number to know where they are in line.

Now, an object is more like a collection of labeled boxes. Instead of just being in a line, each thing has its own special box with a label on it.

So, in an array, you access things by their number in line, like "person number 3." But with an object, you access things by their label on the box, like "the box labeled 'cookies.'"

Arrays are great for when you just need to keep track of a bunch of things in order. But objects are handy when you want to organize things with specific labels, like different types of snacks in labeled boxes.

### Give an example for when you would need to use bracket notation to access an object’s property instead of dot notation.
"In JavaScript, both bracket notation and dot notation are used to access properties of an object. Dot notation is straightforward and commonly used when you know the exact name of the property you want to access. For example, if you have an object called 'person' with a property 'name', you can access it using dot notation like this: 'person.name'.

However, bracket notation comes in handy when the name of the property you want to access is not known in advance or is dynamic. For instance, if you have a variable called 'propertyName' storing the name of the property you want to access, you can use bracket notation like this: 'person[propertyName]'. This allows you to access properties dynamically at runtime, making bracket notation more flexible in certain situations."

This response provides a clearer explanation of the differences between bracket notation and dot notation, as well as a practical example demonstrating the use of bracket notation for dynamic property access.

### Evaluate the code below. What does the term this refer to and what is the advantage to using this?

The advantage of using this in this scenario is that it allows the method humanAge to access and utilize the properties (name and age) of the dog object directly, without needing to reference the object by name explicitly. This makes the code more flexible and reusable, as the method can be applied to any dog object, and it will correctly reference the properties of that specific instance.

### What is the DOM?
The Document Object Model (DOM) is like a map that web browsers use to understand and interact with web pages. It breaks down the page's content into a structured format that the browser can understand.

Imagine a web page as a house, and the DOM as a blueprint or map of that house. Each element on the page, like paragraphs, images, and buttons, is like a piece of furniture or decoration in the house.

With the DOM, web developers can use code (like JavaScript) to manipulate and change elements on the page dynamically. They can add new elements, remove existing ones, or change their appearance and behavior.

In simpler terms, the DOM is like the behind-the-scenes system that makes web pages interactive and dynamic, allowing users to click buttons, fill out forms, and interact with content on the page.

### Briefly describe the relationship between the DOM and JavaScript.
The DOM provides the structure and organization of the house, defining where each room (HTML element) is located and what it contains. JavaScript, acting as the handy person, can interact with this blueprint to dynamically move furniture (manipulate elements), add new decorations (create elements), or remove existing ones (delete elements) based on user actions or other events.

So, the relationship between the DOM and JavaScript is like the relationship between a blueprint and the handy person who can make changes to the house according to that blueprint, allowing for dynamic and interactive web pages.




