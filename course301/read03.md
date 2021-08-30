# Passing Functions as Props

## React Docs - lists and keys
* What does .map() return?
    - loop through array and return element as the length of the array.  
* If I want to loop through an array and display each value in JSX, how do I do that in React?
    - you can do it by using map
* Each list item needs a unique `Key`.
* What is the purpose of a key?
    - Keys help React identify which items have changed, are added, or are removed. Keys should be given to the elements inside the array to give the elements a stable identity.

    *[source](https://reactjs.org/docs/lists-and-keys.html)*

## The Spread Operator

* What is the spread operator?
    - In JavaScript, spread syntax refers to the use of an ellipsis of three dots (…) to expand an iterable object into the list of arguments.
* List 4 things that the spread operator can do.
    - Copying an array
    - Concatenating or combining arrays
    - Using Math functions
    - Using an array as arguments
* Give an example of using the spread operator to combine two arrays.
    > const myArray = [`🤪`,`🐻`,`🎌`]

    > const yourArray = [`🙂`,`🤗`,`🤩`]

    > const ourArray = [...myArray,...yourArray]

    > console.log(...ourArray) // 🤪 🐻 🎌 🙂 🤗 🤩

* Give an example of using the spread operator to add a new item to an array.
    > const fewFruit = ['🍏','🍊','🍌']

    > const fewMoreFruit = ['🍉', '🍍', ...fewFruit]

    > console.log(fewMoreFruit) //  Array(5) [ "🍉", "🍍", "🍏", "🍊", "🍌" ]

* Give an example of using the spread operator to combine two objects into one.
    > const objectOne = {hello: "🤪"}
    > const objectTwo = {world: "🐻"}
    > const objectThree = {...objectOne, ...objectTwo, laugh: "😂"}
    > console.log(objectThree) // Object { hello: "🤪", world: "🐻", laugh: "😂" }

[source](https://medium.com/coding-at-dawn/how-to-use-the-spread-operator-in-javascript-b9e4a8b06fab)

## How to Pass Functions Between Components
[![IMAGE_ALT](https://img.youtube.com/vi/c05OL7XbwXU/0.jpg/default.jpg)](https://www.youtube.com/watch?v=c05OL7XbwXU)
* In the video, what is the first step that the developer does to pass functions between components?
* In your own words, what does the increment function do?
* How can you pass a method from a parent component into a child component?
* How does the child component invoke a method that was passed to it from a parent component?