# Boggle Game

![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)
![Node.js](https://img.shields.io/badge/Node.js-43853D?style=for-the-badge&logo=node.js&logoColor=white)

## 📖 Description
A classic, interactive browser-based Boggle game built from scratch. This project features a 4x4 grid that randomizes dice arrays on every load to generate unique boards. Players can click adjacent dice to construct words, submit them for points based on standard Boggle scoring, and track their total scores in a dynamic table. The underlying logic manages complex state, such as enforcing adjacent-only tile selection, preventing duplicate word submissions, and validating minimum character lengths. 

## 📸 Screenshots & GIFs

*(Note: Replace the placeholder links below with your actual image paths once uploaded to your repository)*

![Gameplay Screenshot](./path/to/screenshot.png)
![Gameplay GIF](./path/to/gameplay.gif)

## ✨ Features
* **Randomized Board Generation:** Simulates real Boggle by randomly selecting one letter from 16 distinct 6-sided dice arrays and shuffling their board placement.
* **Strict Adjacent Selection:** Mathematical index checking prevents players from selecting non-adjacent tiles or jumping across the board.
* **Dynamic Scoring System:** Automatically calculates and adds points based on word length (e.g., 3-4 letters = 1 point; 8+ letters = 11 points).
* **Duplicate Word Prevention:** Tracks previously guessed words in an array and alerts the user if they attempt to submit the same word twice.
* **Responsive Design:** A custom UI built with CSS Grid and Flexbox, featuring interactive states (`.selected`) and a nature-inspired color palette using the "National Park" font.

## 🛠️ Tech Stack
* **Frontend:** HTML5, CSS3, Vanilla JavaScript (ES6+)
* **Backend / Tooling:** Node.js, Express, ESLint

## 🚀 How to Run Locally

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/lilred92/boggle-game.git](https://github.com/lilred92/boggle-game.git)
   ```
2. **Navigate into the directory:**
   ```bash
   cd boggle-game/boggle-game-a87d35599230740646b48bc135b0c2ab52d39b34
   ```
3. **Install Dependencies:**
   ```bash
   npm install
   ```
4. **Launch the game:**
   Since the current iteration is primarily Vanilla JS, you can open the `index.html` file in your preferred web browser, or use an extension like VS Code's Live Server.

## 🔑 Environment Variables

Currently, this project runs client-side and does not require any environment variables.

## 📡 API Reference

No external APIs are currently integrated. Future updates will include internal API routing for dictionary validation against a database.

## 🗓️ Future Feature Updates

- [ ] Transition to a React-Vite project.
- [ ] Transition codebase to TypeScript for stronger type safety.
- [ ] Link to a Database to host a comprehensive word dictionary.
- [ ] Implement a Trie data structure for faster, highly optimized word validation.