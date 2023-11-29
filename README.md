The_Maze

This is a simple 3D game project implemented in C using SDL2. The goal is to create a basic 3D environment with features like raycasting, enemy rendering, rain, and additional visual effects.

## Project Structure

project_folder/
|-- src/
| |-- main.c
| |-- rendering.c
| |-- input_handling.c
| |-- map.c
| |-- enemy.c
| |-- rain.c
| |-- effects.c
|-- inc/
| |-- rendering.h
| |-- input_handling.h
| |-- map.h
| |-- enemy.h
| |-- rain.h
| |-- effects.h

## Steps

### Step 1: Setting Up the Project

Create the necessary folders and files for the project.

### Step 2: Basic SDL and Raycasting

Implement the basic SDL window creation, raycasting, and movement controls.

### Step 3: Enemies

Implement enemy-related code. Load enemy textures and render them.

### Step 4: Rain

Implement rain-related code. Load raindrop textures and render them. Add key event to start/stop rain.

### Step 5: Textures

Load and render weapon, ground, ceiling, and wall textures.

### Step 6: Multiple Directions and Rotation

Modify movement controls to handle multiple keys simultaneously for smoother control.

### Step 7: Collision and Sliding

Handle collisions with walls to make the player slide instead of stopping.

### Step 8: Parser

Implement a map parser to load the map from a file.

### Step 9: Draw the Map

Draw the map on the window. Modify rendering code to include player's line of sight.

### Step 10: Coding Style + Documentation

Check and adhere to the Holberton School coding style. Ensure code is well-documented.

### Step 11: Ground Textures

Load and render ground and ceiling textures.

### Step 12: Weapons

Load and render weapon textures.

### Step 13: Make it Rain

Implement rain and the ability to start/stop rain with a key.

### Step 14: Extra Options

Add shadows, special lighting, or any other creative visual effects.

## How to Build

Ensure that you have SDL2 installed on your system. If not, you can download it [here](https://libsdl.org/download-2.0.php) or install it using your package manager.

Build the project using a C compiler. For example, using gcc:

```bash
gcc src/*.c -o game -Iinc -lSDL2 -lm
