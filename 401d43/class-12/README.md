# Readings: Event Driven Applications
-------------------------------------------------

### Review, Research, and Discussion

1. What is the benefit of transforming data into packets?
  More cost effective

2. UDP is often refereed to as a connectionless protocol. Why is this?
  A connection does not need to exist between the sender and reciever.

3. Can a socket server application have multiple socket connections?
  Yes.

4. Can a socket connection application be connected to multiple socket servers?
  Yes.

5. Can an application be both a socket server and a socket connection?
  No.

### Vocabulary Terms

Observer Pattern - A software design pattern in which a subject, maintains a list of its 'observers' and notifies them automatically of any state changes.

Listener -  A function that waits for an event to occur.

Event Handler - A function that executes when a specific event occurs.

Event Driven Programming - A programming paradigm in which the flow of the program is determined by events.

Event Loop - A design pattern that waits for events in a program and then executes related code.

Event Queue - A queue of events in the order in which they occur.

Call Stack - A stack of functions added in the order in which they were recieved and then executed in a first-in last-out pattern.

Emit/Raise/Trigger - Executers of certain functions.

Subscribe - A part of the messaging pattern. 'Subscribing' to a service starts an event loop where the subscriber listens for messages or events from the subscribed to service.

database - An organized collection of data.

### Preview

1. Which 3 things had you heard about previously and now have better clarity on?
  - UDP
  - Socket.io
  - Subscribe
2. Which 3 things are you hoping to learn more about in the upcoming lecture/demo?
  - Event Driven Programming
  - Benefits of data packets
  - Conectionless Protocols
3. What are you most excited about trying to implement or see how it works?
  - Just excited to dig more into socket.io and it's capabilities