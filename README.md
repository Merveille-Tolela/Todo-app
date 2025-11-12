# 📝 React Todo List App

A simple and interactive **Todo List application** built with **React**.  
This project demonstrates core React concepts like **state management**, **component composition**, and **event handling**.

---

## 🚀 Features

- ✅ **Add Todos** – Create new tasks easily.  
- 🔄 **Toggle Completion** – Mark todos as completed or incomplete using checkboxes.  
- ❌ **Delete Todos** – Remove tasks from the list instantly.  
- 🧠 **Dynamic UI** – The list updates automatically without refreshing the page.  

---

## 🧩 Components Overview

### `App.js`
- Main component managing all todos using React's `useState` hook.  
- Handles adding, toggling, and deleting todos.  
- Passes event handlers to child components via props.

### `NewTodoForm.js`
- Child component responsible for capturing new todo input.  
- Calls the parent’s `onSubmit` function to add new todos.

---

## ⚙️ Technologies Used

- **React** (with functional components)
- **JavaScript (ES6+)**
- **CSS3** (for styling)
- **Vite** or **Create React App** (depending on your setup)

---

## 🧠 Key React Concepts Demonstrated

- `useState` for managing application state.
- Updating state immutably using array spread and `map()` / `filter()`.
- Passing props between components.
- Controlled form input and event handling.
- Generating unique IDs using `crypto.randomUUID()`.

---

## 💻 Installation & Setup

1. **Clone this repository:**
   ```bash
   git clone https://github.com/your-username/react-todo-app.git
   cd react-todo-app
