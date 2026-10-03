# Productivity Suite (To-Do App & Notes App)

A dual-purpose productivity web application built with **React.js** and modern **ES6+ JavaScript**. This project combines an interactive Task Tracker with a categorized Quick Notes Manager, featuring full local persistence and responsive design.

---

## 🚀 Features

### 1. Task Tracker (To-Do App)
- **Add Tasks**: Create new tasks with text descriptions and optional due dates.
- **Mark Completion**: Toggle status dynamically between **Pending** and **Completed** with strike-through styling.
- **Edit & Update**: Inline task editing with pre-filled inputs.
- **Delete Tasks**: Remove individual tasks with real-time state updates.
- **Dynamic Filtering**: Filter items by **All**, **Pending**, or **Completed**.
- **Local Storage Integration**: All tasks persist across browser reloads.

### 2. Quick Notes App
- **Create & Manage**: Compose multi-line notes with structured titles and body content.
- **Categorization**: Organize notes under tags like *Personal*, *Work*, *Study*, and *Ideas*.
- **Live Search**: Instant keyword search matching note titles and text contents.
- **Timestamps**: Automatically updates creation and last-modified dates.
- **Edit & Delete**: Full update and delete lifecycle for every note.
- **Local Storage Integration**: Automatic note state persistence via browser storage.

---

## 🛠️ Technologies & Concepts Used

### React.js Fundamentals
- **Functional Components**: Component-based modular architecture.
- **State Management**: `useState` hook for local UI states, form bindings, and active views.
- **Side Effects**: `useEffect` hook for synchronizing tasks and notes with `localStorage`.
- **Conditional & List Rendering**: Rendering dynamic lists with `.map()` and conditional empty states.
- **Props & Event Handling**: Clean uni-directional data flow from container components to child components.

### Modern JavaScript (ES6+)
- Arrow functions, object & array destructuring.
- Spread operator (`...`) for immutable state updates.
- Array methods: `.map()`, `.filter()`.
- Template literals and clean module imports/exports.

---

## 📂 Project Structure

```text
src/
├── components/
│   ├── Navbar.jsx
│   ├── TodoApp/
│   │   ├── TodoApp.jsx
│   │   ├── TodoFilter.jsx
│   │   ├── TodoForm.jsx
│   │   └── TodoItem.jsx
│   └── NotesApp/
│       ├── NotesApp.jsx
│       ├── NoteForm.jsx
│       ├── NoteItem.jsx
│       └── NoteSearch.jsx
├── App.css
├── App.jsx
├── index.css
└── main.jsx