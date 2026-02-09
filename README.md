Pac-Man Clone (Python, Pygame)

A fully playable Pac-Man clone built from scratch in Python using Pygame.
The game recreates core Pac-Man mechanics including tile-based movement, enemy AI behavior, power-ups, scoring, and win/lose conditions.

Features
- Real-time 2D gameplay at 60 FPS using Pygame
- Tile-based board system with collision detection
- Four AI-controlled ghosts with distinct movement and targeting behavior
- Power-up system with frightened, chase, and respawn ghost states
- Score tracking, lives system, and game over / victory conditions
- Screen wrap tunnels and ghost box logic

Controls
- Arrow Keys or ASWD: Move Pac-Man
- Space: Restart after game over or victory
- Close Window: Exit the game

How to Run
Requirements
- Python 3.9+
- Pygame

Installation
pip install pygame

Run the Game
python main.py

Project Structure
.
├── assets/
│   ├── ghost_images/
│   │   ├── blue.png
│   │   ├── dead.png
│   │   ├── orange.png
│   │   ├── pink.png
│   │   ├── powerup.png
│   │   └── red.png
│   └── player_images/
│       ├── 1.png
│       ├── 2.png
│       ├── 3.png
│       └── 4.png
├── board.py        # Tile-based level layout
├── main.py         # Game loop, rendering, input handling, AI logic
├── venv/           # Python virtual environment (not required to run)
└── README.md

Technical Highlights
- Implemented a custom game loop with frame-based animation and event handling
- Designed modular enemy AI with state-driven behavior (chase, frightened, dead)
- Built collision-aware movement using grid-based navigation
- Managed complex game state transitions including power-ups, respawns, and scoring

Future Improvements
- Add sound effects and background music
- Improve ghost pathfinding using BFS or A*
- Add multiple levels and increasing difficulty
- Implement high-score saving