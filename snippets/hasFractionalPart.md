---
title: hasFractionalPart
tags: math,intermediate
---

Checks if the given number has fractional part.

- Check whether a number has fractional part or not using the modulo (`%`) operator.
- Return `true` if the number has fractional part, `false` if the number has not fractional part.

```js
const hasFractionalPart = num => num % 1 !== 0;
```

```js
hasFractionalPart(3); // false
hasFractionalPart(3.00); // false
hasFractionalPart(3.001); // true
```
