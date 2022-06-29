## Return Negative

```js
function makeNegative(num) {
  // Code?
  if (num === 0) return 0;
  return -Math.abs(num);
}
```

## Sum of Positive

```js
function positiveSum(arr) {
  let sum = 0;
  for (let i = 0; i < arr.length; i++) {
    if (arr[i] > 0) {
      sum += arr[i];
    }
  }
  return sum;
}
```

## Function 2

```js
// Write the "square"-function here
function square(s) {
  return s * s;
}
```

## Sum Arrays

```js
function sum(numbers) {
  "use strict";
  if (numbers === undefined || numbers === 0) return 0;
  let sum = 0;
  for (let i of numbers) {
    sum += i;
  }
  return sum;
}
```

## Reversed Strings

```js
function solution(str) {
  return str.split("").reverse().join("");
}

function solution(str) {
  let reverse = "";
  for (let i = str.length - 1; i >= 0; i--) {
    reverse += str[i];
  }
  return reverse;
}
```
