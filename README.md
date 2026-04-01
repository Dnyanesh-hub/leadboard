# 🎯 Nerf Gun Target Challenge

An interactive web-based scoring system for a **Nerf Gun Event**, designed for managing participants, tracking scores, and maintaining a live leaderboard.

This project is built using **HTML, CSS, and JavaScript** and is ideal for college events, competitions, and fun activities.

---

## 🚀 Features

- 👤 Participant registration (Name & Roll Number)
- 🎯 6-shot scoring system
- 📊 Real-time score tracking
- 🏆 Leaderboard with ranking
- 💾 Data stored using LocalStorage
- 🎨 Modern UI with animated target board
- ⚡ Fast and responsive design

---

## 🎮 How the Game Works

- Each participant gets **6 shots**
- For every shot, the scorer enters points based on hit:

| Target Zone | Points |
|------------|--------|
| Large Ring | 2 pts  |
| Medium Ring | 5 pts |
| Small Ring | 7 pts |
| Bullseye | 10 pts |
| Miss | 0 pts |

- After 6 shots:
  - Total score is calculated
  - Added to leaderboard
  - Ranked automatically

---

## 🖥️ Screens Overview

### 1️⃣ Start Screen
- Enter participant name
- Enter roll number
- Start the game

### 2️⃣ Game Screen
- Displays target board
- Shows shot count (1 to 6)
- Enter score for each shot
- Visual shot tracking

### 3️⃣ Result Screen
- Displays total score
- Options:
  - View leaderboard
  - Add next participant

### 4️⃣ Leaderboard Screen
- Shows all participants ranked by score
- Highlights latest entry
- Option to reset leaderboard

---

## 🛠️ Tech Stack

- HTML5
- CSS3 (Animations & Responsive Design)
- JavaScript (Vanilla JS)
- LocalStorage (for saving leaderboard)

---

## 📂 Project Structure

```
project/
│── index.html   # Complete application (HTML + CSS + JS)
```

---

## ▶️ How to Run

1. Download or clone the repository
2. Open `index.html` in your browser
3. Start playing 🎯

---

## 💡 Key Concepts Used

- DOM Manipulation
- Event Handling
- LocalStorage API
- Dynamic UI Rendering
- Input Validation
- State Management (JS)

---

## 📈 Future Improvements

- 🔸 Add sound effects for shots
- 🔸 Timer-based rounds
- 🔸 Admin panel for control
- 🔸 Export leaderboard (CSV/PDF)
- 🔸 Online multiplayer / backend integration
- 🔸 Authentication system

---

## ⚠️ Note

- Data is stored in browser LocalStorage
- Clearing browser data will remove leaderboard

---

## 🎯 Use Case

Perfect for:
- College fests
- Club events
- Competitions
- Fun activities

---

## 🤝 Contribution

Suggestions and improvements are welcome!

---

## 👨‍💻 Author

**Dnyaneshwar Mali**
