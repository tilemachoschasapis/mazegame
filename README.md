# 🧩 Maze Finder: 2-Player Maze Race Game

**Maze Finder** is a fast-paced, competitive 2-player maze game built with **Pygame**. Players race to reach the purple square goal, avoiding animated obstacles and maze walls. The game tracks time and declares a winner after three rounds.

---

## 🎮 Gameplay

- **Player 1 (White Box) – Arrow Keys:**
  - Move Up: `↑`
  - Move Down: `↓`
  - Move Left: `←`
  - Move Right: `→`

- **Player 2 (Green Box) – WASD Keys:**
  - Move Up: `W`
  - Move Down: `S`
  - Move Left: `A`
  - Move Right: `D`

- **Objective**: Be the first to reach the purple square.
- **Rounds**: The game is played over 3 rounds. Each round tracks the time it takes each player to reach the goal.
- **Winner**: The player with the most wins after 3 rounds is declared the overall winner.

---

## ⚙️ Features

- Dynamic obstacles that move and resize.
- Thread-based animations for challenge.
- Collision detection with maze walls and players.
- Time tracking and winner announcements.
- Smooth 60 FPS gameplay.

---

## 🧠 Dependencies

Make sure you have **Python 3.x** installed. Install Pygame using pip:

```bash
pip install pygame
