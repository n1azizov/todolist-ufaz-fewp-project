# ✅ **To-Do List Web Application**  
*A clean, mobile-friendly task manager built using HTML, CSS, and JavaScript.*

This project is a browser-based To-Do List application that allows users to create, organize, and manage tasks with priorities, statuses, categories, colors, and subtasks. All data is stored locally in the user's browser using **localStorage** — no backend required.

## 🚀 **Features**

### 🔹 Task Creation Page  
*(See: `index.html`)*  
Users can create detailed tasks with:

- **Title, Description, Due Date**
- **Priority levels** (Very Low → Critical)
- **Status** (Not Ready, In Progress, Done)
- **Categories** (Home, Work, University)
- **Color tags** with emoji indicators
- **Subtasks** (one per line, auto-generated IDs)
- All fields validated before saving  
- Automatically stored in **localStorage**

---

### 🔹 Task Summary / Dashboard  
*(See: `task-summary.html`)*  
A dynamic task management interface:

- Full task table with sorting & filtering:
  - By **status**
  - By **priority**
  - By **date range**
  - By **sorting order** (created or due date)
- Collapsible subtasks panel under each task
- Inline status-changing buttons
- Delete button for each task
- Color tags displayed visually (🔴🟢🔵🟡)
- Fully mobile-responsive (horizontal scroll enabled)

---

## 🧠 **Technical Highlights**

- Written using **pure HTML, CSS, and JavaScript** — no frameworks  
- Uses **localStorage** to persist tasks between sessions  
- Auto-generated task IDs & subtask IDs  
- Custom UI components with badges, pills, and responsive design  
- Clean and accessible layout  
- Fully functional CRUD operations (create, update, delete)  
- Multiple inline `<script>` blocks handling data injection  
- All dataset lists (priority, status, categories, color tags) stored in JS arrays  

---

## 📱 **Mobile Friendly**
Both pages are optimized for:

- Small screens  
- Responsive layouts  
- Scrollable tables  
- Touch-friendly buttons  

---

## 📁 **Project Structure**

```
│── index.html # New task creation page
│── task-summary.html # Task dashboard / manager
│── README.md # Project documentation
```

---

## 🛠️ **How It Works**

1. User fills the form on `index.html`
2. JavaScript validates & converts the data into a task object
3. Task is stored in localStorage under key `"taskList"`
4. `task-summary.html` reads this data and builds an interactive table
5. User can:
   - Update status  
   - Expand subtasks  
   - Mark subtasks as complete  
   - Delete tasks  
6. All changes update localStorage live

---

## 🌟 **Author**

**Nadir Azizov**  
n.azizov@ufaz.az
nadirabulfazazizov@gmail.com
UFAZ – Computer Science  
2025 L1 S1 Front-End Web Programming Project

---

## 📜 License

This project is free to use for learning and academic purposes.
