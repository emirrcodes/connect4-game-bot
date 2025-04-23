# Connect4 Game Bot

This project is a C implementation of the classic **Connect4** game, extended with a **game bot** and a **simple command-line interface**. The project was developed for a university-level assignment and is structured using a modular approach with clear separation between logic, interface, and AI components.

## 🧠 Features

- Fully playable Connect4 game logic
- Bot integration for single-player gameplay
- Command-line interface for interaction
- Tree-based game state analysis (for bot moves)
- Memory and error handling integrated with Valgrind testing
- Organized source structure with `Makefile` support

## 🗂️ Project Structure
├── Makefile                  # Build instructions
├── submission_script.sh      # Auto-grading or submission helper
├── src/
│   ├── main.c                # Program entry
│   ├── connect4.c            # Core game logic
│   ├── tree.c                # Game tree for bot decision-making
│   ├── game_bot.c            # AI logic
│   └── interface.c           # CLI interaction
├── include/                  # Header files
├── tests/                    # Test cases (if applicable)
├── bin/                      # Compiled binaries (excluded from git)
├── lib/                      # External libraries (if used)
└── valgrind-out.txt          # Output of memory analysis

## ⚙️ How to Build

```bash
make
```

## ▶️ How to Run
```bash
./bin/connect4
```

## 🧪 Memory Check (Valgrind)
```bash
valgrind ./bin/connect4
````

## 📦 Notes
	•	This project is designed with modularity in mind for better readability and maintenance.
	•	You can extend it further with a GUI or smarter bot strategies.
