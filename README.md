# Todo List

> ✨ Bootstrapped with Create Snowpack App (CSA). <br />

### Why Snowpack
Browser dosn't know how to access node modules, that's why we use a bundeler to bundle up code and node modules so that the browser can understand

## About
This is a small TypeScript project for a Todo List application that allows users to store and retrieve data using the browser's local storage.

### Features
- Add new tasks to the todo list.
- Mark tasks as complete.
- Store and retrieve data using local storage.

### Local Storage
The application utilizes the browser's local storage to persist the todo list data. This allows the user's data to be saved even if the page is refreshed or closed and reopened.

The data is stored as a JSON string in the localStorage object using the key "TASKS". Whenever a change is made to the todo list (e.g., adding a task, marking a task as complete, or removing a task), the updated list is stored in the local storage.

When the application starts, it checks if there is any existing data in the local storage. If there is, it retrieves and populates the todo list with the stored data.


## Available Scripts
### npm start

Runs the app in the development mode.
Open http://localhost:8080 to view it in the browser.

The page will reload if you make edits.
You will also see any lint errors in the console.
