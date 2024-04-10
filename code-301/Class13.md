# Class 13

### Which HTTP method would you use to update a record through an API?
The HTTP method commonly used to update a record through an API is the PUT method.

Here's why:

Idempotent: The PUT method is idempotent, meaning that making the same request multiple times will produce the same result. When you use PUT to update a resource, you're essentially replacing the existing resource with the new representation provided in the request payload. Therefore, if you send the same PUT request multiple times, it will result in the same updated resource state.

Replace: PUT is typically used for full updates, where you replace the entire resource with the new representation provided in the request payload. This is different from the PATCH method, which is used for partial updates.

Specific Resource: PUT requests are used when you have a specific URI for the resource you want to update. You include the new representation of the resource in the request payload and send it to the URI corresponding to the resource you want to update.

For example, if you have a RESTful API endpoint /users/{id} to update user records, you would typically use the PUT method to send updates to this endpoint, providing the new representation of the user in the request payload.

In summary, if you want to update a record through an API and you have the complete representation of the updated record, you would use the PUT method.

### Which REST methods require an ID parameter?
In a RESTful API, the following HTTP methods typically require an ID parameter:

GET: When you want to retrieve a specific resource from the server, you typically use the GET method along with an ID parameter to specify which resource you want to retrieve. For example, you might have an endpoint like /users/{id} to retrieve a specific user by their ID.

PUT: The PUT method is used to update a resource on the server. When using PUT, you usually need to specify the ID of the resource you want to update, along with the updated representation of the resource in the request payload. For example, you might have an endpoint like /users/{id} to update a specific user by their ID.

DELETE: The DELETE method is used to delete a resource from the server. Similar to the GET and PUT methods, you typically need to specify the ID of the resource you want to delete when using the DELETE method. For example, you might have an endpoint like /users/{id} to delete a specific user by their ID.

These HTTP methods require an ID parameter because they are typically used to interact with specific resources on the server. The ID parameter helps identify which resource the client wants to retrieve, update, or delete.

### What’s the relationship between REST and CRUD?

REST (Representational State Transfer) and CRUD (Create, Read, Update, Delete) are closely related concepts in the context of web development, particularly when designing and implementing APIs. Here's the relationship between REST and CRUD:

CRUD Operations: CRUD is an acronym that stands for Create, Read, Update, and Delete. These are the basic operations that can be performed on data within a database or any other persistent storage system.

Create: Creating new records or resources.
Read: Retrieving existing records or resources.
Update: Modifying existing records or resources.
Delete: Removing existing records or resources.
RESTful Principles: REST is an architectural style for designing networked applications. It provides guidelines for creating scalable, stateless, and loosely coupled web services. RESTful APIs are designed around resources, which are typically represented as URIs (Uniform Resource Identifiers). RESTful APIs use standard HTTP methods (GET, POST, PUT, DELETE) to perform CRUD operations on these resources.

Create: In REST, creating a new resource is typically done by sending a POST request to the URI representing the collection of resources. For example, to create a new user, you might send a POST request to /users.
Read: Reading or retrieving existing resources is done using the GET method. Clients send GET requests to the URI representing the specific resource or collection of resources they want to retrieve. For example, to retrieve a specific user, you might send a GET request to /users/{id}.
Update: Updating an existing resource in REST is done using the PUT or PATCH methods. PUT is typically used for full updates, where the entire resource is replaced with the new representation provided in the request payload. PATCH is used for partial updates, where only specific fields of the resource are modified. For example, to update a user, you might send a PUT or PATCH request to /users/{id}.
Delete: Deleting an existing resource is done using the DELETE method. Clients send DELETE requests to the URI representing the specific resource they want to delete. For example, to delete a user, you might send a DELETE request to /users/{id}.
In summary, CRUD operations define the basic functions for manipulating data, while RESTful principles provide a standardized way of designing APIs that expose these operations over HTTP. RESTful APIs use HTTP methods to map CRUD operations to specific actions on resources, providing a uniform interface for interacting with the API.

### If you had to describe the process of creating a RESTful API in 5 steps, what would they be?

Creating a RESTful API typically involves several steps to design, develop, and deploy the API. Here's a simplified description of the process in 5 steps:

Define the Resources and Endpoints:

Identify the resources your API will expose. These could be objects, entities, or data types that your application works with, such as users, products, or orders.
Define the URIs (Uniform Resource Identifiers) that represent these resources. Each resource should have a unique URI that clients can use to interact with it. For example, /users for a collection of users and /users/{id} for a specific user.
Choose HTTP Methods for CRUD Operations:

Decide which HTTP methods (GET, POST, PUT, DELETE) will be used to perform CRUD operations on each resource.
Use GET for reading or retrieving resources, POST for creating new resources, PUT or PATCH for updating existing resources, and DELETE for deleting resources.
Design the Request and Response Payloads:

Define the structure of the request and response payloads for each API endpoint. Specify the data format (e.g., JSON, XML) and the fields or properties included in each payload.
Consider including metadata such as status codes, headers, and error messages to provide additional context to clients.
Implement the API Endpoints:

Develop the server-side logic to handle incoming requests to the API endpoints.
Map each endpoint to a specific route or controller in your backend application framework (e.g., Express.js, Flask, Django).
Implement the business logic to perform the appropriate CRUD operations on the data based on the HTTP method and endpoint.
Test and Deploy the API:

Test the API endpoints to ensure they behave as expected and return the correct responses for different scenarios.
Use tools such as Postman or Thunder Client to send requests and verify the responses.
Once the API is tested and ready for production, deploy it to a server or cloud platform. Configure any necessary infrastructure components such as databases, load balancers, and security settings.
Monitor the API's performance, reliability, and security after deployment, and make any necessary adjustments or optimizations.
