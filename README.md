# 🎮 Tic Tac Toe (Python Console Game)

A simple two-player Tic Tac Toe game built using Python.
Play directly in the console, and the game automatically saves and loads progress using a local file.

---

## 🧩 Features

* Classic **3x3 Tic Tac Toe** gameplay.
* Two-player alternating turns (`X` and `O`).
* Input validation for rows and columns.
* **Automatic save and load** from `game.txt`:

  * Resume your previous game on restart.
  * Automatically updates the file after every move.
* Simple, readable code for beginners to learn from.

---

## 🗂️ Project Structure

```
tic_tac_toe/
│
├── main.py        # The main game file
├── game.txt       # Auto-generated save file (after first run)
└── README.md      # Project documentation
```

---

## ▶️ How to Run

### 1. Clone the Repository

```bash
git clone https://github.com/<your-username>/tic-tac-toe-python.git
cd tic-tac-toe-python
```

### 2. Run the Game

Make sure you have **Python 3.x** installed, then run:

```bash
python main.py
```

### 3. Play the Game

* Enter your move as a row and column number (0–2).
* Example:

  ```
  Player x, choose your move (0–2):
  Row: 1
  Column: 2
  ```
* The board updates and saves automatically after each move.

---

## 💾 Save & Load

* Game progress is saved automatically to `game.txt` after every turn.
* When you restart the game, it loads the previous board state.
* If no save file exists, a new game starts automatically.

---

## 🧠 Concepts Used

* Lists and nested lists
* Loops and conditional logic
* File read/write operations (`open`, `read`, `write`)
* Function definitions and modular programming

---

## 📜 License

This project is open-source and available under the [MIT License](LICENSE).

---

**Developed by:** *Amira Adawy Zaki*
💻 .NET Backend Developer | 🎓 Ain Shams University (Class of 2025)
