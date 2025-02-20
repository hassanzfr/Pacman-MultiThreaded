# 🎮 Pacman Game - Multithreaded Edition

A multithreaded Pacman game implemented in C++, featuring POSIX threads, semaphores, and SFML for graphics rendering. This game brings the classic Pacman experience with enhanced concurrency control for managing game logic, ghosts, and rendering efficiently.

# 🌐 Features

🔌 Multithreading: Separate threads handle game logic, UI updates, and ghost behavior.

🛠 Synchronization Mechanisms: Utilizes pthread_mutex and semaphores to manage concurrency.

👻 AI-Driven Ghosts: Each ghost follows a randomized movement strategy with dynamic speed boosts.

🎨 SFML Graphics: Smooth rendering of Pacman, ghosts, and the game board.

⚡ Power Pellets & Boosts: Pacman can consume power pellets to temporarily weaken ghosts and gain speed boosts.

📈 Score Tracking: Real-time score updates and display.

# 🛠 Technologies Used

C++ ✨ - Core game logic and threading.

POSIX Threads (pthreads) 🔄 - Multithreading implementation.

Semaphores ⚡ - Synchronization for game elements.

SFML (Simple and Fast Multimedia Library) 🎨 - Graphics rendering.

Mutex Locks ⚖ - Data consistency in concurrent environments.

# ⚡ Getting Started

Prerequisites

Make sure you have the following installed:

SFML

G++ Compiler

POSIX Threads (pthreads)

# Installation & Compilation

Clone the repository

git clone https://github.com/hassanzfr/Pacman-MultiThreaded.git
cd pacman-game

Compile the game

g++ main.cpp functions.cpp -o pacman -lsfml-graphics -lsfml-window -lsfml-system -pthread

Run the game

./pacman

# 💪 Controls

Arrow Keys: Move Pacman

ESC: Exit the game

# 🏆 Winning & Losing

Win: Eat all pellets to win the game.

Lose: Run out of lives after being caught by ghosts.


