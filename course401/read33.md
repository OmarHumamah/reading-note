# `<Login /> and <Auth />

## Why is the Context API useful?
- It allows you to pass props down multiple levels of a component tree without having to manually pass the prop each time, essentially providing a shortcut for props to grandchildren
- Context is primarily used when some data needs to be accessible by many components at different nesting levels
## Can a component outside of a provider get its context?
- To access a React context outside of the render function, we can use the useContext hook. We create the UserContext by calling the React. createContext method with a default context value. Then in the Users component, we call the useContext hook with UserContext to access the current value of UserContext.
## What are some common use cases for using the Context API?
- Passing UI Themes, local preferences, or any parameter which needs to be consumable to many different levels of components at the same time.
## Describe “Context Hell”
- Context hell is the nasty code you get taking advantage of the React Context API.
- When you have too many nested contexts… This is similar to callback hell. Can be addressed with the ‘React.cloneElement()’ function which returns a new element using the initial ‘element’ as a starting point

- `global state`: It is the data that is shared between all the components within a React application. When the state is changed, or let's say a filter is added, the components re-render accordingly.
- `global context`: It is designed to share data that can be considered “global” for a tree of React components, such as the current authenticated user, theme, or preferred language.
- `provider`: The Provider component accepts a value prop to be passed to consuming components that are descendants of this Provider. One Provider can be connected to many consumers. Providers can be nested to override values deeper within the tree.
- `consumer`: A React component that subscribes to context changes. Using this component lets you subscribe to a context within a function component.

---

## What is Role-Based Access Control (RBAC)

- Role-based access control (RBAC) restricts network access based on a person's role within an organization and has become one of the main methods for advanced access control. The roles in RBAC refer to the levels of access that employees have to the network.

- Employees are only allowed to access the information necessary to effectively perform their job duties. Access can be based on several factors, such as authority, responsibility, and job competency. In addition, access to computer resources can be limited to specific tasks such as the ability to view, create, or modify a file.

- As a result, lower-level employees usually do not have access to sensitive data if they do not need it to fulfill their responsibilities. This is especially helpful if you have many employees and use third-parties and contractors that make it difficult to closely monitor network access. Using RBAC will help in securing your company’s sensitive data and important applications.

- **EXAMPLES OF ROLE-BASED ACCESS CONTROL**

  - Management role scope – it limits what objects the role group is allowed to manage.
  - Management role group – you can add and remove members.
  - Management role – these are the types of tasks that can be performed by a specific role group.
  - Management role assignment – this links a role to a role group.

  - Other options for user access may include:
    - Primary – the primary contact for a specific account or role.
    - Billing – access for one end-user to the billing account.
    - Technical – assigned to users that perform technical tasks.
    - Administrative – access for users that perform administrative tasks.

- [(RBAC) source](https://digitalguardian.com/blog/what-role-based-access-control-rbac-examples-benefits-and-more)

- [cookies](https://www.npmjs.com/package/react-cookies)
