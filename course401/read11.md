# Event Driven Applications

## Why is access control important?

- it limit the access of users and give special permission to the admin and other permission to the guest users, etc..
- it divides the roles to the users.

## Describe an application that would need access control.

- an application to store blogs, it need special permission to write his blog and and other permission to the admin to accept the blog content then publish it. And a public permission to the guest users to read all or some of the blogs

## What is a role used for?

A role is a collection of permissions that can be divided to the users according to his tag.

## Why is role based access control more scalable than discretionary or mandatory access control?

- In role based access control you can set control for access data by the role of the user, while mandatory access control is limiting access to resources based on the sensitivity of the information that the resource contains

---

- `Authorization`: Authorization in system security is the process of giving the user permission to access a specific resource or function.
- `Role Based Access Control`: It is an approach to restricting system access to authorized users.

---

## Event Driven Applications

- It is a logical pattern that we can choose to confine our programming within to avoid issues of complexity and collision.
- Every time you interact with a webpage through it’s user interface, an event is happening. When you click a button a click event is triggered. When you press a key a keydown event is triggered. These events have associated functions that, when triggered, are executed to make a change to the user interface in some way.
- `EventEmitter`: It allows us to get started incorporating Event-Driven Programming in our project right away.
- `Removing Listeners`: If you want to remove an event listener from an event. for many reasons:- - the event is no longer needed - if an event listener references an object that is no longer needed
  [source](https://www.digitalocean.com/community/tutorials/nodejs-event-driven-programming)
