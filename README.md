# Tic Tac Toe (local)

A beautiful local Tic Tac Toe game with a modern, polished UI built with Python and tkinter.

## Features
- **Modern Dark Theme UI** with clean, professional design
- **Color-coded players**: Teal (X) vs Coral (O)
- **3x3 interactive board** with large buttons and hover effects
- **Local 2-player mode** for playing with friends
- **Single-player vs AI** with two difficulty levels:
  - Easy: Random moves
  - Hard: Unbeatable minimax algorithm
- **Smart scoreboard** tracking wins across games
- **Choose your side**: Play as X or O in single-player mode
- **Visual feedback**: Animated winning line highlight
- **Game controls**: rematch (keep scores) or New Game (reset everything)

Requirements
- Python 3.8+
- tkinter (usually included with standard CPython on Windows)

Quick start (Windows PowerShell)
```powershell
# (optional) create a virtualenv
python -m venv .venv
.\.venv\Scripts\Activate.ps1

# install any dependencies (none required by default)
python -m pip install -r requirements.txt

# run the game
python e:\Course\tic-tac-toe\tic_tac_toe.py
```

Usage
- Select Mode: "2 Players" or "Single Player". 
- If Single Player is selected, choose Difficulty (Easy or Hard) and choose which side you play under "You:" (X or O).
- Click a cell to place your mark. If AI starts it will move automatically.

Notes
- The game uses only the Python standard library. If tkinter is not available, install a Python distribution that includes it (official CPython installer for Windows does).
- The repository includes `pyproject.toml` for basic package metadata.

License
- MIT (feel free to change)
