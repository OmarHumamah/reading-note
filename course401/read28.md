# Component Lifecycle

## Why do we not need more .html pages in a multi-page React app?

- because react use only on html page and make it dynamic by using DOM and JSX, when we make multi-page in react we actually making a single page and the multi-pages are components that mount and unmount by using `<BrowserRouter />` and `<Route />`.

## If we wanted a component to show up on every page, where would we put it and why?

- Inside the `<BrowserRouter />`, outside a `<Route />`
  - because the `<Route />` is for other react pages/components using exact path.

## What does routing do with the components that were rendered when a new route is requested

- It do unmount to the component which is removing it from the DOM

## What does props.children contain?

- it contains the data that we want to pass throw other components.

## How do useState() and this.setState() differ?

- useState() is for hocks that take inside it an array of to element, the first index is the value and the second element is a callback function to change the value. and this.setState() is for class it change the the constructor object values.

---

- `State Hook`: A Hook is a special function that lets you “hook into” React features. And useState is a Hook that lets you add React state to function components.
- `Mounting and Un-Mounting`: mounting is adding or loading components to the DOM, un-mounting is removing them from the DOM.

---

## Using the Effect Hook

- **What does useEffect do?**

  - By using this Hook, you tell React that your component needs to do something after render. React will remember the function you passed (we’ll refer to it as our “effect”), and call it later after performing the DOM updates. In this effect, we set the document title, but we could also perform data fetching or call some other imperative API.

- **Why is useEffect called inside a component?**

  - Placing useEffect inside the component lets us access the count state variable (or any props) right from the effect. We don’t need a special API to read it — it’s already in the function scope. Hooks embrace JavaScript closures and avoid introducing React-specific APIs where JavaScript already provides a solution.

- **Does useEffect run after every render?**

  - Yes! By default, it runs both after the first render and after every update. (We will later talk about how to customize this.) Instead of thinking in terms of “mounting” and “updating”, you might find it easier to think that effects happen “after render”. React guarantees the DOM has been updated by the time it runs the effects.

- [source](https://reactjs.org/docs/hooks-effect.html)
