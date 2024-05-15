# Class 13 - Message Queues

### What does the Chat Example do?
The Chat Example shows how a system for tracking deliveries works. It uses a special way of programming called event-driven programming with something called Socket.IO. This allows for instant communication between people using the system and the main computer that manages everything. So, it helps keep everyone updated on where their deliveries are in real-time.

### What proof of life are we getting on the backend from the above app?
From the app, we're getting signals that everything is alive and working properly. So, when someone using the delivery tracking system sends updates or confirms something, the main computer knows that everything is active and running smoothly.

### What's special about the io.emit() method in Socket.IO?
This method helps send messages to everyone involved. But if you don't want one specific person to get the message, you can use a special flag called "broadcast." This way, everyone else gets the message except that one person.

### What's a room and why is it helpful?
Think of a room like a special area where only certain people can talk to each other. It's useful because you can create different rooms for different groups, like private chat rooms for friends or rooms where only team members can discuss updates.

### How do you join a room?
You can join a room by simply asking to join. It's like raising your hand and saying, "I want to be part of this group." In the delivery tracking system, you'd do this by calling the method that says "join" and telling it the name of the room you want to join.

### How do you leave a room?
Leaving a room is just like walking out of it. You let the system know you're done by calling the method that says "leave" and telling it the name of the room you want to leave.

### What's a Namespace and why do we use it?
A Namespace is like having different rooms for different purposes. It helps keep things organized by separating different parts of the system. So, you might have one Namespace for talking about deliveries and another for talking about payments.

### What can each Namespace have?
Each Namespace can have its own special areas, ways of handling events, and helpers to make things run smoothly.

### Can you think of a reason we might use separate namespaces?
Separate namespaces could be really handy for keeping different types of conversations or tasks separate. For example, we could have one namespace for talking about important stuff with administrators and another for regular users to chat and ask questions.





