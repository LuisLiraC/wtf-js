# WTF JS

Just require the file `wtf-js.js`, this file export by default a function and convert the string that you passed in an "esoteric" JavaScript String

```javascript
const WTFJS = require('./wtf-js')

const wtfText = WTFJS('hello world'))
/* 
    result:

    String.fromCharCode(+(((+!+[] + +!+[]) * (+!+[] + +!+[] + +!+[]) + +!+[] + []) + (+!+[] + +!+[])))+((!![]) + [])[+!+[] + +!+[] + +!+[]]+(![] + [])[+!+[] + +!+[]]+(![] + [])[+!+[] + +!+[]]+({} + [])[+!+[]]+({} + [])[((+!+[] + +!+[]) 
    * (+!+[] + +!+[] + +!+[])) + +!+[]]+String.fromCharCode(+(((+!+[] + +!+[]) ** (+!+[] + +!+[] + +!+[]) + []) + ((+!+[] + +!+[]) * (+!+[] + +!+[] + +!+[]) + +!+[] + [])))+({} + [])[+!+[]]+((!![]) + [])[+[+!+[]]]+(![] + [])[+!+[] + +!+[]]+([][[]] + [])[+!+[] + +!+[]]
*/
```

Now you can confuse your friends. 😁