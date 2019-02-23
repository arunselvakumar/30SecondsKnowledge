Checks if the given argument is a string. Only works for string primitives.

Use typeof to check if a value is classified as a string primitive.

```javascript
const isString = val => typeof val === 'string';
```

```javascript
isString('10'); // true
```
