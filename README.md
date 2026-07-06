# 📝 Task Manager (To-Do App)

A modern **Task Manager (To-Do List)** built using **HTML, CSS, and Vanilla JavaScript**.

This project was developed as part of my JavaScript learning journey to strengthen my understanding of DOM manipulation, events, arrays, objects, Local Storage, and dynamic UI updates without using any external libraries or frameworks.

---

# 🚀 Features

* ✅ Add new tasks
* ✅ Delete tasks
* ✅ Mark tasks as completed
* ✅ Assign task priority (High, Medium, Low)
* ✅ Automatically save tasks using Local Storage
* ✅ Automatically load saved tasks when the browser is reopened
* ✅ Responsive and clean user interface
* ✅ Dynamic DOM rendering
* ✅ Professional card-based layout

---

# 📸 Preview

The application includes:

* Clean dashboard layout
* Input field for new tasks
* Priority selection
* Complete and Delete buttons
* Completed task styling
* Persistent storage using Local Storage

---

# 🛠️ Technologies Used

* HTML5
* CSS3
* JavaScript (ES6)
* Browser Local Storage API

No frameworks or external libraries were used.

---

# 📂 Project Structure

```text
Task-Manager/
│
├── index.html
├── style.css
├── script.js
└── README.md
```

---

# 📚 JavaScript Concepts Practiced

## DOM Manipulation

* document.getElementById()
* document.createElement()
* appendChild()
* innerText
* classList.add()
* className

---

## Event Handling

* onclick
* Button click events
* Dynamic event binding

---

## Arrays

* push()
* unshift()
* splice()
* length

---

## Objects

Each task is stored as an object.

Example:

```javascript
{
    text: "Study JavaScript",
    completed: false,
    priority: "High"
}
```

---

## Loops

* for loop

Used to display every task dynamically.

---

## Conditional Statements

```javascript
if (tasks[i].completed) {
    span.classList.add("completed");
}
```

Used to determine whether a task should appear completed.

---

## Local Storage

Tasks are saved inside the browser using:

```javascript
localStorage.setItem()
```

Tasks are loaded using:

```javascript
localStorage.getItem()
```

Objects are converted into strings using:

```javascript
JSON.stringify()
```

Strings are converted back into JavaScript objects using:

```javascript
JSON.parse()
```

---

# 💾 How Local Storage Works

1. User adds a task.
2. Task is stored inside the `tasks` array.
3. `saveTasks()` saves the array into Local Storage.
4. Refreshing the page does **not** delete the tasks.
5. When the application loads again, Local Storage is read and the tasks are displayed automatically.

Flow:

```text
Add Task
     │
     ▼
tasks Array
     │
     ▼
saveTasks()
     │
     ▼
Local Storage
     │
Refresh Page
     ▼
getItem()
     ▼
displayTasks()
```

---

# ⚙️ How to Run

1. Clone the repository.

```bash
git clone <repository-url>
```

2. Open the project folder.

3. Open `index.html` in your browser.

No installation is required.

---

# 🎯 Future Improvements

* Edit existing tasks
* Search tasks
* Filter (All / Active / Completed)
* Due dates
* Categories
* Drag & Drop task ordering
* Dark Mode
* Task statistics
* Clear completed tasks
* Responsive mobile improvements
* Keyboard shortcut (Enter key to add task)
* Sort tasks by priority

---

# 📖 What I Learned

While building this project, I practiced:

* Selecting elements from the DOM
* Creating HTML elements dynamically
* Updating the DOM
* Working with arrays and objects
* JavaScript functions
* Event handling
* Local Storage
* JSON methods
* Conditional rendering
* Building reusable functions
* Writing clean and organized JavaScript

---

# 👨‍💻 Author

**Taha Nawaz**

Software Engineering Student

Learning JavaScript, React, Django, and Full-Stack Web Development.

---

# ⭐ Acknowledgement

This project was built for learning purposes to improve my understanding of modern JavaScript fundamentals and DOM manipulation before moving on to React.
