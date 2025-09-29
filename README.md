# 🔍 Search Game of Wazowski

This project explores **AI search algorithms** in the context of a **Sokoban-style puzzle game**.  
Players (or algorithms) must move boxes to goals in grid-based levels, while the project demonstrates how search techniques can automate solving such puzzles.

---

## ✨ Key Contents

### Supported Search Algorithms
- **BFS (Breadth-First Search)**
- **DFS (Depth-First Search)**
- **A\*** (A-star search)


### Python Code
- **`game.py`** — Core logic for the puzzle environment and search mechanics. Implements rules for player movement, box pushing, and win conditions.  
- **`gui.py`** — Graphical interface for playing the game interactively with sprites and sounds.

### Jupyter Notebook
- **`notebook.ipynb`** — Demonstrates and analyzes search algorithms (e.g., BFS, DFS, A*). Provides experiments on solving the included maps.

### Assets
- **Maps (`assets/maps/`)**  
  - `map1.txt` … `map10.txt` → Puzzle definitions in text format.  
  - `solutions.txt` → Stores or verifies known solutions.  
- **Sprites (`assets/sprites/`)** — Visual assets for the player, boxes, goals, portals, and environment.  
- **Sounds (`assets/sounds/`)** — Background music and sound effects for moves.

---

## 🧱 Project Structure
```
Search-Game-of-Wazowski-main/
├── game.py            # Core puzzle logic & search mechanics
├── gui.py             # Tkinter/pygame-based GUI for playing
├── notebook.ipynb     # AI search algorithm analysis
└── assets/
    ├── maps/          # Text-based levels & solutions
    ├── sprites/       # Images for game objects
    └── sounds/        # Music & sound effects
```

---

## 🎯 Research & Educational Context
This project was created to study **AI search strategies** through a fun and visual medium:  
- Classic search algorithms (BFS, DFS, A*, etc.) applied to puzzle solving  
- Evaluation of algorithm efficiency on different level sizes and complexities  
- Combination of **game development** and **AI problem solving** to illustrate core computer science concepts  

---

📚 Made for research & learning — where algorithms meet games to solve puzzles intelligently.
