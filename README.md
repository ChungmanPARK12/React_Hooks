# 📌 React Hooks Portfolio
## Showcasing My React Hooks Projects

Welcome to my **React Hooks** project portfolio! This repository demonstrates how I utilize **React Hooks** to build efficient, scalable, and interactive web applications. Below, you'll find details about React Hooks, why they are important, the project structure, key functionalities, and links to the source code.

---

## 🔍 What Are React Hooks?
React Hooks are built-in functions introduced in **React 16.8** that allow developers to use state and lifecycle features **without writing class components**. They make React components more **concise, readable, and reusable**.

### 🏆 **Why Use React Hooks?**
✔ **Simplified State Management** - Use `useState` instead of class-based state.  
✔ **Better Code Reusability** - Extract logic into custom hooks.  
✔ **Improved Performance** - Optimize rendering with `useMemo` and `useCallback`.  
✔ **Easier Side Effects Handling** - Manage lifecycle events with `useEffect`.  
✔ **No More `this` Keyword Confusion** - Functional components become more intuitive.

---

## 📁 Project Structure
### 📂 **Src**
- **`App.js`** - Main component integrating profile, jokes, tasks, gallery, and stories. Handles search and keypress events.  
- **`Gallery.js`** - Displays images from the dataset using the interval method.  
- **`hooks.js`** - API integration using React Hooks.  
- **`Joke.js`** - Fetches and displays jokes using API methods from hooks.  
- **`Stories.js`** - API request handler with URL integration.  
- **`Tasks.js`** - Handles task input, list management, adding, deleting, and cursor events.  
- **`index.js`** - Root component, rendering application with ReactDOM.  

### 📂 **Data**
- **`pictures.js`** - Handles image requests from assets.  

### 📂 **Styles**
- **`index.css`** - Contains global styles for the project.  

---

## 🛠️ **Key Features**
✅ **React Hooks Implementation** - Efficiently manages state using `useState`, `useEffect`, and `useContext`.  
✅ **API Integration** - Fetching data using hooks to display jokes and stories dynamically.  
✅ **Dynamic Image Gallery** - Loads and displays images using an interval function.  
✅ **Task Management System** - Allows users to add, edit, delete, and manage tasks interactively.  
✅ **Keyboard Event Handling** - Implements keypress event detection for better user experience.  

---

## 🏗 **React Hooks Used in This Project**
| Hook       | Purpose |
|------------|---------|
| `useState` | Manages component state dynamically. |
| `useEffect` | Handles side effects such as API calls and event listeners. |
| `useContext` | Shares global state without prop drilling. |
| `useRef` | Directly interacts with the DOM without re-rendering. |
| `useCallback` | Optimizes performance by memoizing callback functions. |
| `useMemo` | Prevents unnecessary re-computation for derived state values. |

---

