# ELEC5620M Mini-Project Repository

This is the blank repository in which you must incrementally commit your code.

Update: This repository contains the code files of the MINI-PROJECT submission for -
ELEC5620M: Embedded Microprocessor System Design Group-23 of 2022/23

# Maze Solver Game for ELEC5620M
This project is a Maze Solver Game for ELEC5620M, created by S.V.V. Penagenti, S.H. Tauro, and R. Mohammad.

## About
The Maze Solver Game is an interactive game that generates a random maze and allows the player to navigate through it. The game is developed in C language and implemented on the DE1-SoC board using its LCD display.

The game has different difficulty levels which change the size of the maze. The game also features a start and an endpoint, where the player has to navigate from the start point to the endpoint to complete the game.

## Instructions
1. Clone the repository to your local machine.
2. Navigate to the directory containing the project files.
3. Use an appropriate C compiler to compile the project.

## Key Files
1. main.c: This is the main file of the game. It includes the initialization of the game, the game loop, and the main logic of the game.
2. maze.h: This is the header file for the maze. It contains the necessary function declarations and constants for the game.
3. maze.c: This is the source file for the maze. It contains the implementation of the maze generation and drawing functions.

## Main Functionality
1. Initialization: Initializes the LCD display and watchdog.
2. Menu display: Displays the home screen with game instructions and options.
3. Difficulty selection: Allows the player to select the difficulty level which changes the size of the maze.
4. Maze generation: Generates a random maze based on the selected difficulty level.
5. Gameplay: Lets the player navigate through the maze. The game ends when the player reaches the endpoint.

## Solved Issues
1. Score updates avaialble. 
2. Timer for difficulty level 4 live.

Please report if you find any other issues.

## Future Work (planned)
1. Improve the maze generation algorithm for more complex mazes.
2. Add more difficulty levels.
3. Add power-ups or obstacles within the maze for a more engaging gameplay experience.

## Contributors
1. S.V.V. Penagenti
2. S.H. Tauro
3. R. Mohammad
MSc. Mechatronics & Robotics, University of Leeds.

We hope you enjoy playing the Maze Solver Game. Happy gaming!
