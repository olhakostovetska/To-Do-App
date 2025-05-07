# 📝 React To-Do App with API Integration

A fully functional **To-Do application built with React and TypeScript** that interacts with a remote API to manage tasks in real time. This app focuses on clean UI/UX, asynchronous operations, and persistent data handling.
The goal of this project is to implement a responsive and intuitive To-Do manager where all data is synchronized with a remote API. The app is built in stages, covering loading, creating, updating, deleting, and filtering todos — ensuring both technical correctness and a smooth user experience.

## 🚀 Live Demo
👉 [DEMO LINK](https://olhakostovetska.github.io/To-Do-App/)

## 🛠️ Technologies Used

- **React (TypeScript)**
- **React Hooks**
- **Vite**
- **CSS Modules**
- **Fetch API**
- **Cypress** (E2E Testing)

## ✅ Features

### 🔄 Load Todos by User ID
- Loads todos for a specific user from a remote API on app load.
- Hides list and footer if no todos exist.

### ➕➖ Add and Delete Todos
- Add new todos with form submission (auto-trimmed and validated).
- Delete single todos or clear all completed ones.
- Uses temporary todo with loader for optimistic UI updates.
- Handles and displays API errors gracefully.

### ✅ Toggle Todo Status
- Toggle completion status of individual todos.
- "Toggle All" functionality to mark all todos as complete/incomplete.
- Only changed todos are updated via API.

### ✏️ Rename Todos
- Double-click to edit a todo.
- Save on blur or Enter.
- Cancel on Escape.
- Automatically deletes if the new title is empty.
- Inline loading spinner and error handling.

### 🔍 Filtering
- Filter todos by **All**, **Active**, or **Completed**.
- Uses visual indicators to highlight the selected filter.

### 🧠 Smart UX Enhancements
- Loader overlays on every async operation.
- Disabled controls during in-progress actions.
- Input auto-focus and state preservation on errors.
- Real-time error notifications with auto-dismiss after 3 seconds.

### 🧪 Testing
- All features are covered by Cypress E2E tests.
- The implementation passes all required test scenarios.
