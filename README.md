# ⌨️ type.race — Typing Speed Game

A clean, fast, browser-based typing speed test built with vanilla HTML, CSS and JavaScript. No frameworks, no dependencies — just open and play.

![HTML](https://img.shields.io/badge/HTML-E34F26?style=flat&logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/CSS-1572B6?style=flat&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![License](https://img.shields.io/badge/License-MIT-green?style=flat)

---

## 🎮 Live Demo

> Open `index.html` directly in any browser — no server or install needed.

---

## ✨ Features

| Feature | Description |
|---|---|
| ⏱️ Real-time WPM | Words per minute calculated live as you type |
| 🎯 Accuracy tracking | Percentage of correct keystrokes shown instantly |
| ❌ Error counter | Tracks every mistake in real time |
| ⏳ Countdown timer | Choose 30s, 60s, or 120s tests |
| 🟢 Live highlighting | Green = correct, Red = wrong, animated cursor on current character |
| 🏆 Leaderboard | Top 5 personal bests saved per difficulty + duration (localStorage) |
| 🎚️ Difficulty levels | Easy, Medium, Hard — different passage complexity |
| 🔄 Instant restart | Press `Tab` anytime to get a new test |

---

## 🚀 How to Play

1. **Clone or download** this repository
2. **Open** `index.html` in your browser
3. **Click** the input box at the bottom
4. **Start typing** the passage shown above — the timer starts on your first keystroke
5. Letters turn **green** when correct, **red** when wrong
6. When the timer hits zero, your results appear automatically

### Controls

| Key | Action |
|---|---|
| Start typing | Begins the timer |
| `Tab` | Restart with a new passage |
| `Enter` | Play again (on results screen) |
| `Backspace` | Correct your last character |

---

## 📁 Project Structure

```
Typing-speed-game/
│
├── index.html      # Complete game — all HTML, CSS and JS in one file
└── README.md       # This file
```

---

## 🛠️ Run Locally with a Dev Server

If you want to run it on localhost instead of opening the file directly:

**Using Python (built-in):**
```bash
python -m http.server 3000
```
Then open [http://localhost:3000](http://localhost:3000)

**Using Node.js:**
```bash
npx serve .
```

---

## 📊 How Scoring Works

- **WPM** = `(characters typed ÷ 5) ÷ elapsed seconds × 60`
  - The standard definition: every 5 characters = 1 word
- **Accuracy** = `(total keystrokes - errors) ÷ total keystrokes × 100`
- **Leaderboard** stores your top 5 scores per mode in `localStorage` — no account needed

---

## 🗺️ Roadmap / Planned Features

- [ ] Ghost race mode — race against your personal best replay
- [ ] Per-key heatmap — see which keys slow you down
- [ ] Custom text input — paste your own passage
- [ ] Sound effects on correct / incorrect keystrokes
- [ ] Dark mode toggle
- [ ] Online leaderboard with a backend

---

## 🤝 Contributing

Contributions are welcome! Here's how:

1. **Fork** this repository (click Fork at the top right of this page)
2. **Clone** your fork:
   ```bash
   git clone https://github.com/YOUR-USERNAME/Typing-speed-game-.git
   ```
3. **Create a new branch** for your feature:
   ```bash
   git checkout -b feature/your-feature-name
   ```
4. **Make your changes** and commit them:
   ```bash
   git add .
   git commit -m "feat: add your feature description"
   ```
5. **Push** to your fork:
   ```bash
   git push origin feature/your-feature-name
   ```
6. **Open a Pull Request** on GitHub — describe what you changed and why

### Commit Message Format

Use clear, descriptive commit messages:

```
feat: add dark mode toggle
fix: correct WPM calculation on timer end
style: improve mobile layout for small screens
docs: update README with new features
refactor: simplify passage rendering logic
```

### Good First Issues to Contribute

- Add more passage texts to any difficulty level
- Improve mobile responsiveness
- Add a dark/light mode toggle
- Add sound feedback for correct/wrong keystrokes
- Write unit tests for the WPM and accuracy calculations

---

## 🐛 Reporting Bugs

Found a bug? Please [open an issue](https://github.com/joyccceee-keren/Typing-speed-game-/issues) with:
- What you expected to happen
- What actually happened
- Your browser and OS
- Steps to reproduce

---

## 📄 License

This project is open source under the [MIT License](LICENSE).

---

## 👤 Author

**joyccceee-keren**
- GitHub: [@joyccceee-keren](https://github.com/joyccceee-keren)

---

> ⭐ If you found this useful, consider giving it a star on GitHub!
