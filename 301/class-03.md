map is a very usefull thing in react.  It helps render multiple components much easier than using a for loop.  The spread operator will definitely come in handy when setting State.  

### What does .map() return?
    - a new array

### If I want to loop through an array and display each value in JSX, how do I do that in React?
    - by using curley braces

### Each list item needs a unique ____.
    - key

### What is the purpose of a key?
    - to help react identify which items have changed, are added or removed


### What is the spread operator?
    - an ellipsis that expands an interable object into the list of arguments
    source: https://medium.com/coding-at-dawn/how-to-use-the-spread-operator-in-javascript-b9e4a8b06fab

### List 4 things that the spread operator can do.
    - copy an array
    - concat or combine arrays
    - add an item to an array
    - add state to react

### Give an example of using the spread operator to combine two arrays.
    const array1 = [1,2,3]
    const array2 = [3,4,5]
    const array3 = [...array1, ...array2]

### Give an example of using the spread operator to add a new item to an array.
    - const array1 = [1,2]
    - array1 = [3,4, ...array1]

### Give an example of using the spread operator to combine two objects into one.
    const obj1 = { a: 1, b: 2 }
    const obj2 = { c: 3, d: 4 }
    const combinedObj = { ...obj1, ...obj2 }
