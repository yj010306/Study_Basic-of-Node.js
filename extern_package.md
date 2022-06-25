## Extern_Package
---
# package.jason
``` javascript
{
  "name": "package-example1",
  "version": "1.0.0",
  "description": "",
  "main": "index.js",
  "scripts": {
    "test": "echo \"Error: no test specified\" && exit 1",
    "start": "node index.js"
  },
  "author": "yongjin",
  "license": "ISC",
  "dependencies": {
    "randomcolor": "^0.6.2"
  }
}
```
# index.js
``` javascript
const randomcolor = require("randomcolor");

let color1 = randomcolor();
let color2 = randomcolor();
let color3 = randomcolor();


console.log(color1, color2, color3);
```
