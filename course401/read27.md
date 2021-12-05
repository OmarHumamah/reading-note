# useState() Hook

## How does React differ from vanilla JS/HTML/CSS?
- Plain JS apps usually start with the initial UI created on the server (as HTML), whereas React apps start with a blank HTML page, and dynamically create the initial state in JavaScript. React requires you to break your UI into components, but plain JS apps can be structured in any way you see fit.
- react uses JSX 
## What is the primary difference between a function component and a class component?
- A functional component is just a plain JavaScript function that accepts props as an argument and returns a React element. A class component requires you to extend from React. Component and create a render function which returns a React element. There is no render method used in functional components.

---

- `Functional Components`: It is just a plain JavaScript function that accepts props as an argument and returns a React element.
- `Children / Child Components`: It is a component that allows you to pass data to other component and you can render it in the parent component many times.

---

## hocks

### Why Hooks?
- We know that components and top-down data flow help us organize a large UI into small, independent, reusable pieces. However, we often can’t break complex components down any further because the logic is stateful and can’t be extracted to a function or another component. Sometimes that’s what people mean when they say React doesn’t let them “separate concerns.”
These cases are very common and include animations, form handling, connecting to external data sources, and many other things we want to do from our components. When we try to solve these use cases with components alone.
- We think Hooks are our best shot at solving all of these problems. Hooks let us organize the logic inside a component into reusable isolated units.

- [source](https://medium.com/@dan_abramov/making-sense-of-react-hooks-fdbde8803889)

### Using the State Hook

- **What does calling useState do?** 
    - It declares a “state variable”. Our variable is called count but we could call it anything else, like banana. This is a way to “preserve” some values between the function calls — useState is a new way to use the exact same capabilities that this.state provides in a class. Normally, variables “disappear” when the function exits but state variables are preserved by React.

- **What do we pass to useState as an argument?**
    - The only argument to the useState() Hook is the initial state. Unlike with classes, the state doesn’t have to be an object. We can keep a number or a string if that’s all we need. In our example, we just want a number for how many times the user clicked, so pass 0 as initial state for our variable. (If we wanted to store two different values in state, we would call useState() twice.)

- **What does useState return?**
    - It returns a pair of values: the current state and a function that updates it. This is why we write const [count, setCount] = useState(). This is similar to this.state.count and this.setState in a class, except you get them in a pair. If you’re not familiar with the syntax we used, we’ll come back to it at the bottom of this page.
- [source](https://reactjs.org/docs/hooks-state.html)

### additional sources
- [Hooks API Reference](https://reactjs.org/docs/hooks-reference.html)
- [Hooks at a Glance](https://reactjs.org/docs/hooks-overview.html)