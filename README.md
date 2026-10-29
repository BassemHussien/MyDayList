# MyDayList 📋

A responsive, single-page task management web app for organizing tasks, planning deadlines, and tracking focus time — built entirely with vanilla HTML, CSS, and JavaScript. No frameworks, no libraries, no build step.

![Vanilla JS](https://img.shields.io/badge/JavaScript-Vanilla-yellow)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)
![No Dependencies](https://img.shields.io/badge/dependencies-0-brightgreen)
![License](https://img.shields.io/badge/license-MIT-blue)

---

## ✨ Features

### 🗂️ Multi-View Single-Page App
- **Home dashboard** — daily overview and quick stats
- **Task list** — full CRUD task management
- **Kanban board** — drag-and-drop columns
- **Calendar** — schedule tasks by dropping them onto days
- **Focus timer** — Pomodoro-style session tracking
- **Settings** — themes, accents, and preferences
- Hash-based client-side router keeps navigation snappy without page reloads

### ✅ Task Management
- Create, edit, complete, and delete tasks
- Priorities (low / medium / high), due dates, and descriptions
- Real-time **search**, **filtering** (status, priority, date), and **sorting**
- Automatic persistence via `localStorage` — data survives refreshes and browser restarts

### 🖱️ Drag & Drop
- Powered by the native **HTML5 Drag and Drop API**
- Move cards between **Kanban columns** to update status
- **Drop tasks onto a calendar day** to schedule a due date

### ⏱️ Focus Timer (Pomodoro)
- Automatic **focus → break → focus** cycles
- **Per-task session tracking** and **daily statistics**
- Keeps running **across page navigation** inside the SPA
- Audio alert on cycle completion via the **Web Audio API** (no audio files needed)

### 🎨 Customisable UI
- **Light, dark, and system** theme modes
- Selectable **accent colours**
- **Glassmorphism** effects using `backdrop-filter`
- Smooth CSS animations built with **CSS custom properties**
- Respects the **`prefers-reduced-motion`** preference

### 📱 Accessible & Responsive
- Fully responsive layout for **desktop and mobile**
- **Keyboard-friendly** controls and focus management
- **ARIA labels** throughout for screen reader support

---

## 🚀 Getting Started

### Prerequisites
None. This is a static site with zero dependencies.

### Run Locally

```bash
# Clone the repository
git clone https://github.com/your-username/mydaylist.git
cd mydaylist
```

Then simply open `index.html` in your browser — or serve it locally for the best experience:

```bash
# Python 3
python -m http.server 8000

# or Node.js
npx serve .
```

Visit `http://localhost:8000`.
