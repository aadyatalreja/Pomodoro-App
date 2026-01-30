# ⏱️ Pomodoro Timer with To-Do List

A modern, aesthetic, and user-friendly **Pomodoro Timer web application** built using **plain HTML, CSS, and JavaScript**.  
The app helps users stay focused using the Pomodoro Technique, manage tasks with an integrated to-do list, and switch seamlessly between **Light and Dark modes**.

---

## Features

### Pomodoro Timer
- Default **25-minute focus session**
- Start, Pause, and Reset controls
- Accurate countdown using `setInterval`
- Prevents multiple timers running simultaneously
- Displays completion message when time ends

### Session Management
- Preset modes:
  - Focus (25 min)
  - Short Break (5 min)
  - Long Break (15 min)
- Optional custom duration support
- Session completion counter (Pomodoros completed)

### Progress Visualization
- Smooth animated progress bar
- Updates every second
- Resets correctly on mode or duration change

### Integrated To-Do List
- Add, complete, and delete tasks
- Highlight the active task during a focus session
- Completed tasks shown with visual distinction
- Tasks persist using `localStorage`

### Light / Dark Mode
- Toggle between Light and Dark themes
- Smooth theme transitions
- User preference saved in `localStorage`

### Sound & Accessibility
- Sound alert when a session completes
- Mute / Unmute option
- Keyboard shortcuts:
  - `Space` → Start / Pause
  - `R` → Reset

### Technologies Used
- **HTML5** – Structure
- **CSS3** – Styling, animations, themes
- **JavaScript (ES6)** – Timer logic, interactivity
- **Browser APIs** – `setInterval`, `localStorage`, DOM manipulation

### How to Run

1. Clone this repository or download the files
2. Open `index.html` in any modern web browser
3. Start focusing!

No installations or dependencies required.

### Key Learnings
- Managing timers safely using `setInterval`
- Preventing race conditions and multiple intervals
- DOM manipulation and UI state handling
- Using CSS variables for theming
- Persisting data with `localStorage`


