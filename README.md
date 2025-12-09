# 🐍 Snake AI Demo

## Overview

**Snake AI Demo** is a modern version of the classic Snake game, built with **Python** and **Pygame**.  
This project demonstrates how a simple AI agent ⚡ can automatically control the snake to eat apples 🍎 while avoiding walls and its own body.

- Grid-based gameplay on a 20x20 board
- Apples 🍎 spawn in a safe zone, avoiding corners and edges for smoother AI performance
- The snake 🐍 grows longer after eating apples
- Game ends if the snake 🐍 hits the wall 🧱 or itself

---

## Features

### 1. AI-Controlled Snake ⚡
- **Greedy path selection**: AI moves the snake 🐍 in the direction that reduces the distance to the apple 🍎
- **Collision avoidance**: prevents hitting walls 🧱 or the snake’s body 🐍
- **Fallback logic**: if the preferred path is blocked, AI selects an alternative safe direction
- Demonstrates how a simple AI ⚡ can outperform human players

### 2. Manual Play 🎮
- Control the snake 🐍 using arrow keys
- Press **Space 🔄** to restart after game over
- Real-time score ⭐ display on the screen

---

## Installation 🛠️

1. Ensure **Python 3.x** is installed  
   Check Python version:

   ```bash
   python --version
   ```

2. Create and activate a virtual environment (optional but recommended)
```
python -m venv venv
source venv/bin/activate   # Linux/Mac
venv\Scripts\activate      # Windows
```

3. Install Pygame
```
pip install pygame
```

4. Clone the repository
```
git clone <repo-url>
cd snake-ai-demo
```

## How to Run ▶️
```
python snake_ai.py
```
- The AI ⚡ will automatically control the snake 🐍

- You can also play manually using the arrow keys 🎮

## How the AI Works ⚡

The AI is rule-based, not machine learning 🤖. Each frame, it performs the following steps:

1. Calculate optimal direction toward the apple 🍎

2. Check safety: ensure the next move does not hit walls 🧱 or the snake 🐍

3. Fallback: choose an alternative safe direction if the preferred path is blocked

=> This results in more stable gameplay and higher average scores ⭐

Advanced options for development:

- Implement pathfinding algorithms (BFS / A*)

- Apply reinforcement learning (Q-learning) to maximize survival and apples eaten 🍎

## Notes 📝

- Current AI ⚡ is basic but effective for demonstration purposes

- Designed as a demo to showcase AI logic in games

## License 📜

This project is licensed under the MIT License:

- Free to use, modify, and distribute

- No warranty; authors are not responsible for any damages

