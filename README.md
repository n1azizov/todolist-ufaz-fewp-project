# 📌 To-Do List Web Application  
A modern, fully client-side task management system featuring task creation, filtering, sorting, subtasks, color tagging, and persistent storage using `localStorage`.

---

## 🚀 Features

### **Task Creation Page**
- Create tasks with:
  - Title, description, due date  
  - Priority, status, category  
  - Optional color tag  
  - Optional subtasks (one per line)
- Auto-generated task IDs
- Subtask ID generation based on parent task
- Clean, responsive UI with real-time validation
- **Toast notification** confirming successful task creation

### **Task Summary Page**
- Dynamic task table with:
  - Category, priority badges, status pills  
  - Color indicators (🔴 🟢 🔵 🟡)  
  - Subtask count  
  - Created and due dates
- Interactive features:
  - Expand/collapse subtasks by clicking on a row  
  - Update task status using action buttons  
  - Filter tasks by status, priority, date range  
  - Sort tasks by due/creation date (ascending/descending)  
  - Delete tasks with confirmation
- Automatic task status update when all subtasks are completed
- Safe handling of corrupted storage and validation checks

---

## 🛠️ Technical Highlights
- Fully client-side — **no backend required**
- Reliable data persistence using `localStorage`
- Structured JSON task model with validation
- Modular, readable logic for rendering and updates
- Responsive UI for desktop and mobile
- Separation of concerns between data logic, UI logic, and styling
- Defensive coding: safe date handling, event propagation control, and error tolerance

---

## 📁 **Project Structure**

```
│── index.html # New task creation page
│── task-summary.html # Task dashboard / manager
│── README.md # Project documentation
```


---

## 🔧 How to Run
1. Open `index.html` in any modern browser  
2. Fill out and save a task  
3. Click **"View task summary"** to open the management page  
4. Filter, sort, update status, and expand subtasks interactively  

No installation, server, or dependencies are required.

---

## 📚 Future Improvements (Do not wait for them)
- Task export/import (JSON)
- Editable subtasks
- Dark mode
- Search bar
- Drag-and-drop ordering

---

## 🧑‍💻 Author
**Nadir Azizov**  

n.azizov@ufaz.az

nadirabulfazazizov@gmail.com

UFAZ — FEWP Project (2025)

---

This project is free to use for learning and academic purposes.
