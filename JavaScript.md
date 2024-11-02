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
<br></br>

# conditional statements
### switch case
```js
const price = 0;
switch(price) {
    case 1:
        console.log("1");
        break;

    case 2:
        console.log("2");
        break;

    default:
        console.log("0");
}
```
<br></br>

# functions
### traditional function
```js
function add(num1, num2) {
    console.log(num1 + num2);
}

add(5, 5);
```

### arrow function
```js
const add = (num1, num2) => {
    return num1 + num2;
}

console.log(add(5, 5))

```
<br></br>

# loops
