# Class 06

### Who is Roy Fielding?
Roy Fielding is a computer scientist known for his role in creating the HTTP specification and for developing the REST architectural style, which has become a foundation for building scalable web services.

### Why don’t the techniques that we use in this class work well when we need to be able to talk to all of the machines in the world?
The techniques used in a class may not scale well to communicate with all machines in the world because they might be limited in scope or designed for specific environments. Scaling to communicate with all machines globally requires robust protocols, standards, and architectures, which are typically more complex and optimized for the diverse range of devices, networks, and environments found worldwide. This challenge is often addressed through technologies like the Internet Protocol Suite (TCP/IP), HTTP, and REST, which are designed to facilitate communication across the vast and heterogeneous landscape of the internet.

### What is the HTTP protocol that Fielding and his friends created?
Roy Fielding, along with his colleagues, played a significant role in creating the HTTP (Hypertext Transfer Protocol) protocol. HTTP is the foundation of data communication for the World Wide Web. It defines how messages are formatted and transmitted, and how web servers and browsers should respond to various commands. HTTP enables the exchange of text, images, videos, and other multimedia files on the internet.

### What does a GET do?
In the context of the HTTP protocol, a GET request is a method used by a client (typically a web browser) to retrieve data from a server. When a client sends a GET request to a server, it is asking the server to send back a representation of a specific resource identified by a URL (Uniform Resource Locator).

The server then processes the GET request, retrieves the requested resource (such as a web page, an image, or a file), and returns it to the client in the HTTP response. GET requests are typically used for safe and idempotent operations, meaning they should not have any side effects on the server's state and can be repeated multiple times without changing the result.

### What does a POST do?
In the context of the HTTP protocol, a POST request is a method used by a client to send data to a server to create or update a resource. When a client sends a POST request to a server, it includes data in the request body, which the server processes according to the application's logic.

Unlike GET requests, which are primarily used for retrieving data, POST requests are often used for actions that modify the state of the server or create new resources. For example, submitting a form on a website, uploading a file, or making a purchase in an online store typically involve sending POST requests to the server.

POST requests are not idempotent, meaning that sending the same request multiple times may result in different outcomes or have side effects on the server's state. Therefore, they are commonly used for operations that change data or trigger actions on the server.

### What does PUT do?
In the context of the HTTP protocol, a PUT request is a method used by a client to send data to a server to create or update a resource at a specific URL. When a client sends a PUT request to a server, it includes the data to be stored or updated in the request body, along with the URL identifying the location of the resource.

PUT requests are commonly used for updating existing resources on the server. If the resource identified by the URL already exists, the server replaces it with the new data provided in the PUT request. If the resource does not exist, the server may create a new resource using the provided data.

It's important to note that PUT requests are idempotent, meaning that sending the same request multiple times should have the same effect as sending it once. This makes PUT requests suitable for operations that are intended to be repeatable without causing unintended side effects.

### What does PATCH do?
In the context of the HTTP protocol, a PATCH request is a method used by a client to send partial data to update a resource on the server.

Unlike PUT requests, which typically send the entire updated representation of a resource, PATCH requests are used to apply partial modifications to an existing resource. The client includes in the request body only the changes that need to be applied, rather than sending the entire updated representation.

PATCH requests are particularly useful when you want to make small, incremental changes to a resource without having to resend the entire representation. They are commonly used in RESTful APIs for updating specific fields or properties of a resource while leaving other parts unchanged.

It's worth noting that like PUT requests, PATCH requests are also idempotent, meaning that sending the same request multiple times should have the same effect as sending it once.
