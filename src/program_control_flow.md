# Program control flow

* **if - else** statement:

```js
var x = 5;
var y = 6;

if (x > y) {
    console.log("x is greater than y.");
} else {
    console.log("x is less than y.");
}
```

* **switch** statement:

```js
var vegetable = 'Cucumber';

switch (var) {
    case 'Cucumber':
        console.log('Cucumber are $0.59 a pound.');
        break;
    case 'Spinatch':
        console.log('Spinatch are $0.32 a pund.');
        break;
    default:
        console.log('Sorry we are out of ' + vegetable + '.');
}
```