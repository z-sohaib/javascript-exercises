# ES6

### Exercise 1: ES6 Kick Off

#### Part A: Convert the following function to an arrow function and use template strings to format the output.

```
function greet(name) {
    return "Hello, " + name + "!";
}

console.log(greet("Alice")); // Should print: Hello, Alice!
```

Part B: Use the spread operator to merge two arrays and the rest operator to create a function that accepts any number of arguments.

```
// Merge these arrays using the spread operator
const arr1 = [1, 2, 3];
const arr2 = [4, 5, 6];
// Result should be: [1, 2, 3, 4, 5, 6]

// Create a function that accepts any number of arguments and returns their sum
function sumAll(...numbers) {
    // Implement the function to return the sum of all numbers
}

console.log(sumAll(1, 2, 3, 4)); // Should print: 10
```

### Exercise 2: Classes and Modules

- Create two modules: taskManager.js and main.js.
- In taskManager.js, export a class TaskManager that takes username and tasks as properties and allows you to add and list tasks using the corresponding methods.
- In main.js, import the TaskManager class and use it.

### Exercise 3: Promises

In this exercise, we'll use Promises to simulate a delay and indicate the completion of a task after a certain period:

- Create a function that returns a Promise, which resolves after a specified number of milliseconds passed as a parameter for the function.
- Create a function that simulates a task, using the delay function to wait for a specified time before marking the task as complete. The funcation takes a task name and a given delai as parameters.
