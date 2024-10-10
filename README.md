# Jest Dojo

### 1. `addTask(tasks, taskDescription)`
- **Requirement 1**: Test that a new task is added to the list with the correct description and completion status (`completed: false`).
- **Requirement 2**: Test that the task list is saved to `localStorage` after adding a task.

### 2. `completeTask(tasks, index)`
- **Requirement 1**: Test that a task at the given `index` is marked as completed (`completed: true`).
- **Requirement 2**: Test that the updated task list is saved to `localStorage` after completing a task.

### 3. `clearCompletedTasks(tasks)`
- **Requirement 1**: Test that all completed tasks are removed from the task list.
- **Requirement 2**: Test that `localStorage` is updated with the remaining tasks after clearing completed tasks.

### 4. `loadTasks()`
- **Requirement 1**: Test that tasks are correctly loaded from `localStorage`.
- **Requirement 2**: Test that an empty array is returned if `localStorage` has no tasks stored.

### 5. `saveTasks(tasks)`
- **Requirement 1**: Test that the given task list is saved to `localStorage`.
- **Requirement 2**: Test that an empty task list is correctly saved to `localStorage`.
