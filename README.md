# 🎯 Daily Habit Tracker

<div align="left">
  <img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" alt="React" />
  <img src="https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white" alt="Vite" />
  <img src="https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white" alt="Tailwind CSS" />
  <img src="https://img.shields.io/badge/DaisyUI-5A0EF8?style=for-the-badge&logo=daisyui&logoColor=white" alt="DaisyUI" />
  <img src="https://img.shields.io/badge/React_Router-CA4245?style=for-the-badge&logo=react-router&logoColor=white" alt="React Router" />
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript" />
</div>

<br />

A sleek, responsive, and interactive Daily Habit Tracker built with **React** and **Vite**. It allows users to set custom daily goals, track real-time progress, and maintain consistency with automated browser persistence.

This project highlights clean component architecture, dynamic conditional rendering, and seamless **LocalStorage** synchronization.

---

### Live Demo: [https://masihcodes.github.io/Habit-Tracker/](https://daily-habit-tracker.vercel.app/)

___

### ✨ Key Features

* **📊 Real-Time Progress Dashboard:** Visualizes overall daily completion using dynamic progress bars and radial percentage charts.
* **⚡ 3-State Smart Cards:** Habits dynamically transform their UI based on progress:
  * 💤 *Not Started:* Greyed-out state with disabled decrement.
  * ⏳ *In Progress:* Active state with animated indicators and quick increment/decrement controls.
  * 🎉 *Completed:* Rewarding green UI with strike-through text and quick-delete options.
* **💾 Persistent Storage:** Automatically syncs and retrieves your daily habits from `localStorage` so your progress is never lost.
* **🎨 Modern UI/UX:** Fully responsive design styled with **Tailwind CSS** and **DaisyUI**, featuring smooth hover effects and transitions.

---

### 💡 What I Learned

* **Implementing complex conditional rendering** in React to serve different UI layouts based on component state.
* **Syncing React state** (`useState` and `useEffect`) directly with browser `localStorage` using lazy initial state setup.
* **Structuring clean, reusable functional components** with clear prop drilling (`App` ➔ `Overall`, `Adder`, `Card`).
* **Leveraging DaisyUI component classes** (like `radial-progress` and `badge`) for rapid, professional UI development.

