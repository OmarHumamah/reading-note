# Socket.io

## What is the benefit of transforming data into packets?
- TDM-based networks must transform into packet-based networks to meet the demands of pervasive data-centric applications and services.
- Packet-based networks not only enable new innovations, services, and business opportunities, they are also the most cost-effective, efficient, and scalable networks for content delivery.
## UDP is often refereed to as a connectedness protocol. Why is this?
- because No connection needs to be established between the source and destination before you transmit data.
- UDP does not have a mechanism to make sure that the payload is not corrupted. As a result, the application must take care of data integrity all by itself.
## Can a socket connection application be connected to multiple socket servers?
- A socket that has been established as a server can accept connection requests from multiple clients.
- By default, a single server can handle 65,536 socket connections just because it's the max number of TCP ports available.
## Can an application be both a socket server and a socket connection?
- You can not combine server and client sockets into one, because a TCP/IP connection goes from a source port to a destination port, with each having unique port numbers.

--- 

- `Observer Pattern`: The observer pattern is a software design pattern in which an object, named the subject, maintains a list of its dependents, called observers, and notifies them automatically of any state changes, usually by calling one of their methods.
- `Listener`: Often an event listener is registered with the object that generates the event. When the event occurs, the object iterates through all listeners registered with it informing them of the event.
- `Event Handler`: Events are signals fired inside the browser window that notify of changes in the browser or operating system environment. Programmers can create event handler code that will run when an event fires, allowing web pages to respond appropriately to change.
- `Event Driven Programming`: It is a logical pattern that we can choose to confine our programming within to avoid issues of complexity and collision.
- `Event Loop`: It is a programming construct or design pattern that waits for and dispatches events or messages in a program. The event loop works by making a request to some internal or external "event provider", then calls the relevant event handler.
- `Event Queue`: It is a repository where events from an application are held prior to being processed by a receiving program or system. Event queues are often used in the context of an enterprise messaging system
- `Call Stack`: It is a stack data structure that stores information about the active subroutines of a computer program. This kind of stack is also known as an execution stack, program stack, control stack, run-time stack, or machine stack, and is often shortened to just "the stack".
- `Emit/Raise/Trigger`: to call an event in event driven programming. 
- `database`: It is an organized collection of data stored and accessed electronically from a computer system. Where databases are more complex they are often developed using formal design and modeling techniques.

