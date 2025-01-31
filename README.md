3D Raycasting Game with Pygame

Overview
This project is a simple 3D raycasting game developed using Pygame. It implements a first-person perspective using a raycasting technique to simulate 3D environments. The game includes walls, textures, and sprite objects.

Features
Raycasting Engine for 3D visualization.
Player Movement with collision detection.
Wall Textures and environment rendering.
Sprite System for static and animated objects.
Object Handling for managing in-game elements.

Installation
Ensure you have Python installed on your system. Then, install the required dependencies using:
"pip install pygame"

How to Run
Simply execute the main.py file:
"python main.py"

Code Structure

1. main.py
This is the main entry point of the game. It initializes the game loop, handles events, updates the game state, and renders objects.

2. map.py
Defines the game map using a 2D list where different numbers represent different textures or objects.

3. object_handler.py
Manages in-game objects like static and animated sprites.

4. object_renderer.py
Renders walls, sky, floor, and game objects on the screen.

5. player.py
Controls the player's movement and interaction with the environment. Implements movement using the WASD keys and mouse for rotation.

6. raycasting.py
Handles the raycasting algorithm for rendering the 3D environment based on the player's viewpoint.

7. settings.py
Stores all game-related configuration settings, such as screen resolution, player speed, and raycasting parameters.

8. sprite_object.py
Handles sprite-based objects such as decorations and animated items within the game.

Controls
W/A/S/D: Move forward, left, backward, and right.
Mouse Movement: Look around.
ESC: Exit the game.

Requirements
Python 3.x
Pygame library

Future Improvements
Adding enemies and AI interaction.
Implementing weapon mechanics.
Expanding the map and adding new textures.(I`m not sure.)

Enjoy coding and exploring the world of Pygame! 🚀
