# Passing Functions as Props

## React Docs - lists and keys

1. What does .map() return?
-- .map() returns an array.

2. If I want to loop through an array and display each value in JSX, how do I do that in React?
-- It can be done with the following code:
```
const numbers = [1, 2, 3, 4, 5];
const listItems = numbers.map((number) =>
  <li>{number}</li>
);
```
```
function NumberList(props) {
  const numbers = props.numbers;
  return (
    <ul>
      {numbers.map((number) =>
        <ListItem key={number.toString()}
                  value={number} />
      )}
    </ul>
  );
}
```
source: https://reactjs.org/docs/lists-and-keys.html

3. Each list item needs a unique ____.
-- Key

4. What is the purpose of a key?
-- A key is there to help React figure out which list items have been changed, added or removed.

## The Spread Operator

1. What is the spread operator?
-- it is:
```
...
```

2. List 4 things that the spread operator can do.
-- It is capable of:
```
Copying an array
Concatenating or combining arrays
Using Math functions
Using an array as arguments
Adding an item to a list
Adding to state in React
Combining objects
Converting NodeList to an array
```

3. Give an example of using the spread operator to combine two arrays.
--
```
let arr1 = [1, 2]
let arr2 = [3, 4]
let arr3 = [...arr1, ...arr2]
```

4. Give an example of using the spread operator to add a new item to an array.
--
```
let arr1 = [1, 2]
let arr2 = [0, ...arr1]
```

5. Give an example of using the spread operator to combine two objects into one.
--
```
const objectOne = {hello: "🤪"}
const objectTwo = {world: "🐻"}
const objectThree = {...objectOne, ...objectTwo, laugh: "😂"}
console.log(objectThree) // Object { hello: "🤪", world: "🐻", laugh: "😂" }
```
source: https://medium.com/coding-at-dawn/how-to-use-the-spread-operator-in-javascript-b9e4a8b06fab

## How to Pass Functions Between Components

1. In the video, what is the first step that the developer does to pass functions between components?
-- He creates a function that takes in an object from state, he then adds the method to the button click.

2. In your own words, what does the increment function do?
-- The increment function adds 1 to the count variable within state.

3. How can you pass a method from a parent component into a child component?
-- This part of the video got pretty confusing for me... 

4. How does the child component invoke a method that was passed to it from a parent component?
-- This part of the video got pretty confusing for me...