

🐍 Snake Game using SFML
This is a classic Snake Game built using C++ and SFML (Simple and Fast Multimedia Library). The game runs in a graphical window and offers smooth gameplay using arrow key controls. It’s designed to help beginners understand how graphics rendering, event handling, and game logic work together in a 2D environment.

🎮 Game Overview
The Snake Game is a simple yet engaging arcade game where the player controls a snake that moves around the screen, eating food to grow longer. The challenge increases as the snake grows in size and the risk of colliding with itself or the boundaries rises.

Key gameplay mechanics include:

Arrow keys to control the direction

Red square food that appears randomly

Green snake that grows with every food consumed

Game over if the snake hits itself or the wall

This project is a minimal, no-sound, no-score version suitable for fast compilation and easy understanding of SFML basics.

⚙️ Technologies Used
Language: C++

Graphics Library: SFML 2.5.1

Build Tool: g++ (MinGW-w64 for Windows)

🚀 Features
Real-time graphics with SFML

Keyboard input handling (arrow keys)

Snake movement and growth

Food spawning at random locations

Collision detection (self and wall)

Simple modular structure for extensibility

📂 Folder Structure
less
Copy
Edit
SnakeGame/
│
├── main.cpp             // Complete game logic
├── .vscode/             // Optional: VS Code build config
│   └── tasks.json
├── README.md            // This file
└── sfml-dlls/           // Optional: Place SFML DLLs here if needed
🧰 Setup Instructions
✅ Prerequisites:
C++ Compiler (MinGW-w64 recommended)

SFML Library installed on your system

🛠 How to Compile (Windows):
Download and extract SFML

Compile using the following command:

bash
Copy
Edit
g++ main.cpp -o snake -IC:/SFML/include -LC:/SFML/lib -lsfml-graphics -lsfml-window -lsfml-system
Replace C:/SFML/ with your actual SFML path.

Copy required .dll files from SFML/bin to your project folder:

sfml-graphics-2.dll

sfml-window-2.dll

sfml-system-2.dll

Run the game:

bash
Copy
Edit
./snake
📌 Future Improvements (Optional Ideas)
Add sound effects (using sfml-audio)

Display score and high score

Add menu screen and restart functionality

Use textures instead of plain shapes

Increase difficulty as time passes

💡 Credits
Built using SFML

Inspired by the classic Snake game concept

📜 License
This project is open-source and free to use under the MIT License.

