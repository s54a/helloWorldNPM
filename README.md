# h8d || Hello World

This is my first NPM Package it just prints Hello World!!! in console

### How to Use

```js
const helloWorld = require("h8d");

helloWorld();
```

Below is the code in the h8d index.js file

```js
function h8d() {
  return console.log("Hello World!!!");
}

module.exports = h8d;
```
