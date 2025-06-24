# New PvZ 🌻🧟

A C++ Plants vs. Zombies–inspired 2D fighting game project built with [EasyX](http://www.easyx.cn/).  
This is a personal game development project focusing on basic scene management, animation, player controls, bullet physics, and collision detection.

---

## 🎮 Features

- Two-player fighting mode inspired by PvZ plants and zombies
- Encapsulated **Animation** and **Camera** classes
- Parabolic bullet trajectories and bullet collision detection
- Camera shake effects and hit feedback
- Invincibility frames using a `Timer` class
- Debugging tools (e.g., FPS display, hitbox visibility toggle)
- Modular scene structure:
  - Main Menu Scene
  - Selector Scene
  - Game Scene

---

## 🧱 Technologies Used

- **C++**
- **EasyX graphics library**
- Object-oriented design (OOP)
- Custom math utility functions

---

## 🖼️ Screenshots

_Add screenshots here once the game window is ready_

---

## 🚀 Getting Started

### Prerequisites

- Windows system
- Visual Studio
- [EasyX library](http://www.easyx.cn/) installed

### Build & Run

1. Clone the repository:
   ```bash
   git clone https://github.com/KarthusChen/New-PvZ.git
Open the .sln file in Visual Studio

Build and run the project (Debug or Release mode)

📂 Project Structure
plaintext
Copy
Edit
New PvZ/
├── bullet/                  # Bullet-related classes
├── player/                  # Player and character logic
├── scene/                   # Scene classes (menu, game, selector)
├── animation.h              # Animation system
├── camera.h                 # Camera shake and view logic
├── timer.h                  # Timer utilities (e.g. i-frame)
├── main.cpp                 # Entry point
└── .gitignore
✨ Future Improvements
Add background music and sound effects

Support for more characters and skills

Game UI (health bars, timer)

Online multiplayer (maybe via SFML or socket)

📜 License
This project is for learning and personal use.
Feel free to fork and improve it!

💬 Contact
Developed by KarthusChen
Feel free to open issues or suggest features!
