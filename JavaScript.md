# logical operators
### "==" vs "==="
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

### ternary operator
```js
let isSunny = true;
let weatherMessage = isSunny ? "It's is a sunny day." : "It's NOT a sunny day.";
console.log(weatherMessage);
```
