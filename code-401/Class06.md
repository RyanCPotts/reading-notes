# Class 06 REST

### Who is Roy Fielding?
Roy Fielding is a computer scientist and one of the principal authors of the HTTP specification and the REST architectural style. He is best known for his work on REST (Representational State Transfer), which he introduced in his doctoral dissertation while studying at the University of California, Irvine.

Fielding's dissertation, titled "Architectural Styles and the Design of Network-based Software Architectures," presented REST as an architectural style for distributed hypermedia systems, particularly emphasizing its applicability to the World Wide Web. In this dissertation, he outlined the principles and constraints of REST, which have since become fundamental to the design of web APIs and distributed systems.

REST, as defined by Fielding, emphasizes a stateless client-server architecture, where communication is achieved through standardized operations (such as HTTP methods like GET, POST, PUT, DELETE) and representations of resources (typically in formats like JSON or XML). It promotes scalability, performance, and simplicity in designing networked applications.

Fielding's contributions to REST have had a profound impact on the development of the modern web, influencing the design of web APIs, cloud computing architectures, and distributed systems. His work has helped establish REST as one of the primary architectural styles for building scalable and interoperable web services.

In addition to his academic research, Roy Fielding has also been involved in various industry projects and initiatives related to web standards and protocols. He continues to be an influential figure in the field of computer science, particularly in areas related to web architecture and network protocols.

### Why don’t the techniques that we use in this class work well when we need to be able to talk to all of the machines in the world?
The techniques used in a class or a closed environment may not work well when trying to communicate with all machines in the world due to several reasons:

Scale: In a class or a closed environment, the number of machines or devices is limited and known in advance. However, when communicating with all machines in the world, the scale increases exponentially. Managing and coordinating communication with billions of devices distributed worldwide poses significant challenges in terms of scalability.
Heterogeneity: Machines in the real world vary significantly in terms of hardware, software, protocols, and capabilities. Unlike in a controlled environment where all machines may be standardized, the diversity of devices worldwide requires accommodating different platforms, operating systems, network configurations, and communication protocols.
Connectivity: In a closed environment, machines are typically connected to the same local network or controlled infrastructure, facilitating communication. However, reaching machines globally requires dealing with diverse network infrastructures, including wired, wireless, cellular, satellite, and other technologies. Ensuring reliable connectivity across different network environments is complex and challenging.
Security and Privacy: When communicating with machines globally, security and privacy considerations become paramount. In a closed environment, security measures may be relatively easier to implement and manage. However, in the open and distributed nature of the internet, there are various security threats, including unauthorized access, data breaches, malware, and other attacks. Safeguarding communication while respecting user privacy becomes a critical concern.
Interoperability: Achieving interoperability, the ability of different systems to communicate and work together effectively, becomes more challenging when dealing with machines worldwide. Ensuring compatibility and seamless communication across diverse platforms, languages, and standards requires robust protocols, standards, and frameworks.
Reliability and Resilience: In a closed environment, reliability and resilience can be easier to maintain due to controlled conditions. However, when communicating globally, factors such as network congestion, latency, packet loss, and hardware failures become more prevalent. Implementing mechanisms for fault tolerance, redundancy, and load balancing becomes essential to ensure reliable and resilient communication.
Overall, while the techniques used in a class or a closed environment may provide a foundation for understanding networking concepts, addressing the complexities of global communication requires specialized knowledge, tools, and strategies tailored to the challenges of the real world.

### What is the HTTP protocol that Fielding and his friends created?
HTTP (Hypertext Transfer Protocol) is a fundamental protocol for web communication. Roy Fielding was a key contributor to HTTP's development, particularly in authoring the HTTP/1.1 specification. HTTP facilitates clients, like web browsers, requesting resources from servers and receiving responses. It operates over TCP/IP and uses methods (e.g., GET, POST) and status codes (e.g., 200 OK) to define actions and outcomes. Fielding's work on REST influenced HTTP's design principles. While HTTP has evolved through collaboration, Fielding's contributions have significantly shaped its development.

### What does a GET do?
A GET request is a type of HTTP request method used by clients (such as web browsers) to retrieve resources from a server. When a client sends a GET request to a server, it is asking the server to provide a specific resource identified by a URL (Uniform Resource Locator).

### What does a POST do?
A POST request is a type of HTTP request method used by clients (such as web browsers) to submit data to a server for processing or storage. Unlike a GET request, which retrieves data from a server, a POST request sends data to a server to be processed in some way.

### What does PUT do?
A PUT request is a type of HTTP request method used by clients (such as web browsers) to update or replace an existing resource on a server with the provided data. It is similar to a POST request but typically used for updating existing resources rather than creating new ones.

### What does PATCH do?
A PATCH request is a type of HTTP request method used by clients (such as web browsers) to make partial updates to an existing resource on a server. Unlike PUT requests, which typically replace the entire resource with new data, PATCH requests are used to apply partial modifications to a resource.
