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

- ⏱️ 60-second countdown timer
- ⚡ Real-time **WPM (Words Per Minute)** calculation
- 🔤 **CPM (Characters Per Minute)**
- ❌ Mistake tracking system
- 🎯 Accuracy feedback via correct/incorrect highlighting
- 🔄 Reset / Try Again functionality
- 📝 Random paragraph generation
- 💻 Simple and clean UI

---

## 🧠 How It Works

- Random paragraph is loaded from `paragraphs.js`
- Each character is wrapped in `<span>` for tracking
- User input is compared character-by-character
- Metrics are calculated dynamically:
  - WPM = ((typed characters - mistakes) / 5) / time * 60
- Timer starts when user begins typing

---

## 🛠️ Tech Stack

- HTML5
- CSS3
- Vanilla JavaScript

---

## 📂 Project Structure
TypingTestGame/
│── index.html # Main UI
│── style.css # Styling
│── js/
│ ├── script.js # Game logic
│ └── paragraphs.js # Text data source


---

## ⚙️ Installation & Usage
⚙️ Installation Guide

Follow the steps below to set up and run the project locally:

## 1. Clone the Repository
git clone https://github.com/May12365/TypingTestGame.git
## 2. Navigate to the Project Directory
cd TypingTestGame
## 3. Launch the Application
Since this is a client-side web application, no build tools or dependencies are required.

Simply open the index.html file in your preferred web browser:

# Option 1: Open manually
Double-click index.html

# Option 2: Use VS Code Live Server (recommended)
Right-click → "Open with Live Server"

🎮 How to Play
Start typing the given text
Track your performance:
WPM
CPM
Mistakes
Complete before time runs out
Click Try Again to restart
📸 Demo (Recommended)

Add GIF here using tools like:

ScreenToGif
LICEcap
🚀 Deploy on GitHub Pages
Go to Settings
Click Pages
Select:
Branch: main
Folder: /root
Save

Your site will be live at:

https://<your-username>.github.io/TypingTestGame/


Contributions are welcome!

##Fork this repo
Create a new branch
Commit your changes
Submit a Pull Request
📜 License

This project is licensed under the MIT License.

##👤 Author
GitHub: https://github.com/May12365
