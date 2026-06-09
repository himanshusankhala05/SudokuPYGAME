# 🧩 SudokuPYGAME

A desktop-based, interactive **Sudoku Game and Automated Solver** built entirely in Python using the **Pygame** library. This application provides users with a fully functional graphical interface to play Sudoku manually, track high scores via an integrated database, and visualize an automated solving mechanism powered by a classic **Backtracking Algorithm**.

---

## 🚀 Key Features

* **Interactive Gameplay Interface:** Clean grid rendering with responsive keyboard inputs to enter numbers, clear cells, and navigate the board.
* **Visualized Backtracking Solver:** Watch the algorithmic magic happen in real time! Press a hotkey to trigger the backtracking algorithm and view how it recursively explores, tests, and backtracks to solve the entire grid.
* **Automated Strike & Win Checker:** Built-in validation checking inputs against traditional Sudoku rules, highlighting errors, tracking incorrect attempts, and recognizing a completed board.
* **Score Tracking Database:** Local data persistence allowing players to log high scores, save game states, or reset historic records.

---

## 🛠️ Tech Stack & Mechanics

* **Language:** Python 3.x
* **GUI Engine:** Pygame (for window management, grid drawing, text rendering, and low-level keyboard/mouse event handling).
* **Core Algorithm:** Backtracking (Depth-First Search approach ensuring an exact, programmatic solution for any valid puzzle layout).
* **Database Layer:** SQLite (Lightweight, zero-configuration relational database to store performance statistics and player scoring history).

---

## 📁 Project Architecture

```plaintext
SudokuPYGAME/
│
├── src/
│   ├── main.py            # Primary game loop, window setup, and event dispatcher
│   ├── solver.py          # Backtracking algorithm logic and constraint checkers
│   ├── grid.py            # Board rendering, cell objects, and user input validation
│   └── database.py        # SQLite connectivity, score logger, and reset routines
│
├── assets/                # Creative elements (custom fonts, audio effects, icons)
├── requirements.txt       # Project dependencies (e.g., pygame)
└── README.md              # System documentation
