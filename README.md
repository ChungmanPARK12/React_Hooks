# 📌 React Hooks Portfolio
![Image](https://github.com/user-attachments/assets/8cd350d4-6a9b-4eff-ac22-c9f2c2d5ac7a)
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
- **`App.js`** – The main component that integrating a search bar, joke display, task manager, stories, and a togglable gallery. It utilizes React Hooks for state management and user interactions dynamically. 
  - **View Code:** [Click here](https://github.com/ChungmanPARK12/React_Hooks/tree/c260ec93b189614392ea7c1c953979c2283ba090/src/App)

- **`Gallery.js`** - This component dynamically cycles through images from a dataset every 7 seconds using the useEffect hook. It efficiently updates the displayed image while ensuring proper cleanup with clearInterval() to prevent memory leaks. 
  - **View Code:** [Click here](https://github.com/ChungmanPARK12/React_Hooks/tree/c260ec93b189614392ea7c1c953979c2283ba090/src/Gallery)

- **`hooks.js`** - This custom hook, useFetch, simplifies API integration by fetching data from a given URL using the useEffect hook. It initializes state with a default value and updates it upon receiving JSON data, ensuring efficient and reusable API calls.
  - **View Code:** [Click here](https://github.com/ChungmanPARK12/React_Hooks/tree/c260ec93b189614392ea7c1c953979c2283ba090/src/hooks)

- **`Joke.js`** – Fetches and displays a random joke using API methods from the `useFetch` custom hook. It retrieves the joke's **setup and punchline** dynamically from an API, ensuring an interactive user experience.
  - **View Code:** [Click here](https://github.com/ChungmanPARK12/React_Hooks/tree/c260ec93b189614392ea7c1c953979c2283ba090/src/Joke)

- **`Stories.js`** – Handles API requests and integrates URLs to fetch and display top news stories dynamically. It utilizes the `useFetch` custom hook to retrieve story details, including the author, title, and publication date.
  - **View Code:** [Click here](https://github.com/ChungmanPARK12/React_Hooks/tree/c260ec93b189614392ea7c1c953979c2283ba090/src/Stories)  

- **`Tasks.js`** – Manages task input, list updates, completion, and deletion using React Hooks. It stores tasks in **localStorage**, allowing users to persist their task lists while enabling interactive management through click events.
  - **View Code:** [Click here](https://github.com/ChungmanPARK12/React_Hooks/tree/c260ec93b189614392ea7c1c953979c2283ba090/src/Tasks)

- **`index.js`** – The root component responsible for rendering the application using `ReactDOM.createRoot()`. It imports global styles and initializes the `App` component, serving as the entry point for the React application.
  - **View Code:** [Click here](https://github.com/ChungmanPARK12/React_Hooks/tree/c260ec93b189614392ea7c1c953979c2283ba090/src/index)

### 📂 **Data**
- **`pictures.js`** – Manages and exports an array of image objects sourced from the assets folder. Each image is assigned a unique `id`, allowing for dynamic rendering in the gallery component.
  - **View Code:** [Click here](https://github.com/ChungmanPARK12/React_Hooks/tree/c260ec93b189614392ea7c1c953979c2283ba090/src/pictures)

### 📂 **Styles**
- **`index.css`** – Defines global styles for the project, including typography, layout, form styling, button design, gallery presentation, and task list interactions. It enhances the visual consistency and user experience across the application.
  - **View Code:** [Click here](https://github.com/ChungmanPARK12/React_Hooks/tree/c260ec93b189614392ea7c1c953979c2283ba090/src/css)

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



