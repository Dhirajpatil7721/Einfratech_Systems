# Task Manager App

This is a simple Task Manager application where users can add, edit, delete, and clear tasks. The tasks are saved in the browser's `localStorage`, which means the data will persist even after a page reload.

## Features

- **Add Task**: Allows users to add new tasks to the list.
- **Edit Task**: Enables users to modify an existing task.
- **Delete Task**: Users can delete tasks from the list.
- **Clear All Tasks**: Clears all tasks from the list and `localStorage`.
- **Persistent Storage**: All tasks are saved in `localStorage`, ensuring persistence even after a page reload.
  
## Prerequisites

- A modern web browser that supports JavaScript and `localStorage`.

## How to Use

1. **Add a Task**:
    - Type a task in the input field and click the **Add** button to add it to the list.
  
2. **Edit a Task**:
    - Click the **Edit** button next to a task to modify its content.
  
3. **Delete a Task**:
    - Click the **Delete** button next to a task to remove it from the list.

4. **Clear All Tasks**:
    - Click the **Clear All** button to delete all tasks from the list and `localStorage`.


## Code Explanation

- **`localStorage`**: Used to store tasks so that they persist even after the page is reloaded.
- **Task Operations**:
  - **Add Task**: Adds a task to the list and updates `localStorage`.
  - **Edit Task**: Allows you to modify a task and save the new task to `localStorage`.
  - **Delete Task**: Removes a task from the list and updates `localStorage`.
  - **Clear All Tasks**: Clears both the display and `localStorage`.

## Technologies Used

- **HTML**: For the structure of the task manager.
- **CSS**: For styling the task manager and buttons.
- **JavaScript**: To handle adding, editing, deleting, and displaying tasks. Uses `localStorage` for persistence.

## Demo

To view the demo, simply open the `index.html` file in your browser.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
