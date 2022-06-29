## Return Negative

```js
function makeNegative(num) {
  return -Math.abs(num);
}
```

## Sum of Positive

```js
function positiveSum(arr) {
   return arr.reduce((a,b)=> a + (b > 0 ? b : 0),0);
}
```

## Function 2

```js
const square = (n) => n * n;
```

## Sum Arrays

```js
function sum(numbers) {
  return numbers.reduce((a, b) => a + b, 0);
}
```

## Reversed Strings

```js
function solution(str){
  return str.split('').reverse().join('');  
}
```
