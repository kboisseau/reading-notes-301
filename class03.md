# Code 301 
## Class 3


### Lab 3 tips: 
  map function takes an array of numbers and doubles their values, we do this by assgning 
  the new array returned by map() to the variable doubled and then logging it.
  
  const numbers = [1, 2, 3, 4, 5];
const doubled = numbers.map((number) => number * 2);
console.log(doubled);

We can return a <li> element for each item. we will assign the resulting array elements to listItems
  
  const numbers = [1, 2, 3, 4, 5];
const listItems = numbers.map((number) =>
  <li>{number}</li>
);
Each list item needs a unique component.
  
Keys help react identify which items have changed, are added,or are removed. they should be given to the 
elements inside the array to give the elements a stable identity:

## What is the spread operator?
  In javascript .spread syntax refers to the use of an ellipsis of three dots (...) to expand
  an interable object into the list of proposed arguments.
 
 Spread operator can :
     Copy an array,
     Use An array as arguments,
     Combining objects,
     Adding to state in React

An example of an spread operator combining two arrays, also known as array conactenation:

const myArray = [`ðĪŠ`,`ðŧ`,`ð`]
const yourArray = [`ð`,`ðĪ`,`ðĪĐ`]
const ourArray = [...myArray,...yourArray]
console.log(...ourArray) // ðĪŠ ðŧ ð ð ðĪ ðĪĐ

An example of spread operator adding a new item to an array:

const fewFruit = ['ð','ð','ð']
const fewMoreFruit = ['ð', 'ð', ...fewFruit]
console.log(fewMoreFruit) //  Array(5) [ "ð", "ð", "ð", "ð", "ð" ]

An example of the spread operator combining two objects into one:

const objectOne = {hello: "ðĪŠ"}
const objectTwo = {world: "ðŧ"}
const objectThree = {...objectOne, ...objectTwo, laugh: "ð"}
console.log(objectThree) // Object { hello: "ðĪŠ", world: "ðŧ", laugh: "ð" }
const objectFour = {...objectOne, ...objectTwo, laugh: () => {console.log("ð".repeat(5))}}
objectFour.laugh() // ððððð
