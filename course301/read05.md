# React Docs - thinking in React
* How would you break a mock into a component heirarchy?
    - By draw boxes around every component (and subcomponent) in the mock and give them all names. If you’re working with a designer, they may have already done this, so go talk to them! Their Photoshop layer names may end up being the names of your React components!

* What is the single responsibility principle and how does it apply to components?
    - that is, a component should ideally only do one thing. If it ends up growing, it should be decomposed into smaller subcomponents.
* What does it mean to build a ‘static’ version of your application?
    - It is too build an initial  version of the app to render components that reuse other components and pass data using props in one JS page.
* Once you have a static application, what do you need to add?
    - To make your UI interactive, you need to be able to trigger changes to your underlying data model. React achieves this with state.
* What are the three questions you can ask to determine if something is state?
    - Is it passed in from a parent via props? If so, it probably isn’t state.
    - Does it remain unchanged over time? If so, it probably isn’t state.
    - Can you compute it based on any other state or props in your component? If so, it isn’t state.
* How can you identify where state needs to live?
    -  State is reserved only for interactivity, that is, data that changes over time. Since the app is a static version, you don’t need it.

[source](https://reactjs.org/docs/thinking-in-react.html)

**[Back to: Homepage](https://omarhumamah.github.io/reading-note/).**