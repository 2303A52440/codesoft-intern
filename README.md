# ✅ TaskFlow — To-Do List App

A clean, responsive, and feature-rich To-Do List web application built with pure HTML, CSS, and JavaScript. No frameworks, no dependencies — just open the file in any browser and start managing your tasks.

---

## 🚀 Live Demo

> Open `taskflow.html` directly in your browser — no server needed.

---

## 📸 Screenshots

| Home Screen | Add Task | Task Management |
|---|---|---|
| View all tasks with priority badges and due dates | Create tasks with title, description, priority & due date | Edit, complete, or delete any task |

---

## ✨ Features

- **➕ Add Tasks** — Create tasks with a title, optional description, priority level, and due date
- **✏️ Edit Tasks** — Update any task's details at any time
- **🗑️ Delete Tasks** — Remove tasks with a confirmation dialog to prevent accidents
- **✅ Task Completion** — Toggle tasks between active and completed with one click
- **🔴 Priority Levels** — Assign Low, Medium, or High priority to every task
- **📅 Due Dates** — Set due dates with smart labels: *Overdue*, *Today*, *Tomorrow*, or the date
- **🔍 Search** — Live search across task titles and descriptions
- **📂 Sidebar Views** — Filter by All, Active, Completed, High Priority, or Due Today
- **📊 Progress Tracker** — Visual completion percentage bar in the sidebar
- **💾 Local Storage** — Tasks persist automatically across browser sessions
- **⌨️ Keyboard Shortcuts** — `Esc` to close modals, `Ctrl/Cmd + Enter` to save

---

## 🛠️ Tech Stack

| Technology | Usage |
|---|---|
| HTML5 | Structure and layout |
| CSS3 | Styling, animations, responsive design |
| Vanilla JavaScript | App logic, DOM manipulation |
| localStorage API | Data persistence (no backend needed) |
| Google Fonts | Inter + Space Grotesk typography |

---

## 📁 Project Structure

```
taskflow-todo-app/
│
├── taskflow.html       # Main application file (all-in-one)
└── README.md           # Project documentation
```

---

## ⚙️ How to Run

### Option 1 — Open Directly
1. Download `taskflow.html`
2. Double-click to open in any modern browser (Chrome, Firefox, Edge, Safari)

### Option 2 — GitHub Pages (Live URL)
1. Push this repo to GitHub
2. Go to **Settings → Pages**
3. Set source to **main branch / root**
4. Your app will be live at `https://yourusername.github.io/taskflow-todo-app/taskflow.html`

---

## 🎯 How to Use

### Adding a Task
1. Click the **"＋ Add Task"** button in the top right
2. Enter a title (required), description (optional), priority, and due date
3. Click **"Save Task"** or press `Ctrl + Enter`

### Completing a Task
- Click the **circle icon** on the left of any task to toggle it complete/active

### Editing a Task
- Hover over a task card → click the **✏️ edit icon**

### Deleting a Task
- Hover over a task card → click the **🗑️ delete icon** → confirm deletion

### Filtering Tasks
- Use the **sidebar** to switch views: All, Active, Completed, High Priority, Due Today
- Use the **priority chips** below the topbar to filter by priority level
- Use the **search bar** to find tasks by keyword

---

## 💡 Keyboard Shortcuts

| Shortcut | Action |
|---|---|
| `Ctrl + Enter` / `Cmd + Enter` | Save task in modal |
| `Esc` | Close any open modal |

---

## 📦 Data Storage

All tasks are saved in the browser's **localStorage** under the key `taskflow_tasks_v2`. Data persists across page refreshes and browser restarts. No account or internet connection is required.

> **Note:** Clearing browser data/cache will erase saved tasks.

---

## 🎨 Design Highlights

- Dark theme with a deep navy/charcoal palette
- Accent color: `#7c6fff` (soft purple)
- Priority color coding: 🟢 Green (Low) · 🟡 Yellow (Medium) · 🔴 Red (High)
- Smooth hover animations and modal transitions
- Fully responsive — works on mobile and desktop

---

## 📋 Task Requirements Fulfilled

| Requirement | Status |
|---|---|
| Display task list with titles and completion status | ✅ |
| Add new tasks with title and description | ✅ |
| Edit task titles and descriptions | ✅ |
| Mark tasks as completed or active | ✅ |
| Delete tasks from the list | ✅ |
| Local data storage for persistence | ✅ |
| Task priorities (Low / Medium / High) | ✅ |
| Due dates | ✅ |
| Intuitive and user-friendly interface | ✅ |

---

## 👨‍💻 Author

Built as part of a mobile/web application development assignment.

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).
