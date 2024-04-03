# Class 08 -- APIs

### What does REST stand for?
Representational State Transfer. It is an architectural style for designing networked applications. RESTful APIs adhere to the principles of REST, which include using standard HTTP methods (such as GET, POST, PUT, DELETE) for communication and leveraging the statelessness of HTTP to create scalable and reliable systems. RESTful APIs typically use JSON or XML for data exchange.

### REST APIs are designed around a ____.
REST APIs are designed around a resource. In RESTful architecture, resources are the key abstractions, representing any information that can be named, such as a document, image, or user. Each resource is uniquely identifiable through a URI (Uniform Resource Identifier), and the operations performed on these resources are defined by the standard HTTP methods like GET, POST, PUT, DELETE, etc.

### What is an identifier of a resource? 
An identifier of a resource is a unique reference that allows you to locate and interact with that resource within a system. In the context of RESTful APIs, URIs (Uniform Resource Identifiers) serve as identifiers for resources.

For example, consider a simple blog application. Each blog post might be represented as a resource, and each post could have a unique identifier in the form of a URI.

### What are the most common HTTP verbs?
GET: Used to request data from a server. It should only retrieve data and should not have any other effect on the data.
POST: Used to submit data to be processed to a specified resource. It can create new resources or update existing ones.
PUT: Used to update data on a server. It replaces the existing data with the new data provided in the request.
DELETE: Used to delete a specified resource from the server.
PATCH: Used to apply partial modifications to a resource.
HEAD: Similar to GET but only returns the headers of the response without the actual data.
OPTIONS: Used to describe the communication options for the target resource.
TRACE: Used to perform a message loop-back test along the path to the target resource.
CONNECT: Used to establish a tunnel to the server identified by the target resource.
OPTIONS: Used to retrieve the supported HTTP methods of a server.
Among these, GET, POST, PUT, and DELETE are the most commonly used HTTP verbs in RESTful APIs for CRUD (Create, Read, Update, Delete) operations.

### What should the URIs be based on?
URIs (Uniform Resource Identifiers) in RESTful APIs should be based on the resources they represent. This means that URIs should reflect the hierarchical structure of the resources within the system.

### Give an example of a good URI.
  https://api.example.com/v1/users
In this URI:

https://api.example.com is the base URL of the API.
/v1 indicates the version of the API being used.
/users represents the collection of users.
This URI follows several best practices:

It's resource-oriented: The URI represents a resource (users).
It's versioned: The version number (v1) is included in the URI.
It's hierarchical: The URI has a clear hierarchical structure, indicating that it's accessing users within the API.
It's readable and concise: The URI is easy to read and understand.
It avoids unnecessary information: It doesn't include unnecessary details, focusing solely on identifying the resource (users).
Overall, this URI provides a clear and intuitive way to access the collection of users in the API.

### What does it mean to have a ‘chatty’ web API? Is this a good or a bad thing?
A "chatty" web API refers to an API that requires a large number of requests to accomplish a single task or retrieve a set of data. In other words, it means that the client needs to make multiple API calls to perform a single operation or retrieve a complete set of data.
  It's generally a bad thing.

### What status code does a successful GET request return?
A successful GET request typically returns a status code of 200 OK. This status code indicates that the request has succeeded, and the server has returned the requested resource(s). The response body usually contains the requested data.

### What status code does an unsuccessful GET request return?
An unsuccessful GET request typically returns a status code indicating the specific reason for the failure. Some common status codes for unsuccessful GET requests include:

404 Not Found: This status code indicates that the requested resource could not be found on the server.

403 Forbidden: This status code indicates that the server understood the request but refuses to authorize it. This could be due to lack of permissions or authentication failure.

401 Unauthorized: Similar to 403 Forbidden, this status code indicates that the request lacks valid authentication credentials for the target resource.

400 Bad Request: This status code indicates that the server cannot process the request due to malformed syntax or other client-side error.

500 Internal Server Error: This status code indicates that the server encountered an unexpected condition that prevented it from fulfilling the request. This could be due to a server-side error.

The specific status code returned depends on the circumstances of the unsuccessful GET request. It's essential to check the response status code and handle it appropriately in the client application.

### What status code does a successful POST request return?
A successful POST request typically returns a status code of 201 Created. This status code indicates that the request has been fulfilled, and a new resource has been created as a result of the request. The server should include a Location header in the response, indicating the URI of the newly created resource.

### What status code does a successful DELETE request return?
A successful DELETE request typically returns a status code of 204 No Content. This status code indicates that the request has been successfully processed, and there is no content to return in the response body.


  
