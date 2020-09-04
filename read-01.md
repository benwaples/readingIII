# Summary of Class 01 Reading

## [Promise](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Promise)
The Promise object is a representation of a given async function, telling the function to wait until the promise is fulfilled. It is either pending, fulfilled, or rejected.

Promises can be chained `.then`, or batched with `async` `await` calls.

## [Destructuring](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Destructuring_assignment)
Destructuring is the process of pulling info out of a variable.

``` js
const dogs = [
  {
    name: 'skip',
    age: 12
  },
  {
    name: 'happy',
    age: 2
  }
]
module.exports = { dogs }

import { dogs } from './dogs.js'
const [skip, happy] = dogs;

```
## [Spread](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Spread_syntax)
Spread operator `...` is used after `=` and sorta imports the previous data of the variable that follows the operator.

```js
const spot = {
  type: 'dog',
  name: 'spot',
  weight: '12'
}

const newDog = {...spot, name: 'skip'} 
// creates a newDog object that has all the same keys as spot, however the nam will change to skip.
```

## [Rest](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Functions/rest_parameters)

The Rest operator `...` is used before the the `=`. When it is passed along with a parameter (`function name(...arg){}`) the rest operator acts like a basket for all the args that the user passes at and after that position! The basket is an array tho.

## [TDD, Where did is all go wrong](https://www.youtube.com/watch?v=EZ05e7EMOLM&ab_channel=DevTernity)
I like how critical he is on TDD and brings up how TDD isn't good if done incorrectly.

## [What is the Event Loop](https://www.youtube.com/watch?v=8aGhZQkoFbQ)
Event loop is how JS manages tasks. It handles async tasks differently, it will actually pass those tasks off to other things to manage them and then has those things tell JS when they are ready to be implemented.