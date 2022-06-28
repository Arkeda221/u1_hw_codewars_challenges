## Return Negative

```js
function makeNegative(num) {
  if (num > 0) {
    return num * -1
  } else {
    return num
  }
}
```

## Sum of Positive

```js
function positiveSum(arr) {
  let sum = 0
  for (i = 0; i < arr.length; i++) {
    if (arr[i] > 0) {
      sum = sum + arr[i]
    }
  }
  return sum
}
```

## Function 2

```js
function square(num) {
  return Math.pow(num, 2)
}
```

## Sum Arrays

```js
function sum(numbers) {
  let ans = 0
  for (i = 0; i < numbers.length; i++) {
    ans = ans + numbers[i]
  }
  return ans
}
```

## Reversed Strings

```js
function solution(str) {
  str = str.split('').reverse().join('')
  return str
}
```

// found an explantion on stackoverflow and used mdn to further understand how split, reverse, and join work
