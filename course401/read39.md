# Redux - Additional Topics

## What’s the best practice for “pre-loading” data into the store (on application start) in a Redux application?
- Best practice would be to fire off an api call from a useEffect() call on pageload. Because this is asynchronous, this will require Thunk middleware. You may then use mapStateToProps() to assign the returned data to props which can be passed to the component in question. 
## When using a thunk/async action that dispatches the actual action, which do you export from your reducer?
- The most common use case for Redux Thunk is for communicating asynchronously with an external API to retrieve or save data. Redux Thunk makes it easy to dispatch actions that follow the lifecycle of a request to an external API.

--- 

- `middleware`: It is a code that runs between two functions, in the case of redux, code that is wrapped between our createStore() function and our connect() function. 
- `thunk`: It is a middleware that lets you call action creators that return a function instead of an action object.

---

## Redux Toolkit (RTK) 
- [overview](https://redux-toolkit.js.org/tutorials/overview)
- [quick-start](https://redux-toolkit.js.org/tutorials/quick-start)

## MobX
- MobX is a simple, scalable and battle tested state management solution. This tutorial will teach you all the important concepts of MobX in ten minutes. MobX is a standalone library, but most people are using it with React and this tutorial focuses on that combination.
- ![](https://mobx.js.org/assets/getting-started-assets/overview.png)
 
-[source](https://mobx.js.org/getting-started.html) 

## Hookstate
- Hookstate is a small and yet fast and flexible state management tool based on React and Hooks. Hookstate is simple and easy to learn with a pragmatic and flexible API. Even though Hookstate is small, it comes with some good developer-friendly features. 

- [getting-started](https://hookstate.js.org/docs/getting-started)