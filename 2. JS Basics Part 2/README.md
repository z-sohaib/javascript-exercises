# JavaScript Basics Part 2

### Practice 1

Write a JavaScript function to get the first n elements of an array. 

Examples:
```
function firstElements(arr, n) {...}

console.log(firstElements([1, 2, 3, 4], 1)) // 1
console.log(firstElements(1, 2, 3, 4), 3) // [1, 2, 3]
```

### Practice 2

Write a JavaScript function that finds the most frequent item in an array. 

Examples:
```
function mostFrequent(arr) {...}

console.log(mostFrequent([1, 2, "a", "a", 5, 15, true, "a"])) // a
```

### Practice 3

Write a Javascript function that returns the product of an array of integers. If an element is not an integer the function should return -1

Examples:
```
function productOfArray(arr) {...}
console.log(productOfArray([1, 2, 5])) // 10
console.log(productOfArray([1, 2, true])) // -1
```

### Practice 4

Write a Javascript function removes non-integer values from an array

Examples:
```
function removeNonIntegers(array) {...}
console.log(removeNonIntegers([1, 2, 3])) // [1, 2, 3]
console.log(removeNonIntegers([1, true, NaN, "a", 10])) // [1, 10]
```

### Practice 5

Write a JavaScript function to insert a string within a string at a particular position (default is 1).

Examples:
```
console.log(insert('We are doing some exercises.','JavaScript ')) //  "JavaScript We are doing some exercises." 
console.log(insert('We are doing some exercises.','JavaScript ',18)); //  "We are doing some JavaScript exercises."
```