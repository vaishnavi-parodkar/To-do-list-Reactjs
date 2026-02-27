# To-Do-List Using React.js 

A simple and elegant **To-Do List application built with React** that helps users manage daily tasks efficiently. The app supports adding, deleting, reordering, and marking tasks as completed, with persistent storage using the browser’s `localStorage`.

---

## 🚀 Features

* ➕ Add new tasks
* ❌ Delete tasks
* ✅ Mark tasks as completed (with strike-through effect)
* 🔼 Move tasks up and down in the list
* 💾 Persistent data storage using `localStorage`
* ⌨️ Add tasks using the **Enter key**
* 🎨 Clean, dark-themed UI with responsive styling

---

## 🛠️ Tech Stack

* **React** (Functional Components & Hooks)
* **JavaScript (ES6+)**
* **CSS3**
* **Vite** (for fast development and build)

---

## 📂 Project Structure

```
src/
│── App.jsx          # Root component
│── ToDoList.jsx     # Main To-Do List logic and UI
│── index.css        # Global and component styling
│── main.jsx         # React DOM rendering
│── index.html
```

---

## ⚙️ Installation & Setup

1. **Clone the repository**

   ```bash
   git clone https://github.com/your-username/your-repo-name.git
   ```

2. **Navigate to the project directory**

   ```bash
   cd your-repo-name
   ```

3. **Install dependencies**

   ```bash
   npm install
   ```

4. **Start the development server**

   ```bash
   npm run dev
   ```

5. Open your browser and visit:

   ```
   http://localhost:5173
   ```

---

## 📸 Screenshots 

<img width="1257" height="987" alt="image" src="https://github.com/user-attachments/assets/7ca409bc-6a76-4abc-b44f-9dc29838442a" />

---

## 🧠 How It Works

* React `useState` is used to manage tasks and input state.
* React `useEffect` syncs tasks with `localStorage`.
* Tasks are stored as objects containing:

  ```js
  {
    text: "Task name",
    completed: false
  }
  ```
* Task reordering is handled using array element swapping.

---

## 🔮 Future Enhancements

* Edit existing tasks
* Clear all completed tasks
* Due dates and priority levels
* Animations for task actions
* Mobile-first UI improvements

---

## 📬 Contact

For any queries or collaborations, feel free to connect:

**Vaishnavi Parodkar**  

📧 Email: vaishnaviparodkar@gmail.com

🔗 GitHub: [@vaishnavi-parodkar](https://github.com/vaishnavi-parodkar)

---
