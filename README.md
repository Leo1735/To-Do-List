# To-Do List App

A lightweight browser-based To-Do List application built with vanilla JavaScript, HTML, and CSS. The application allows users to create, edit, complete, and delete tasks while automatically saving progress using the browser's Local Storage.

## Features

- Add new tasks
- Edit existing tasks
- Mark tasks as completed
- Delete tasks
- Prevent duplicate tasks
- Automatically save tasks using Local Storage
- Tasks persist after closing or refreshing the browser

## Technologies Used

- HTML5
- CSS3
- JavaScript (ES6)
- Local Storage API
- Font Awesome

## How It Works

Tasks are stored as an array of JavaScript objects in the browser's Local Storage.

Example:

```javascript
[
  {
    "task": "Complete assignment",
    "completed": false
  },
  {
    "task": "Buy groceries",
    "completed": true
  }
]
```

When the page loads, the application retrieves this data and dynamically recreates the task list.

Users can:

- Create new tasks
- Edit task names
- Toggle completion status
- Remove tasks

Every change immediately updates Local Storage, ensuring task data is preserved between sessions.

## Running the Project

1. Clone the repository

```bash
git clone https://github.com/Leo1735/<repository-name>.git
```

2. Open the project folder.

3. Launch `index.html` in your web browser.

No additional dependencies or installation are required.

## Future Improvements

Potential enhancements include:

- Due dates and reminders
- Task categories
- Search and filtering
- Drag-and-drop task ordering
- Dark mode
- Responsive mobile layout
- Export and import task lists

## What I Learned

This project helped strengthen my understanding of:

- DOM manipulation
- Event-driven programming
- JavaScript functions and scope
- Browser Local Storage
- Dynamic HTML generation
- CRUD (Create, Read, Update, Delete) operations
- Client-side state management

## Project Status

Completed as a personal learning project and available for future improvements.
