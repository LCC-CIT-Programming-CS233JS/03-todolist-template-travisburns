# To-Do List Application

![todolist](https://github.com/LCC-CIT-Programming-CS233JS/03-todolist-template-travisburns/assets/41456635/44283435-c549-4058-90fe-ae811dda97e9)

## Project Overview
This application simulates an electronic todo list. Users can add and delete tasks from the list and mark tasks as complete. The list of tasks is stored on the user's machine in local storage, allowing tasks to persist over time.

## Features
- Add new tasks
- Delete existing tasks
- Mark tasks as complete/incomplete
- Persistent storage using localStorage
- Responsive design using Bootstrap

## Technologies Used
- HTML5
- CSS3 (Bootstrap 5.2.1)
- JavaScript (ES6+)
- Webpack for module bundling
- Babel for JavaScript transpiling

## Key Learning Points
1. ES6 Classes:
   - Encapsulation of app logic in a ToDoList class

2. DOM Manipulation:
   - Dynamic rendering of task list
   - Event handling for task interactions

3. Local Storage:
   - Saving and loading tasks for data persistence

4. Modern JavaScript Development:
   - Use of Webpack for bundling
   - Babel for backwards compatibility

5. Bootstrap Integration:
   - Responsive design implementation
   - Utilization of Bootstrap components and icons

6. Event Handling:
   - Managing click and change events for task operations

## Code Structure
- Constructor initializes tasks from localStorage or default list
- Methods for loading, adding, toggling, and deleting tasks
- Helper method for generating HTML for each task

## How to Use
1. Clone the repository
2. Open `index.html` in your web browser
3. Add new tasks using the input field and 'Add' button
4. Click checkboxes to mark tasks as complete/incomplete
5. Click the trash icon to delete tasks
