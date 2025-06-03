# Tic-Tac-Toe Game with SFML

![Tic-Tac-Toe Screenshot](screenshot.png) <!-- Add your screenshot here -->

A classic Tic-Tac-Toe game built with C++ and SFML featuring smooth animations and AI opponent.

## Features

- 🎮 Player vs. Computer gameplay
- ✨ Smooth animations (fade effects, symbol pop-in)
- 🔄 Choose to play as X or O
- 🏆 Win detection and game over screen
- 🔄 Quick restart functionality (press R or F5)
- 🖱️ Mouse and keyboard controls

## Installation

### Requirements
- C++17 compiler
- SFML 2.5.x library

### Build Instructions

**Linux/macOS:**
```bash
g++ -std=c++17 main.cpp -o tictactoe -lsfml-graphics -lsfml-window -lsfml-system
Windows (Visual Studio):

Install SFML via vcpkg or download binaries

Add SFML include and lib paths to your project

Link required SFML libraries

How to Play
Run the executable

Press ENTER at the welcome screen

Choose X or O (X goes first)

Click on any empty square to place your mark

The computer will automatically make its move

Game ends when someone wins or board is full

Press R to restart or F5 to return to main menu

Controls
Mouse: Click on squares to place your mark

Keyboard:

ENTER: Start game/confirm selection

X/O: Choose your symbol

R: Restart after game over

F5: Reset to main menu

Code Structure
Key components:

Game state management (Welcome, Playing, GameOver)

Animation system for smooth transitions

Win condition checking algorithm

Simple AI opponent (random moves)

Future Improvements
Implement Minimax algorithm for smarter AI

Add difficulty levels

Sound effects

Online multiplayer

License
MIT License - Feel free to use and modify this code


### Additional recommendations:

1. Create a `screenshot.png` showing your game in action and place it in the same directory
2. Consider adding a short demo GIF to showcase animations
3. For Windows users, you might want to add more detailed setup instructions
4. If you upload to GitHub, the markdown will render nicely with proper formatting

Would you like me to modify any specific section or add more details about particular parts of the implementation?