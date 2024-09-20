## Return Negative

```
function makeNegative(num) {
  return num > 0 ? -num : num;
  };
```

## Sum of Positive

```
function positiveSum(arr) {
  return arr
  .filter(num => num > 0)
  .reduce((sum, num) => sum + num, 0);  
}
console.log(positiveSum([1, -4, 7, 12]));
```

## Function 2

```
function square(num) {
  return num * num;
}
console.log(square(15)); // Output 225
console.log(square(20)); // Output 400
```

## Sum Arrays

```
function sum(numbers) {
  let total = 0; 
  for (let num of numbers) {
    total += num;

}
return total;
  }
// Example usage:
console.log(sum([1, 5.2, 4, 0, -1]));  // Output: 9.2
console.log(sum([]));  // Output: 0
console.log(sum([-2.398]));  // Output: -2.398

//.reduce
//Sums all the numbersin the array 
//The second arguement to reduce, 0 is the intitial value of the sum 
//The function works postivie and negative numbers, as well as decimal numbers, just as required 
```

## Reversed Strings

```
function solution(str){
  return str.split('').reverse().join('');  
}
```

