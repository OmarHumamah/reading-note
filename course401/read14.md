# Event Driven Architecture

## What’s the difference between a FIFO and a standard queue?

- Standard queues provide at-least-once delivery, which means that each message is delivered at least once. FIFO queues provide exactly-once processing, which means that each message is delivered once and remains available until a consumer processes it and deletes it.
- Standard queues allow nearly-unlimited number of transactions per second. FIFO queues allow to process up to 3000 messages per second per API action.

## How can the server be assured a message was properly received?

- the receiver send a notification to the server that the message is received and emit a function to delete the message from the queue.

## What classic design pattern is best represented by event driven programming?

- It is the Observer pattern
- The observer pattern is a software design pattern in which an object, named the subject, maintains a list of its dependents, called observers, and notifies them automatically of any state changes, usually by calling one of their methods.

## How do you test an event driven system?

1. Ensure supporting topics exist.
2. Start the application under test
3. Send some input events.
4. Wait until the application has finished processing the test input.
5. Assert that it looks right.

---

- `FIFO Queue`: It is a collection of entities that are maintained in a sequence and can be modified by the addition of entities at one end of the sequence and the removal of entities from the other end of the sequence. This means that the first item in the queue will be the first item out of the queue.

- `Pub/Sub`: It is stands for Publisher/Subscriber. It allows services to communicate asynchronously, with latencies on the order of 100 milliseconds. It enables you to create systems of event producers and consumers, called publishers and subscribers

---

## Preparation Materials

[![Watch the video](https://img.youtube.com/vi/mXk0MNjlO7A/maxresdefault.jpg)](https://youtu.be/mXk0MNjlO7A)
