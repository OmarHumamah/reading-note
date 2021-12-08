# Advanced State with Reducers

## How can we ensure that an effect hook runs only once?
- It can be done by use empty array parameter [] as a second parameter, like this it will be rendered on time on (unmount and mount component).
## Can useState() update more than one state variable at the same time?
- To update the component's state invoke the updater function setState(newState) with the new state. The component re-renders and state receives the new value newState.,Invoking the state updater function setState(newState) with the new value updates the state.
## Is useState() synchronous?
- useState and setState both are asynchronous.,They do not update the state immediately but have queues that are used to update the state object.

---

- `State Hook`: A Hook is a special function that lets you “hook into” React features. And useState is a Hook that lets you add React state to function components.
- `Component Lifecycle`: Components are created (mounted on the DOM), grow by updating, and then die (unmount on DOM). This is referred to as a component lifecycle.

---

## useReducer hook

- An alternative to useState. Accepts a reducer of type (state, action) => newState, and returns the current state paired with a dispatch method. (If you’re familiar with Redux, you already know how this works.)

- useReducer is usually preferable to useState when you have complex state logic that involves multiple sub-values or when the next state depends on the previous one. useReducer also lets you optimize performance for components that trigger deep updates because you can pass dispatch down instead of callbacks.

- [source](https://reactjs.org/docs/hooks-reference.html#usereducer)
- [source](https://blog.logrocket.com/guide-to-react-usereducer-hook/)