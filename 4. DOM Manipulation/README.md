# DOM Manipulation

### Exercise: Todo List Application

Welcome to the Todo List Application exercise! In this assignment, you will create a simple Todo List application using JavaScript. The application will allow users to perform the following actions:

- Get all todos from a local array.
- Add a new todo to the array and display it.
- Remove a todo from the array and display the updated list.


#### 1. Set Up Your Project
   
- In your index.html, include a basic HTML structure with a heading, an input field for adding new todos, a button to add the todo, and an unordered list to display the todos.
- Make sure to add some styling to your page to make it fancy before working on js
- In your script.js, create an array named todos to hold your todo items. A todo item is an object consisted of a title and isCompleted property which is a boolean (we will need that property to mark a todo as completed). You can also add an identifier property called "id" which we will be using for indexing todo items in the array.

#### 2. Display All Todos
   
- Write a function named displayTodos that loops through the todos array and displays each todo item as a list item (`<li>`) in the unordered list. 
- The list item should contain a title text and a checkbox input to mark the todo as completed (Time to showcase your JavaScript skills on how to render a group of elements inside one parent element)

#### 3. Add a New Todo
   
- Write a function named addTodo that takes the value from the input field, adds it to the todos array, and calls displayTodos to update the list.
- Ensure the input field is cleared after adding the todo.

#### 4. Mark a Todo as Completed
- Write a function named toggleCompleteTodo that takes an id, toggles the isCompleted property of the corresponding item in the todos array, and calls displayTodos to update the list.
  
#### 5. Remove a Todo
   
- Write a function named removeTodo that takes an id, removes the corresponding item from the todos array, and calls displayTodos to update the list.
- Add a "Remove" button next to each todo item in the list, and set it up to call removeTodo with the correct index when clicked.
  
#### 6. Connect Functions to HTML Elements
   
- Add event listeners to the input field and buttons in your index.html to call the appropriate functions in your script.js.