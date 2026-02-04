# Logic Arena ⚔️💻

**Logic Arena** is an exciting desktop-based programming adventure game (inspired by CodeCombat) where players write **real code** (Python, JavaScript, C++, etc.) to command heroes, solve logic puzzles, battle enemies.

## 🎯 Vision
Turn learning programming into an addictive, competitive game experience.  
Players code strategies → control heroes in real-time battles → master loops, functions, recursion, OOP, and algorithms while having fun.

Target: Ages 10+, schools, coding clubs, esports enthusiasts, self-learners in Bangladesh & worldwide.

The project will run on **Windows, macOS, and Linux** with a single codebase, leveraging modern Python libraries for smooth, professional-quality gameplay.

## ✨ Key Features (Planned)
- Code-driven gameplay: Players control heroes using Python code instead of keyboard/mouse.
- Tick-based game engine: Deterministic execution ensures fair, repeatable gameplay.
- Tile-based 2D maps: Procedurally generated or static, supporting multiple levels.
- Split-screen UI: Embedded code editor + game world + console feedback.
- Cross-platform: Runs on Windows, macOS, Linux.

## Project Structure (Proposed)

```text
LogicArena/
├── engine/                 # Core game engine
│   ├── game_loop.py        # Main loop controlling ticks and updates
│   ├── world.py            # Game world representation (map, tiles)
│   ├── entities.py         # Hero, enemies, NPCs, and object classes
│   ├── physics.py          # Collision detection, movement, and interactions
│   └── renderer.py         # Rendering engine, drawing sprites and tiles
│
├── scripting/              # Handles execution of player code
│   ├── sandbox.py          # Safe code execution environment
│   ├── api.py              # Hero/Enemy API exposed to players
│   └── ast_checker.py      # AST validation to prevent unsafe code
│
├── levels/                 # Level data and configurations
│   ├── level1.yaml         # Map layout and enemy positions
│   └── level2.yaml
│
├── ui/                     # User interface components
│   ├── code_editor.py      # Embedded PyQt6 editor integration
│   └── hud.py              # Console, logs, and additional UI elements
│
├── assets/                 # Game assets (sprites, tiles, sounds)
│   ├── sprites/
│   ├── tiles/
│   └── sounds/
│
├── main.py                 # Entry point for the game
└── README.md               # Project documentation
```

## Tech Stack (Proposed)
- Python 3.12 – Core programming language
- PyQt6 – Desktop UI and embedded code editor integration
- Arcade – 2D game engine and rendering
- Monaco / CodeMirror – Embedded code editor (syntax highlighting and line numbers)
- PyInstaller – Cross-platform packaging
- AST + Sandbox – Safe Python code execution
- Assets: Kenney.nl, OpenGameArt.org, or custom procedural sprites

Star ⭐ the repo if you'd like to follow the journey!

## 📄 License
MIT License – feel free to fork, remix, learn from, and contribute.
