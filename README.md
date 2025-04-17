# 🎮 AI Pacman Model

![Python](https://img.shields.io/badge/Python-3.5+-blue?logo=python&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-yellow)
![CI](https://img.shields.io/badge/CI-passing-brightgreen)

An advanced Pacman implementation with AI capabilities, adapted from Berkeley's AI Lab project with significant improvements.

## 🚀 Features

- **Modernized Codebase**:
  - Upgraded to Python 3.5+
  - Organized into modular packages
  - Comprehensive logging system
  - Automated tests

- **Enhanced AI Capabilities**:
  - Multiple agent implementations
  - Pathfinding algorithms
  - Decision-making strategies
  - Tournament-ready infrastructure

- **Visual Improvements**:
  - New graphics system
  - GIF generation from gameplay
  - Customizable display options

## 📦 Installation

1. Clone the repository:
  ```bash
   git clone https://github.com/ryanhui30/ai-pacman.git
   cd ai-pacman
  ```

2. Install dependencies:
 ```bash
 pip install -r requirements.txt
 ```

3. Install Tkinter for GUI:
- Linux: sudo apt-get install python3-tk
- Mac: brew install python-tk
- Windows: Comes pre-installed with Python

🕹️ Usage
Run the main game:

 ```bash
 python -m pacai.bin.pacman
 ```

Available modules:
 ```bash
 # Run specific AI agents
 python -m pacai.bin.pacman --agent=YourAgent

 # Generate gameplay GIFs
 python -m pacai.bin.replay --output=gameplay.gif
 ```

🧠 AI Components
- Pathfinding: A* and Dijkstra implementations
- Decision: Making	Minimax with alpha-beta pruning
- Ghost AI: Various chasing/evading strategies
- Utility Systems: Scoring and state evaluation

Need Help?
📩 Contact: ryanhui30@gmail.com
