# ♟️ Checkers Game – Red vs White with AI (Pygame)

This is a Python-based Checkers (Draughts) game implemented using **Pygame**, where a human player competes against an AI opponent powered by the **Minimax algorithm**. The game features a traditional **Red vs White** theme with a clean graphical interface and intelligent move handling.

---

## 🧠 Features

- 🎮 Human vs AI gameplay
- 🤖 AI powered by the Minimax decision-making algorithm
- 👑 Automatic promotion to king with crown image
- 🎨 Classic Red vs White board design
- 🖱️ Mouse interaction to select and move pieces
- 🔵 Highlights valid moves visually for ease of play

---

## 🚀 Getting Started

### Prerequisites:

- Python 3.6 or higher
- Pygame

### To install Pygame:
-pip install pygame

---

### Running the Game:
python main.py

## 📁 Project Structure
checkers-game/

│

├── assets/

│   └── crown.png               # Icon used when a piece becomes king

│

├── checkers/

│   ├── __init__.py             # (if needed)

│   ├── board.py                # Board layout, movement logic

│   ├── constants.py            # Color and layout settings

│   ├── game.py                 # Game control logic

│   ├── piece.py                # Piece drawing and king logic

│   └── minimax/

│       └── algorithm.py        # AI move calculation


│

├── main.py                     # Main loop to launch game

└── README.md

---

## 🤖 AI Logic
The AI uses the Minimax algorithm (depth = 4 by default) to:

-Simulate future board states

-Evaluate best possible moves

-Prioritize capturing and promoting to king

-Each move considers a few steps ahead to make intelligent decisions.

---

## 🔧 Future Improvements
-Add difficulty settings (easy, medium, hard)

-Alpha-beta pruning to speed up AI

-Multiplayer mode (local or online)

-Undo/Redo move support

-Score display and restart menu

-Sound effects and animations
