# Simple Bouncing Ball Game with OpenCV

This project implements a basic Bouncing Ball game using OpenCV. The game features a moving ball, a controllable racket, and simple collision detection with the walls and the racket. The game ends if the ball falls below the racket.

## Features

- **Mouse Control:** Use the mouse wheel to move the racket left or right.
- **Keyboard Control:** Use the `A` and `D` keys to move the racket left and right, respectively.
- **Collision Detection:** The ball bounces off the walls and the racket.
- **Game Over:** The game ends if the ball falls below the racket.

## Prerequisites

- **OpenCV:** Ensure OpenCV is installed on your system. You can install it using:
  ```bash
  pip install opencv-python
  ```
- **C++ Compiler:** Ensure you have a C++ compiler that supports C++11 or later.

## How to Build

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/yourusername/3D-Computer-Vision---Bouncing-Ball-Game.git
   cd 3D-Computer-Vision---Bouncing-Ball-Game
   ```

2. **Compile the Program:**
   ```bash
   g++ -o 3D-Computer-Vision---Bouncing-Ball-Game main.cpp `pkg-config --cflags --libs opencv4`
   ```

3. **Run the Program:**
   ```bash
   ./3D-Computer-Vision---Bouncing-Ball-Game
   ```

## How to Play

- **Mouse Wheel:** Scroll the mouse wheel to move the racket left or right.
- **Keyboard Controls:**
  - Press `A` or `a` to move the racket to the left.
  - Press `D` or `d` to move the racket to the right.
  - Press `ESC` to exit the game.

- **Objective:** Keep the ball in play by bouncing it off the racket. The game ends if the ball falls below the racket.

## Project Structure

- **main.cpp**: The main source code file containing the game implementation.
- **README.md**: Documentation file (this file).

## Future Enhancements

- Add scoring to track how long the player can keep the ball in play.
- Add levels with increasing difficulty (e.g., faster ball speed).
- Implement sound effects for collisions and game over.
- Add more sophisticated collision detection for angled racket deflections.


