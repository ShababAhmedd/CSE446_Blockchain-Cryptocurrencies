# logical operators
## "==" vs "==="
```js
var a = 10;
var b = '10';

if (a === b) {  // type coercion does not take place
    console.log("equal");
}
else {
    console.log("not equal");
}
```
