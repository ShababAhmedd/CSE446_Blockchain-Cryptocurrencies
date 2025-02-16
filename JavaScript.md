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
### for
```js
for (let i = 0; i < 10; i++) {
    console.log("hello")
}
```

### for in 
(when iterating an object) <br> </br>
key = in <br></br>
```js
const myObj = {
    a : 1,
    b : 2,
    c : 3,
}

for (const i in myObj) {
    console.log(i);
}
```

### for of 
(when iterating an array) <br></br>
val = off <br></br>
```js
const arr = ["CSE446", "CSE490", "CSE447"];

for (const i of arr) {
    console.log(i);
}

for (const i in arr) {
    console.log(i);
}
```

# objects
```js
const car = {
    name: "Axio", 
    company: "toyota",
    colour: "white"
}

console.log(car.name);
```

### object within object
```js
const car = {
  // key: "value"
  parts: {
    doors: 4,
    lights: 4,
  },
};

console.log(car.parts);
console.log(car.parts.doors);
```

### dynamic access
```js
const car = {
  parts: {
    doors: 4,
    lights: 4,
  },
};

const prop = "parts";

console.log(car[prop]);
```
