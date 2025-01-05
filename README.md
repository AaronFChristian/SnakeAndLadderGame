# Snake and Ladder Game

## Overview
This is a Python implementation of the classic **Snake and Ladder** game. The game supports two players, where each player takes turns rolling a dice to move along the game board. Encountering ladders moves the player up, while encountering snakes slides them down. The first player to reach the final position wins the game.

## Features
- Simulates a two-player Snake and Ladder game.
- Random dice rolls using Python's `random` module.
- Dynamic messages for gameplay actions like encountering snakes or climbing ladders.
- Easy-to-follow gameplay with clear instructions.

## Rules
1. Both players start at position `0`.
2. Players take turns to roll a dice and move forward by the number rolled.
3. If a player lands at the bottom of a ladder, they climb up to the top.
4. If a player lands on the head of a snake, they slide down to its tail.
5. The first player to reach position `100` wins the game.

## How to Run
1. Ensure you have Python 3 installed on your system.
2. Save the script in a file, e.g., `snake_and_ladder.py`.
3. Open a terminal or command prompt and navigate to the file's directory.
4. Run the script using the command:

   ```bash
   python snake_and_ladder.py
   ```
