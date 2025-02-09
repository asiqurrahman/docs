---
Title: ".then()"
Subjects:
  - "Web Development"
Tags:
  - "Methods"
  - "Promise"
Catalog Content:
  - "https://www.codecademy.com/learn/introduction-to-javascript"
  - "https://www.codecademy.com/learn/paths/full-stack-engineer-career-path"
---

## Definition

Returns a new `Promise` object.

## Syntax

```js
Promise.prototype.then(resolvedPromiseCallback, rejectedPromiseCallback);
```

The `resolvedPromiseCallback` function handles any resolved data from the previously fulfilled promise. The other argument, `rejectedPromiseCallback`, is optional and executes if the previous Promise was rejected.

## Example

```js
const myPromise = new Promise((resolve, reject) => {
  if (2 + 2 === 3) {
    resolve("Success!");
  } else {
    reject({
      errorType: "ArithmeticError",
      message: "The numbers don't add up!",
    });
  }
});

myPromise.then(
  (result) => {
    console.log(result);
  },
  (reason) => {
    console.log(`${reason.errorType}: ${reason.message}`); // ArithmeticError: The numbers don't add up!
  }
);
```
