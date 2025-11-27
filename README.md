Snake AI Demo


Overview

Snake AI Demo is a modern implementation of the classic Snake game using Python and Pygame.
This version introduces a simple AI agent that automatically navigates the snake toward apples while avoiding obstacles, demonstrating basic decision-making and AI logic in a game environment.

Grid-based gameplay on a 20x20 board

Apples spawn randomly in a safe zone to minimize immediate collisions

The snake grows in length after eating an apple

The game ends if the snake collides with walls or itself

Features
AI-Controlled Snake

Greedy path selection: the AI chooses the direction that reduces distance to the apple

Collision avoidance: AI avoids walls and its own body

Fallback logic: if the preferred direction is blocked, AI selects an alternative safe path

Demonstrates how simple AI can outperform human reflexes in predictable scenarios

Manual Play

Control the snake using arrow keys

Press Space to restart after game over

Real-time score display

Installation

Ensure you have Python 3.x installed. Then install Pygame:

pip install pygame


Clone the repository:

git clone <repo-url>
cd snake-ai-demo

How to Run
python snake_ai.py


The AI will automatically control the snake if enabled

You can also play manually using arrow keys

AI Overview

The AI uses rule-based logic (no machine learning)

At each frame:

Calculates the optimal direction toward the apple

Checks if the next move is safe (within grid, not hitting itself)

Chooses a fallback direction if the preferred path is blocked

Results in a more stable gameplay and higher average score compared to random or human play

Notes

Current AI is basic but effective for demonstration purposes

For advanced AI, consider implementing pathfinding algorithms (BFS/A*) or reinforcement learning (Q-learning)

Designed as a demo project for learning AI logic in games
