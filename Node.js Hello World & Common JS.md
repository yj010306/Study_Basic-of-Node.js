# Node.js Hello World & Common JS
---

## Calc.js
``` javascript
const add = (a, b) => a + b;
const sub = (a,b) => a - b;

module.exports = {
    moduleName: "Calc module",
    add: add,
    sub: sub,
};
```

## index.js
``` javascript
const calc = require("./Calc");

console.log(calc.add(1,2));
console.log(calc.add(4,5));
console.log(calc.sub(10, 2));
```
