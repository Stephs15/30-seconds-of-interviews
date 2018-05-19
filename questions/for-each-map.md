### What is the difference between a `map` loop and a `forEach` loop?

#### Answer

Both loops iterate through the elements in an array. `.map()` maps each element to new element by calling the function on each element and it returns the new array. On the other hand, `.forEach()` executes a callback function for each element but does not return anything. `.forEach()` is generally used when causing a side effect on each iteration, whereas `.map()` is a common functional programming technique.

#### Good to hear

* Use `.forEach()` if you need to iterate over an array and cause mutations to the elements without needing to return values to generate a new array.
* `.map()` is the right choice to keep data immutable where each value of the original array is mapped to a new array.

##### Additional links

* [MDN docs for forEach](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/forEach)
* [MDN docs for map](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/map)
* [JavaScript — Map vs. ForEach](https://codeburst.io/javascript-map-vs-foreach-f38111822c0f)

<!-- tags: (javascript) -->