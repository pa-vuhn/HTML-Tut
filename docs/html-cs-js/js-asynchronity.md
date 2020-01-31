# JS Asynchronity

1. What is Synchronous and asynchronous
   - Synchronous is a thing do first then It MUST complete first, then the next thing can continue to do its tasks

   - Asynchronous is a thing can do first but maybe complete later, the next thing can do its task without have to wait the first thing to complete.

_Example:_

>Synchronous 
```js

console.log('my order is 1')
console.log('my order is 2')


// Result
my order is 1
my order is 2
```

>Asynchronous 
```js
setTimeout(() => { console.log('my order is 1'); }, 100);
console.log('my order is 2')


// Result
my order is 2
my order is 1
```

2. How to create a asynchronous tasks.

    In Javascript, you can create a async task by follow way

- [Promise](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Promise)
- [async ](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/async_function) / [await](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/await)
- [setTimeout](https://www.w3schools.com/jsref/met_win_settimeout.asp)

