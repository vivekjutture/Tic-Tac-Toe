# 🎮 Tic-Tac-Toe Game



![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![License](https://img.shields.io/badge/License-MIT-green.svg?style=for-the-badge)

**A classic Tic-Tac-Toe game** built with vanilla HTML, CSS, and JavaScript. Play against a friend directly in your browser with a clean, responsive interface and smooth animations.

---
## 🎮 Live Demo

### [🌐 Play the Game Online →](https://vivekjutture.github.io/Tic-Tac-Toe)

_Enjoy a quick game in your browser—no installation needed!_


## ✨ Features

| Feature                         | Description                                                            |
| ------------------------------- | ---------------------------------------------------------------------- |
| 👥 **Two-Player Gameplay**      | Play as Player 1 (X) and Player 2 (O) taking turns                     |
| 🔔 **Real-time Status Updates** | Dynamic game status display showing whose turn it is                   |
| 🏆 **Win Detection**            | Automatic detection of winning combinations (rows, columns, diagonals) |
| 🤝 **Draw Detection**           | Recognizes when the board is full with no winner                       |
| 🔄 **Reset Functionality**      | Quick reset button to start a new game anytime                         |
| 📱 **Responsive Design**        | Works seamlessly on desktop and mobile devices                         |
| ✨ **Smooth Animations**        | Hover effects and visual feedback on interactions                      |
| 🚀 **No Dependencies**          | Pure vanilla JavaScript—no frameworks or libraries required            |

## 🛠️ Tech Stack



| Technology                                                                                                        | Purpose                                      |
| ----------------------------------------------------------------------------------------------------------------- | -------------------------------------------- |
| ![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)                  | Semantic markup and structure                |
| ![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)                     | Modern styling with flexbox and grid layouts |
| ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)   | Game logic and interactivity                 |
| ![Google Fonts](https://img.shields.io/badge/Google%20Fonts-4285F4?style=flat-square&logo=google&logoColor=white) | Typography (Poppins font family)             |



## 📂 Project Structure

```
📦 Tic-Tac-Toe/
 ┣ 📄 index.html       # 🎯 Main HTML file with game board and UI
 ┣ 🎨 style.css        # 🖌️ Styling for the game interface
 ┣ ⚙️ script.js        # 🧠 Game logic and event handlers
 ┣ 🖼️ images/          # 📸 Game assets and icons
 ┣ 📋 LICENSE          # ⚖️ MIT License
 ┣ 📖 README.md        # 📚 This file
 └ 💰 FUNDING.yml      # 💸 Funding information
```

## 🚀 Getting Started

### 🌐 Option 1: Play Online



Simply click the link below and start playing!

### [👉 Play Now 👈](https://vivekjutture.github.io/Tic-Tac-Toe)



### 💻 Option 2: Run Locally

1. **📥 Clone the repository:**

   ```bash
   git clone https://github.com/vivekjutture/Tic-Tac-Toe.git
   cd Tic-Tac-Toe
   ```

2. **📂 Open in browser:**
   - Double-click `index.html` to open in your default browser

3. **🎮 Start playing!**



## 📖 How to Play

1. ▶️ **Game Start** - Player 1 (X) goes first
2. 🔄 **Taking Turns** - Click any empty cell to place your mark
3. 🏆 **Win Condition** - Get three of your marks in a row (horizontal, vertical, or diagonal)
4. 🤝 **Draw** - If all 9 cells are filled with no winner, the game is a draw
5. 🔁 **Reset** - Click the "Reset Game" button to start a new game

### 🎮 Game Controls

| Action           | Method                            |
| ---------------- | --------------------------------- |
| **Place Mark**   | Click on any empty cell           |
| **Reset Game**   | Click "Reset Game" button         |
| **Refresh Page** | Press F5 or Ctrl+R (Cmd+R on Mac) |

## 🎯 Game Logic Details

### Board Representation

The game board is represented as an array of 9 positions:

```
0 | 1 | 2
---------
3 | 4 | 5
---------
6 | 7 | 8
```

### Winning Combinations

```javascript
[
  [0, 1, 2], // Top row
  [3, 4, 5], // Middle row
  [6, 7, 8], // Bottom row
  [0, 3, 6], // Left column
  [1, 4, 7], // Middle column
  [2, 5, 8], // Right column
  [0, 4, 8], // Diagonal (top-left to bottom-right)
  [2, 4, 6], // Diagonal (top-right to bottom-left)
];
```
## 📱 Browser Compatibility



| Browser                                                                                                    | Support            |
| ---------------------------------------------------------------------------------------------------------- | ------------------ |
| ![Chrome](https://img.shields.io/badge/Chrome-4285F4?style=flat-square&logo=google-chrome&logoColor=white) | ✅ Fully Supported |
| ![Firefox](https://img.shields.io/badge/Firefox-FF7139?style=flat-square&logo=firefox&logoColor=white)     | ✅ Fully Supported |
| ![Safari](https://img.shields.io/badge/Safari-000000?style=flat-square&logo=safari&logoColor=white)        | ✅ Fully Supported |
| ![Edge](https://img.shields.io/badge/Edge-0078D4?style=flat-square&logo=microsoft-edge&logoColor=white)    | ✅ Fully Supported |



## 📝 License

📜 This project is licensed under the **MIT License**. See the [LICENSE](LICENSE) file for details.

---

## 👤 Author



**Vivek Utture**

[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/vivekjutture)
[![Repository](https://img.shields.io/badge/Repository-Tic--Tac--Toe-blue?style=for-the-badge)](https://github.com/vivekjutture/Tic-Tac-Toe)



## 🤝 Contributing

🎉 Contributions are welcome! Feel free to:

- 🐛 Report bugs by opening an issue
- 💡 Suggest enhancements
- 🔧 Submit pull requests with improvements



### We appreciate every contribution! 🙌



## 💡 Future Enhancements

🚀 Potential features for future versions:

- 🤖 Single-player mode with AI opponent
- 📊 Score tracking across multiple games
- 🎯 Difficulty levels for AI
- 🔊 Sound effects and animations
- ⌨️ Keyboard controls
- 🌓 Dark/Light theme toggle

___