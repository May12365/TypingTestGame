# ⌨️ Typing Test Game

![GitHub repo size](https://img.shields.io/github/repo-size/May12365/TypingTestGame)
![GitHub stars](https://img.shields.io/github/stars/May12365/TypingTestGame?style=social)
![GitHub forks](https://img.shields.io/github/forks/May12365/TypingTestGame?style=social)
![License](https://img.shields.io/badge/license-MIT-green)

A simple and interactive **Typing Speed Test Game** built using HTML, CSS, and JavaScript.
Test your typing speed, accuracy, and performance in real-time.

---

## 🌐 Live Demo

👉 https://typingtestgames.netlify.app/

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
* Vanilla JavaScript

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

1. Start typing the given text
2. Track your performance:

   * WPM
   * CPM
   * Mistakes
3. Complete before time runs out
4. Click **Try Again** to restart

---

## 📸 Demo

> Add a GIF demo using tools like:
>
> * ScreenToGif
> * LICEcap

---

## 🚀 Deploy on GitHub Pages

1. Go to **Settings**
2. Click **Pages**
3. Under **Branch**, select:

   * `main`
   * `/ (root)`
4. Click **Save**

Your site will be available at:

```
https://<your-username>.github.io/TypingTestGame/
```

---

## 🤝 Contributing

Contributions are welcome!

1. Fork this repository
2. Create a new branch
3. Commit your changes
4. Submit a Pull Request

---

## 📜 License

This project is licensed under the MIT License.

---

## 👤 Author

* GitHub: https://github.com/May12365

---

## ⭐ Support

If you found this project useful, please consider giving it a ⭐!
