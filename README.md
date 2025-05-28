# Snake-Game

This is a simple **Snake Game** built with **Tkinter** in Python. The game features basic gameplay mechanics, such as controlling the snake with the arrow keys, growing the snake when it eats food, and ending the game when the snake collides with itself or the boundaries of the window.

## Features

- **Snake Movement**: Use arrow keys to change the direction of the snake.
- **Growing Snake**: Each time the snake eats food, it grows in size.
- **Game Over**: The game ends when the snake collides with itself or the boundaries of the game area.
- **Score**: A score is displayed which increases every time the snake eats food.
- **Game Window**: The window is centered on the screen.

## Example Gameplay

![Snake Game](![alt text](image.png))

## Requirements

- Python 3.x
- Tkinter (usually comes pre-installed with Python)

## How to Run

1. Make sure you have Python 3.x installed on your computer. You can check your Python version by running:
   ```
   python --version
   ```
   
2. Make sure you have Tkinter installed. Tkinter is included by default in most Python installations, but if it's not installed, you can install it using:
   ```
   pip install tk
   ```

3. Copy the code into a Python file (e.g., `snake_game.py`).

4. Run the script:
   ```
   python snake_game.py
   ```

5. The game window will appear, and you can start playing by using the arrow keys to control the snake.

## Game Controls

- **Up Arrow**: Move the snake up.
- **Down Arrow**: Move the snake down.
- **Left Arrow**: Move the snake left.
- **Right Arrow**: Move the snake right.

## Game Description

- **Snake**: The snake is represented by green squares. Initially, the snake has 3 body parts.
- **Food**: Food is represented by a red circle. Each time the snake eats food, its size increases by one body part, and the score increases by 1.
- **Game Over**: The game ends when the snake collides with itself or the window boundaries.

## Code Breakdown

1. **Snake Class**:
   - Initializes the snake's body and creates graphical representations (rectangles) for each part of the body.
   - Moves the snake and checks for collisions.
   
2. **Food Class**:
   - Randomly places food on the game canvas.
   - Redraws the food every time it is eaten by the snake.

3. **Game Logic**:
   - The snake moves continuously, and after each move, it checks for collisions with food or its own body.
   - The game ends if the snake collides with itself or the window boundaries.

4. **Tkinter Window**:
   - A Tkinter `Canvas` is used to draw the game elements (snake, food, etc.).
   - The game window is non-resizable and is centered on the screen.

5. **Control System**:
   - The snake’s direction is changed using the arrow keys.
   - The game continuously updates using `window.after()` for smoother gameplay.



## License

This project is licensed under the MIT License - (https://github.com/ShivakotiShambhavi/Snake-game-/blob/main/LICENSE)
