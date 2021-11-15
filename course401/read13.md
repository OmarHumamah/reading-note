# Message Queues

## What does it mean that web sockets are bidirectional? Why is this useful?
- It is relies on client request and respond from server.
- This enables the server to send real-time updates asynchronously, without requiring the client to submit a request each time.
## Does socket.io use HTTP? Why?
- Websocket is created when you make upgrade from http to websocket, so it kind of does need http. socket.io isn't a pure Websocket server/implementation, it depends on HTTP for its initial connection setup.
## What happens when a client emits an event?
-  The call back function that in in the event will be executed. the client become connected to the server.  
## What happens when a server emits an event?
- the event will be executed to all the clients.
## What happens if a client “misses” an event?
- the function will be false or Ignored.
## How can we mitigate this?
- make well connection between the server and the client.

--- 

- `Socket`: It is one endpoint of a two-way communication link between two programs running on the network.
- `Web Socket`: It is a computer communications protocol, providing full-duplex communication channels over a single TCP connection.
- `Socket.io`: It is a library that enables real-time, bidirectional and event-based communication between the browser and the server.
- `Client`: It is user-facing computers that run software to make requests to servers, and either interpret or display the responses. In particular, a client sends a request to the server.
- `Server`: It is a computer or system that provides resources, data, services, or programs to other computers or clients.
- `OSI Model`: It is The Open Systems Interconnection model is a conceptual model that characterizes and standardizes the communication functions of a telecommunication or computing system without regard to its underlying internal structure and technology
- `TCP Model`: It is a standard that defines how to establish and maintain a network conversation by which applications can exchange data.
- `TCP`: It is stands for Transmission Control Protocol
- `UDP`: It is stands for User Datagram Protocol, or UDP, is a communication protocol used across the Internet for especially time-sensitive transmissions such as video playback or DNS lookups.
- `Packets`: It is like a container for the messages but in pref shape.
