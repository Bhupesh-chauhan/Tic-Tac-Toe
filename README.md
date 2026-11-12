# Tic Tac Toe

A classic, interactive Tic Tac Toe game built using pure **HTML**, **CSS**, and **JavaScript**. No external libraries or frameworks required.

## 🌐 Live Demo
https://tic-tac-toe-fzi1.onrender.com

## 🎮 Features

* **Two-Player Gameplay:** Play locally with a friend (Player X vs. Player O).
* **Win & Draw Detection:** Automatically detects horizontal, vertical, and diagonal wins, as well as draw games.
* **Turn Indicator:** Displays whose turn it is in real time.
* **Game Reset:** Easily clear the board and start a new round with a single click.
* **Responsive Design:** Clean layout that works smoothly across desktop and mobile browsers.

## 🛠️ Built With

* **HTML5** – Structure and layout of the game board.
* **CSS3** – Styling, grid layout, and hover effects.
* **JavaScript (ES6)** – Game logic, state management, and DOM manipulation.

## 📂 Project Structure

```text
tic-tac-toe/
├── index.html      # Main HTML file
├── style.css       # Stylesheet for layout and design
├── script.js       # Game logic and interactivity
└── README.md       # Project documentation
```

## 🚀 How to Run Locally

Since this project uses vanilla web technologies, you don't need to install any dependencies.

1. **Clone the repository:**
   ```bash
   git clone https://github.com[your-username]/[your-repo-name].git
   ```
2. **Navigate to the project folder:**
   ```bash
   cd [your-repo-name]
   ```
3. **Open the game:**
   Double-click `index.html` to open it in your default web browser, or run it using a local development server (such as the VS Code Live Server extension).

## ☁️ Deployment (Render)

This project is hosted on https://tic-tac-toe-fzi1.onrender.com

1. Push the code to a GitHub/GitLab repository with `index.html` in the root folder.
2. On Render, select **New +** > **Static Site** and connect the repository.
3. Leave the **Build Command** blank and set the **Publish Directory** to `.`.
4. Click **Create Static Site** to deploy.

## 🕹️ How to Play

1. The game starts with **Player X**.
2. Players take turns clicking on an empty square in the 3×3 grid.
3. The first player to get **3 of their marks in a row** (horizontally, vertically, or diagonally) wins the game.
4. If all 9 squares are filled and neither player has 3 in a row, the game ends in a **Draw**.
5. Click the **Restart / Reset** button at any time to play again.

## 📄 License

This project is open-source and available under the [MIT License](LICENSE).
