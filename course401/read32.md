# Context API - Behaviors

## When you have multiple contexts, what component type should you use (class/function) and why?
- Both Ways Can used In class components, the render method will be called, whenever the state of the components changes. On the other hand, the Functional components render the UI based on the props. Class Components should be preferred whenever we have the requirement with the state of the component.

## What are some good use cases for using the Context API for global state?
- Context is primarily used when some data needs to be accessible by many components at different nesting levels

## How can you best test context?
- The best way to test Context is to make our tests unaware of its existence and avoiding mocks. We want to test our components in the same way that developers would use them (behavioral testing) and mimic the way they would run in our applications (integration testing).

---

- `context`: It is designed to share data that can be considered “global” for a tree of React components, such as the current authenticated user, theme, or preferred language. For example, in the code below we manually thread through a “theme” prop in order to style the Button component: class App extends React.
- `useContext()`: It is used to create common data that can be accessed throughout the component hierarchy without passing the props down manually to each level. Context defined will be available to all the child components without involving “props”.
- `static context`: It belongs to the class and these will be loaded into the memory along with the class. You can invoke static methods without creating an object.

---

## Context

- Context provides a way to pass data through the component tree without having to pass props down manually at every level.

- **When to Use Context**
  - Context is designed to share data that can be considered “global” for a tree of React components, such as the current authenticated user, theme, or preferred language

  