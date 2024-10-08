# Pac-Man Game in Python with PyGame

## Overview
This is a Pac-Man game implemented in Python using the PyGame library. The game features the classic Pac-Man gameplay, including the iconic characters, maze, and scoring system.

## Features
- Classic Pac-Man gameplay with Pac-Man, Blinky, Pinky, Inky, and Clyde
- Maze with walls, pellets, and power pellets
- Scoring system with points for eating pellets and ghosts
- Lives system with game over and restart functionality
- Winning condition when all pellets are eaten

## Requirements
- Python 3.x
- PyGame library (install with `pip install pygame`)
- `boards.py` file containing the maze layout (not included in this repository)

## Gameplay
- Use the arrow keys to move Pac-Man
- Eat pellets to score points
- Eat power pellets to turn the ghosts blue and earn bonus points
- Avoid the ghosts to survive
- Restart the game with the space bar when game over or won

## Code Structure
The code is organized into the following sections:
1. **Initialization**: Game setup, including importing libraries, setting up the display, and initializing game variables
2. **Game Loop**: Main game loop that handles events, updates game state, and renders the game
3. **Game Logic**: Functions that implement game logic, such as moving Pac-Man, updating ghost positions, and checking collisions
4. **Drawing**: Functions that render the game, including the maze, characters, and score

## Classes
- **Ghost**: Represents a ghost character, including its position, direction, and behavior

## Functions
- **draw_board**: Draws the maze
- **draw_player**: Draws Pac-Man
- **check_position**: Checks if Pac-Man can move in a certain direction
- **move_player**: Moves Pac-Man
- **get_targets**: Calculates the targets for the ghosts
- **check_collisions**: Checks for collisions between Pac-Man and the ghosts or pellets

## License
This code is released under the MIT License. See the LICENSE file for details.

## Contributing
Contributions are welcome! If you'd like to contribute to this project, please fork the repository and submit a pull request.

## Acknowledgments
This project was inspired by the classic Pac-Man game. The maze layout is not included in this repository, but you can create your own using the `boards.py` file.
