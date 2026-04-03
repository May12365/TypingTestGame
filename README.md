# ⌨️ Typing Test Game

![GitHub repo size](https://img.shields.io/github/repo-size/May12365/TypingTestGame)
![GitHub stars](https://img.shields.io/github/stars/May12365/TypingTestGame?style=social)
![GitHub forks](https://img.shields.io/github/forks/May12365/TypingTestGame?style=social)

A simple and interactive **Typing Speed Test Game** built using HTML, CSS, and JavaScript.
Test your typing speed, accuracy, and performance in real-time.

---
## 📸 Video Demo
<p align="center">
  <video src="https://github.com/May12365/TypingTestGame/releases/download/v1.0.0/demo.mp4"autoplay loop muted  width="700"></video>
</p>

---

## 🌐 Live Demo

👉https://typingtestgames.netlify.app/ 

---

## 📌 Features

* ⏱️ 60-second countdown timer
* ⚡ Real-time **WPM (Words Per Minute)** calculation
* 🔤 **CPM (Characters Per Minute)**
* ❌ Mistake tracking system
* 🎯 Accuracy feedback via correct/incorrect highlighting
* 🔄 Reset / Try Again functionality
* 📝 Random paragraph generation
* 💻 Simple and clean UI

---

## 🧠 How It Works

* Random paragraph is loaded from `paragraphs.js`
* Each character is wrapped in `<span>` for tracking
* User input is compared character-by-character
* Metrics are calculated dynamically:

  * `WPM = ((typed characters - mistakes) / 5) / time * 60`
* Timer starts when user begins typing

---

## 🛠️ Tech Stack

* HTML5
* CSS3
* JavaScript

---

## 📂 Project Structure

```
TypingTestGame/
│── index.html              # Main UI
│── style.css               # Styling
│── js/
│   ├── script.js           # Game logic
│   └── paragraphs.js       # Text data source
```

---

## ⚙️ Installation

```bash
git clone https://github.com/May12365/TypingTestGame.git
cd TypingTestGame
```

Open `index.html` in a modern web browser, or run via a local development server (e.g., VS Code Live Server).

---

## 🎮 How to Play

1. A random paragraph will appear on the screen.  
2. Start typing the text **exactly as displayed**.  
3. Your typing performance will be tracked in real-time:
   - WPM (Words Per Minute)  
   - CPM (Characters Per Minute)  
   - Mistakes  
4. Each incorrect character will be counted as a mistake.  
5. Complete the test before the **time limit expires**.  
6. Click **"Try Again"** to restart and improve your score.   

---


## 📜 License

This project is created for **educational and portfolio purposes**.

---

## 👤 Author

* GitHub: https://github.com/May12365

---

