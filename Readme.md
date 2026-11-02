# 🎮 FOCUS.EXE

> Productivity ko game bana do. A gamified Pomodoro timer with a neon cyberpunk terminal UI.

Earn XP, level up, keep your streak alive, and clear your "objectives" while rain or lo-fi plays in the background. Pure HTML, CSS and JavaScript. No frameworks, no installs, no dependencies.

---

## ✨ Features

- ⏱️ **Three timer modes**: Focus, Short break, Long break, with an animated progress ring
- 🏆 **XP and levels**: every completed session earns XP, and the XP bar fills up to the next level
- 🔥 **Streak tracking**: don't break the chain
- ✅ **Mission Log**: add tasks as "objectives" and tick them off
- 📊 **Combat Stats**: total focus time, sessions completed, streak, current level
- 🎧 **Ambient audio**: Rain, White Noise and Lo-fi, generated with the Web Audio API (no audio files), with volume control
- 💾 **Progress saved locally** using `localStorage`
- 📦 **Single file**: everything lives in one HTML file

---

## 🚀 Getting Started

No setup needed.

```bash
git clone https://github.com/<your-username>/focus-exe.git
cd focus-exe
```

Then just open `index.html` (or `focus-exe.html`) in any modern browser. Done.

Or run a quick local server if you prefer:

```bash
python -m http.server 8000
# open http://localhost:8000
```

---

## 🕹️ How to Use

1. Pick a mode: **FOCUS**, **SHORT** or **LONG**
2. Add your objectives in the **Mission Log**
3. Hit ▶ to start the timer
4. Optionally turn on **Rain / Noise / Lo-fi** and adjust the volume
5. Finish sessions to earn XP, level up and build your streak

Controls: ↻ reset, ▶ start/pause, ⏭ skip.

---

## 🛠️ Tech Stack

| Layer | Tech |
|-------|------|
| Markup | HTML5 |
| Styling | CSS3 (custom properties, animations, SVG ring) |
| Logic | Vanilla JavaScript |
| Audio | Web Audio API |
| Storage | localStorage |

---

## 📁 Project Structure

```
focus-exe/
├── index.html    # the entire app
└── README.md
```

---

## 🌐 Live Demo

Enable GitHub Pages (Settings → Pages → Deploy from branch → `main`) and add your link here:

`https://<your-username>.github.io/focus-exe/`

---

## 🗺️ Roadmap

- [ ] Custom timer durations
- [ ] Daily and weekly stats history
- [ ] More ambient sounds
- [ ] Desktop notifications when a session ends

---

## 🤝 Contributing

Ideas and PRs are welcome. Fork the repo, make your changes, and open a pull request.

---

## 📄 License

MIT. Free to use, modify and share.

---

Made with ☕ and too many Pomodoros by [Shriyam](https://github.com/shriyamgupta14-sys)
