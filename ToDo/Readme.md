# L1 - Enhanced Todo List with localStorage and Search

## 📌 Features

- Add tasks to the todo list
- Mark tasks as completed by clicking on them
- Delete tasks
- Search tasks in real-time
- Saves all tasks in `localStorage`, so they remain even after refreshing the page

---

## 🏗 How It Works

1. Type a task in the input box and click **Add Task**
2. Your task appears in the list
3. Click a task to mark it as **completed**
4. Click **Delete** to remove a task
5. Use the search bar to filter tasks by name
6. The app automatically remembers your tasks using `localStorage`

---

## 💾 Storage Format

Tasks are stored in `localStorage` as a JSON array like this:

```json
[
  {
    "id": 123456789,
    "text": "Learn JavaScript",
    "completed": false
  }
]
