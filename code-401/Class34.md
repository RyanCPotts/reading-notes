# Class 34 - API Integration

### Explain the different between a query string parameter and a path parameter.
When navigating a website or using an app, you often see different kinds of URLs (web addresses). These URLs can contain extra bits of information called parameters, which help the website understand what you want to see or do. There are two common types of parameters: query string parameters and path parameters. Here’s an explanation of each, using simple analogies:

Query String Parameters
Analogy: Think of query string parameters like a detailed shopping list you give to a friend when they go to the grocery store. The list tells them exactly what you want, but it’s not part of the store’s layout—it’s extra information.

Explanation:

Location in URL: Query string parameters appear at the end of a URL, following a question mark (?).
Structure: They are made up of key-value pairs (like "item=milk" or "amount=2"), separated by an ampersand (&) if there are multiple parameters.
Example: Imagine you’re shopping online and you want to filter results to see only red shoes in size 10. The URL might look like this: www.shop.com/shoes?color=red&size=10. Here, color=red and size=10 are query string parameters telling the website exactly what kind of shoes you want to see.
Path Parameters
Analogy: Think of path parameters like a specific address in a neighborhood. They tell you exactly where to go within a larger area, like "123 Main Street" in a city.

Explanation:

Location in URL: Path parameters are part of the URL path itself, often used to navigate to a specific section or item on a website.
Structure: They are part of the directory structure of the URL and are separated by slashes (/).
Example: Imagine you’re looking up a specific article on a news website. The URL might look like this: www.news.com/articles/12345. Here, 12345 is a path parameter that directs you to a specific article in the "articles" section of the website.
Summary
Query String Parameters:

Found at the end of a URL, after a question mark (?).
Provide extra information in key-value pairs (e.g., ?color=red&size=10).
Similar to a detailed shopping list specifying exactly what you want.
Path Parameters:

Part of the URL path, separated by slashes (/).
Navigate to specific sections or items (e.g., /articles/12345).
Similar to a specific address guiding you to an exact location.
Both types of parameters help websites understand what you’re looking for, but they are used in slightly different ways to provide or locate the information you need.

### We have created a dynamic API with an “interface”. Describe how that interface works to a non-technical friend.
The interface of a dynamic API acts as a user-friendly way to interact with complex systems. It ensures that you can make requests and get responses consistently and clearly, no matter how things might change behind the scenes. It's like a universal remote control that lets you easily operate different devices, simplifying your experience and saving you from having to understand the technical details.

### Describe how you would use middleware to implement basic and bearer auth.
Summary

Basic Auth Middleware: Extract credentials, validate, and grant access.

Bearer Auth Middleware: Extract token, verify, and grant access.

Both middleware functions serve as gatekeepers, ensuring only authenticated requests reach the protected routes.

### Describe the handshake necessary to implement OAuth.
This handshake ensures that third-party applications can access user data securely without needing to handle passwords directly. It’s a robust way to delegate access while maintaining user control and security.

### Describe how Role Based Access Control works to a non-technical friend.
Role Based Access Control (RBAC) works by assigning specific roles to users and then granting those roles permission to perform certain actions. Instead of giving each user individual access rights, you group users by their roles, such as "Admin," "Editor," or "Viewer," and each role has predefined access levels. This way, managing who can do what becomes simpler and more organized, like giving keys only to those who need them.



