# Code 301 
## Class 1

Do not plagiarize.
Make sure to give proper attribution to sources tyou draw from for your projects
"____ helped with ____"
Add it to your README, or a collab.md doc in your repo

Never copy and paste

If I copy code from an article or anything, link the source to the copy. If I reference mulitple times, add article to README and then reference it in my notes.


### Partner Power Hour
- The people presenting are hiring. 
- Connect with them on LinkedIn (messages save).


### EQ
- High emotional intelligence earns $10-$20k more. It's important


### Bias

#### Implicit Bias
- In group/out group- Favor those who belong to your group
- GroupThink - you let the social dynamics of a group override the best outcomes.
- Biases are the stories we've made up about people before we know who they really are.
        Who is missing in your circle? 
        Diversity is good




## Setup
**Method** is a function that lives inside of an object

**forEach()** is a method that calls a provided function at each index of an array on the element at that index.
```js
arry.forEach(callback(currentValue[, index[, array]]){
    //executes something
}


// Currying: passing a function to another function. We often currey callback functions.
element.addEventListener('click', function(event){});

const arr = ['a', 'b', 'c'];

arr.forEach(callback)

function callbackthis(valuethis, indexthis){console.log(valuethis)};
                    //paraments, we can chose them

    //calls callback once for each element
    //console.log 'a', 'b', and also 'c'


arr.forEach(function(v, i, a){
        console.log('value', v);
        console.log('index', i);
        console.log('array', a);
    })

    // same as the following

for(let i =0; i < arr.length; i++) {
    callbackthis(arr[i], i, arr);
}


// Example:
const nums  [5, 6, 7];

nums.forEach(multiplyByIndex);

function multiplyByIndex)number, index){ //number and index are parameters
    console.log(number * index);
}


```

