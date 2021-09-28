# Block and function

* Block mostly is used for grouping code into one related group and is defined by using such syntax:

```js
{
    var a = "Hello";
}
```

* Functions are declared as follows:

```js
function multiply(p1, p2) {
    return p1 * p2;
}
```

Functions also groups code into one group, but it is possible to pass some variables to them and also possible to get a result after function is executed:

```js
var res = multiply(5, 6);
console.log(res);
```

Function can be declared in this way as well:

```js
var add = function(left, right) {
    return left + right;
}

var res = add(5, 5);
```

What is the difference between:

```js
function one() {}
```

and

```js
var one = function() {}
```