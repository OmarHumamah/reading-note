# Context API

## Describe use cases useState() vs useReducer()
- useReducer is usually preferable to useState when you have complex state logic that involves multiple sub-values or when the next state depends on the previous one. useReducer also lets you optimize performance for components that trigger deep updates because you can pass dispatch down instead of callbacks.
- The useState() is a Hook that allows you to have state variables in functional components. React has two types of components, one is class components which are ES6 classes that extend from React and the other is functional components.

## Why do custom hooks need the use prefix?
- This is mainly to have an extra option for sharing state and logic between components. ... Custom hooks are normal JS functions, named with the prefix 'use', that can use hooks inside of it and contain a common stateful logic to be reused in other components.

## What do custom hooks usually do?
- Custom hooks allow us to have cleaner functional components, remove logic from the UI layer, and prevent code duplication by bringing common use cases to reusable hooks.

## Using any list of custom hooks, research and name one that you think will be useful in your applications
1. useClippy A hook for copying data to the clipboard and retrieving/pasting it using Ctrl-C/Command-C and Ctrl-V/Command-V.

2. useBrowserContextCommunication useBrowserContextCommunication uses the Broadcast Channel API to deliver an easy solution for communication between different browser contexts (tabs, iframes, windows)

3. useScript is a hook for loading (and notifying when they’re loaded) external scripts, dynamically.

## Describe how a hook that fetches API data might work
- Put the fetchData function above in the useEffect hook and call it, like so: useEffect(() => { const url = "https://api.adviceslip.com/advice"; const fetchData = async () => { try { const response = await fetch(url); const json = await response. json(); console. log(json); } catch (error) { console.

---

- `reducer`: It is one of the additional Hooks that shipped with React 16.8. An alternative to the useState Hook, it helps you manage complex state logic in React application.

---

## Context

- Context provides a way to pass data through the component tree without having to pass props down manually at every level.

- **When to Use Context**
  - Context is designed to share data that can be considered “global” for a tree of React components, such as the current authenticated user, theme, or preferred language