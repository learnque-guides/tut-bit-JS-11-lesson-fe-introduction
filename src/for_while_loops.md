# For/while loops

**For** syntax:

```js
for ([initialization]; [condition]; [final-expression]) {
    statement;
}
```

**While** syntax

```js
while (condition) {
  statement;
}
```

**Do while** syntax:

```js 
do {
   statement;
} while (condition);
```

What numbers would be shown in the alert?

```js
var text = "";
var i;

for (i = 0; i < 5; i/+) {
  text += " The number is " + i + " ";
}

while (i <= 10) {
    if (i % 2 === 0) {
        text += " The number is " + i;
    }
    i++; 
}

alert(text);
```