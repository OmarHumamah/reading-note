# React and Forms

## React Docs - Forms
* What is a ‘Controlled Component’?
    - In HTML, form elements such as `<input>`, `<textarea>`, and `<select>` typically maintain their own state and update it based on user input. In React, mutable state is typically kept in the state property of components, and only updated with setState().
    
    - We can combine the two by making the React state be the “single source of truth”. Then the React component that renders a form also controls what happens in that form on subsequent user input. An input form element whose value is controlled by React in this way is called a “controlled component”.
* Should we wait to store the users responses from the form into state when they submit the form OR should we update the state with their responses as soon as they enter them? Why.
 I DIDN'T UNDERSTAND => ( **Things I want to know more about** )
* How do we target what the user is entering if we have an event handler on an input field?
 I DIDN'T UNDERSTAND => ( **Things I want to know more about** )


## The Conditional (Ternary) Operator Explained
* Why would we use a ternary operator?
    - To create an if statement in shorter and cleaner way. 
* Rewrite the following statement using a ternary statement:
    >`if(x===y){`

    >`console.log(true);`
    
    >`} else {`
    
    >`console.log(false);`
    
    >`}`

    `V V V V (IN TO Ternary) V V V V`

    **`x === y ? console.log(true) : console.log(false)`**

    *[source](https://codeburst.io/javascript-the-conditional-ternary-operator-explained-cac7218beeff)*

**-------------------------------------------------------------------------------**  

## Things I want to know more about

* Should we wait to store the users responses from the form into state when they submit the form OR should we update the state with their responses as soon as they enter them? Why.

* How do we target what the user is entering if we have an event handler on an input field?

**[Back to: Homepage](https://omarhumamah.github.io/reading-note/).**