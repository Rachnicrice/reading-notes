# Readings: Message Queues
-------------------------------------------------

### Review, Research, and Discussion

1. What does it mean that web sockets are bidirectional? Why is this useful?
  It means that data can be transmitted back and forth. Useful so services can communicate.

2. Does socket.io use HTTP? Why?
  No it operates at the TCP level.

3. What happens when a client emits an event?
  The server hears it.

4. What happens when a server emits an event?
  The client hears it.

5. What happens if a client “misses” an event?
  It does not respond to the event.

6. How can we mitigate this?
  Not sure. Make sure the client is available to listen?

### Vocabulary Terms

Socket - An endpoint for sending and receiving data.

Web Socket - A protocol for communicating over a single TCP connection.

Socket.io - A JavaScript library for realtime web applications.

Client - The service requesting information/data.

Server - The service supplying data.

OSI Model - Open Systems Interconnection model characterises how data is communicated.

TCP Model - Transmission Control Protocol defines a suite of transmission protocols.

TCP - Transmission Control Protocol

UDP - User Datagram Protocol

Packets - A small segment of a larger message.

### Preview

1. Which 3 things had you heard about previously and now have better clarity on?
  - TCP
  - Sockets
  - OSI Model
2. Which 3 things are you hoping to learn more about in the upcoming lecture/demo?
  - Different kinds of queues
  - AWS & Socket.io
  - 
3. What are you most excited about trying to implement or see how it works?
  - Hoping that we'll get to implement an api for our service.