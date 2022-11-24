# Exam-2-js

## JavaScript

#### Q1. Which operator returns true if the two compared values are not equal?

- [ ] `<>`
- [ ] `~`
- [ ] `==!`
- [ ] `!==`


#### Q2. How is a forEach statement different from a for statement?

- [ ] Only a for statement uses a callback function.
- [ ] A for statement is generic, but a forEach statement can be used only with an array.
- [ ] Only a forEach statement lets you specify your own iterator.
- [ ] A forEach statement is generic, but a for statement can be used only with an array.


#### Q3. Review the code below. Which statement calls the addTax function and passes 50 as an argument? How would you use this function to find out how much tax should be paid on \$50?

```js
function addTax(total) {
  return total * 1.05;
}
```

- [ ] `addTax = 50;`
- [ ] `return addTax 50;`
- [ ] `addTax(50);`
- [ ] `addTax 50;`


#### Q6. When would the final statement in the code shown be logged to the console? When would 'results shown' be logged to the console?

```js
let modal = document.querySelector('#result');
setTimeout(function () {
  modal.classList.remove('hidden');
}, 10000);
console.log('Results shown');
```

- [ ] after 10 second
- [ ] after results are received from the HTTP request
- [ ] after 10000 seconds
- [ ] immediately

 
#### Q8. You've written the code shown to log a set of consecutive values, but it instead results in the value 5, 5, 5, and 5 being logged to the console. Which revised version of the code would result in the value 1, 2, 3 and 4 being logged?

```javascript
for (var i = 1; i <= 4; i++) {
  setTimeout(function () {
    console.log(i);
  }, i * 10000);
}
```

- [ ]

```javascript
for (var i = 1; i <= 4; i++) {
  (function (i) {
    setTimeout(function () {
      console.log(j);
    }, j * 1000);
  })(j);
}
```

- [ ]

```javascript
while (var i=1; i<=4; i++) {
  setTimeout(function() {
    console.log(i);
    }, i*1000);
}
```

- [ ]

```javascript
for (var i = 1; i <= 4; i++) {
  (function (j) {
    setTimeout(function () {
      console.log(j);
    }, j * 1000);
  })(i);
}
```

- [ ]

```javascript
for (var j = 1; j <= 4; j++) {
  setTimeout(function () {
    console.log(j);
  }, j * 1000);
}
```

#### Q9. How does a function create a closure?

- [ ] It reloads the document whenever the value changes.
- [ ] It returns a reference to a variable in its parent scope.
- [ ] It completes execution without returning.
- [ ] It copies a local variable to the global scope.


#### Q16. Which property references the DOM object that dispatched an event?

- [ ] `self`
- [ ] `object`
- [ ] `target`
- [ ] `source`


#### Q18. Which method converts JSON data to a JavaScript object?

- [ ] `JSON.fromString();`
- [ ] `JSON.parse()`
- [ ] `JSON.toObject()`
- [ ] `JSON.stringify()`

#### Q19. When would you use a conditional statement?

- [ ] When you want to reuse a set of statements multiple times.
- [ ] When you want your code to choose between multiple options.
- [ ] When you want to group data together.
- [ ] When you want to loop through a group of statement.


#### Q21. Which Object method returns an iterable that can be used to iterate over the properties of an object?

- [ ] `Object.get()`
- [ ] `Object.loop()`
- [ ] `Object.each()`
- [ ] `Object.keys()`


#### Q22. What will be logged to the console?

```js
var a = ['dog', 'cat', 'hen'];
a[100] = 'fox';
console.log(a.length);
```

- [ ] 101
- [ ] 3
- [ ] 4
- [ ] 100


#### Q29. Which Variable-defining keyword allows its variable to be accessed (as undefined) before the line that defines it?

- [ ] all of them
- [ ] `const`
- [ ] `var`
- [ ] `let`


#### Q30. Which of the following values is not a Boolean false?

- [ ] `Boolean(0)`
- [ ] `Boolean("")`
- [ ] `Boolean(NaN)`
- [ ] `Boolean("false")`


#### Q32. Which variable is an implicit parameter for every function in JavaScript?

- [ ] Arguments
- [ ] args
- [ ] argsArray
- [ ] argumentsList



#### Q34. What is the result of running this code?

```js
sum(10, 20);
diff(10, 20);
function sum(x, y) {
  return x + y;
}

let diff = function (x, y) {
  return x - y;
};
```

- [ ] 30, ReferenceError, 30, -10
- [ ] 30, ReferenceError
- [ ] 30, -10
- [ ] ReferenceError, -10


#### Q35. Why is it usually better to work with Objects instead of Arrays to store a collection of records?

- [ ] Objects are more efficient in terms of storage.
- [ ] Adding a record to an object is significantly faster than pushing a record into an array.
- [ ] Most operations involve looking up a record, and objects can do that better than arrays.
- [ ] Working with objects makes the code more readable.



#### Q40. What will this code print?

```js
var v = 1;
var f1 = function () {
  console.log(v);
};

var f2 = function () {
  var v = 2;
  f1();
};

f2();
```

- [ ] 2
- [ ] 1
- [ ] Nothing - this code will throw an error.
- [ ] undefined



#### Q42. Your code is producing the error: TypeError: Cannot read property 'reduce' of undefined. What does that mean?

- [ ] You are calling a method named reduce on an object that's declared but has no value.
- [ ] You are calling a method named reduce on an object that does not exist.
- [ ] You are calling a method named reduce on an empty array.
- [ ] You are calling a method named reduce on an object that's has a null value.


#### Q45. What type of scope does the end variable have in the code shown?

```javascript
var start = 1;
if (start === 1) {
  let end = 2;
}
```

- [ ] conditional
- [ ] block
- [ ] global
- [ ] function


#### Q46. What will the value of y be in this code:

```js
const x = 6 % 2;
const y = x ? 'One' : 'Two';
```

- [ ] One
- [ ] undefined
- [ ] TRUE
- [ ] Two


#### Q49. The following program has a problem. What is it?

```js
var a;
var b = (a = 3) ? true : false;
```

- [ ] The condition in the ternary is using the assignment operator.
- [ ] You can't define a variable without initializing it.
- [ ] You can't use a ternary in the right-hand side of an assignment operator.
- [ ] The code is using the deprecated var keyword.


#### Q50. Which statement references the DOM node created by the code shown?

```html
<p class="pull">lorem ipsum</p>
```

- [ ] `Document.querySelector('class.pull')`
- [ ] `document.querySelector('.pull');`
- [ ] `Document.querySelector('pull')`
- [ ] `Document.querySelector('#pull')`

#### Q51. What value does this code return?

```js
let answer = true;
if (answer === false) {
  return 0;
} else {
  return 10;
}
```

- [ ] 10
- [ ] true
- [ ] false
- [ ] 0

#### Q52. What is the result in the console of running the code shown?

```js
var start = 1;
function setEnd() {
  var end = 10;
}
setEnd();
console.log(end);
```

- [ ] 10
- [ ] 0
- [ ] ReferenceError
- [ ] undefined



#### Q56. How does the `forEach()` method differ from a `for` statement?

- [ ] forEach allows you to specify your own iterator, whereas for does not.
- [ ] forEach can be used only with strings, whereas for can be used with additional data types.
- [ ] forEach can be used only with an array, whereas for can be used with additional data types.
- [ ] for loops can be nested; whereas forEach loops cannot.

#### Q57. Which choice is an incorrect way to define an arrow function that returns an empty object?

- [ ] => `({})`
- [ ] => `{}`
- [ ] => `{ return {};}`
- [ ] => `(({}))`

#### Q58. Why might you choose to make your code asynchronous?

- [ ] to start tasks that might take some time without blocking subsequent tasks from executing immediately
- [ ] to ensure that tasks further down in your code are not initiated until earlier tasks have completed
- [ ] to make your code faster
- [ ] to ensure that the call stack maintains a LIFO (Last in, First Out) structure

#### Q61. Which method cancels event default behavior?

- [ ] `cancel()`
- [ ] `stop()`
- [ ] `preventDefault()`
- [ ] `prevent()`

#### Q62. Which method do you use to attach one DOM node to another?

- [ ] `attachNode()`
- [ ] `getNode()`
- [ ] `querySelector()`
- [ ] `appendChild()`


#### Q69. What is the result of running the statement shown?

```javascript
let a = 5;
console.log(++a);
```

- [ ] 4
- [ ] 10
- [ ] 6
- [ ] 5

#### Q70. You've written the event listener shown below for a form button, but each time you click the button, the page reloads. Which statement would stop this from happening?

```javascript
button.addEventListener(
  'click',
  function (e) {
    button.className = 'clicked';
  },
  false,
);
```

- [ ] `e.blockReload();`
- [ ] `button.preventDefault();`
- [ ] `button.blockReload();`
- [ ] `e.preventDefault();`


#### Q74. What is the HTTP verb to request the contents of an existing resource?

- [ ] DELETE
- [ ] GET
- [ ] PATCH
- [ ] POST


#### Q79. What is the output of this code?

```javascript
var obj;
console.log(obj);
```

- [ ] `ReferenceError: obj is not defined`
- [ ] `{}`
- [ ] `undefined`
- [ ] `null`


#### Q91. Which missing line would allow you to create five variables(one,two,three,four,five) that correspond to their numerical values (1,2,3,4,5)?

```js
const numbers = [1, 2, 3, 4, 5];
//MISSING LINE
```

- [ ] `const [one,two,three,four,five]=numbers`
- [ ] `const {one,two,three,four,five}=numbers`
- [ ] `const [one,two,three,four,five]=[numbers]`
- [ ] `const {one,two,three,four,five}={numbers}`

#### Q92. What will this code print?

```js
const obj = {
  a: 1,
  b: 2,
  c: 3,
};

const obj2 = {
  ...obj,
  a: 0,
};

console.log(obj2.a, obj2.b);
```

- [ ] Nothing, it will throw an error
- [ ] 0 2
- [ ] undefined 2
- [ ] undefined 2

#### Q99. Which statement can take a single expression as input and then look through a number of choices until one that matches that value is found?

- [ ] else
- [ ] when
- [ ] if
- [ ] switch


#### Q104. Which method call is chained to handle a successful response returned by `fetch()`?

- [ ] `done()`
- [ ] `then()`
- [ ] `finally()`
- [ ] `catch()`

