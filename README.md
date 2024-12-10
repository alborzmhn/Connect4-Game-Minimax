
# 🎮 Connect 4 AI Game

This repository contains an implementation of the classic Connect 4 game with an AI opponent powered by the Minimax algorithm with Alpha-Beta pruning.

---

## 📁 Project Contents

- **Game.py** - The main game file containing the implementation of the Connect 4 game, AI logic, and game loop.

---

## 🕹️ Game Features

- **Game Mechanics:**
  - Two-player game: Human vs. AI.
  - Classic Connect 4 rules (four in a row to win).
  - Board size: 6 rows x 7 columns.
  
- **AI Features:**
  - **Minimax Algorithm** with Alpha-Beta pruning.
  - Heuristic-based scoring for optimal decision-making.
  - Configurable AI search depth for difficulty adjustment.
  - Randomness in AI decisions for unpredictability.

---

## 🎯 How to Play

1. **Run the Game:** Execute `Game.py` using Python 3.
   ```bash
   python3 Game.py
   ```
2. **Gameplay:**
   - The game window opens, and the board is displayed.
   - Red pieces represent the player.
   - Yellow pieces represent the AI.
   - Click on a column to place a piece.

3. **Winning Conditions:**
   - Four connected pieces horizontally, vertically, or diagonally.
   - The game announces the winner or a draw if the board is full.

---

## 🧠 AI Logic Overview

- **Minimax with Alpha-Beta Pruning:**
  - Evaluates potential moves up to a given depth.
  - Uses a heuristic scoring function to evaluate board states.
  - Prunes branches of the search tree that won't affect the final decision.

- **Heuristic Evaluation:**
  - Scores board positions based on potential winning combinations.
  - Prefers center columns and longer chains of connected pieces.

- **Difficulty Adjustment:**
  - Search depth can be configured in the game settings.

---

## 🚀 Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/YourUsername/YourRepo.git
   ```

2. Navigate to the project directory:
   ```bash
   cd YourRepo
   ```

3. Run the game:
   ```bash
   python3 Game.py
   ```

