# Tic Tac Toe Game

## Overview
This is a web-based Tic Tac Toe game for two players. Players take turns to place their symbol ("X" or "O") on a 3x3 grid. The game declares a winner when a player aligns three symbols in a row, column, or diagonal, or it ends in a draw.

---

## Live Demo
Check out the live demo of the game here: [Live Demo](https://preethesh26.github.io/Tic-Tac-Toe-Game/)

---

## Features
- **Interactive Gameplay**:
  - Players take turns marking the grid.
  - Winner announcement or draw notification.
- **Controls**:
  - Reset the game or start a new one using dedicated buttons.
- **Design**:
  - Clean and responsive UI styled with CSS.

---

## Files Included
- `index.html`: The structure and layout of the game.
- `style.css`: Styles for the game interface.
- `app.js`: JavaScript logic for game functionality.

---

## How to Use
1. Open the `index.html` file in any modern web browser, or access the [live demo](https://preethesh26.github.io/Tic-Tac-Toe-Game/).
2. **Gameplay**:
   - Click on a grid cell to place your mark ("X" or "O").
   - The game announces the winner or declares a draw when applicable.
3. **Buttons**:
   - **Reset Game**: Clears the current game board.
   - **New Game**: Resets the game state after a winner or draw.

---

## Game Logic
- **Turn System**:
  - Player O always starts.
  - Alternating turns for "X" and "O".
- **Winning Conditions**:
  - Three symbols in a line (row, column, or diagonal).
- **Draw Condition**:
  - Declared when all cells are filled without a winner.

---

## Customization
- Modify the grid size or winning conditions by editing the `winPatterns` array in `app.js`.
- Update styles such as colors or fonts by changing `style.css`.

---

## Example UI
- A 3x3 grid with buttons for gameplay.
- Winner or draw notification displayed dynamically.

---

## Future Enhancements
- Single-player mode with AI.
- Animations for marking grid cells.
- Scoreboard to track player performance.

---

Enjoy the game! 🎉
