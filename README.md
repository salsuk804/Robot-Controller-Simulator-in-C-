# Robot-Controller-Simulator-in-Cpp
A terminal-based robot movement controller on a fixed 10-cell array, featuring move history, reboot, and cancel support


# Project Description
This C++ program simulates a robot moving within a fixed-size array of 10 cells (from index 0 to 9). The robot begins at position 0 and can move left or right based on user input through a menu. The program supports command history, which allows reversing previous actions using the cancel(n) command.

#Problem Statement
Design a C++ program that controls the movement of a robot along a 1D array of size 10 using a set of commands accessed via a terminal-based menu. The robot must always remain within the array bounds and maintain a history of movements for potential rollback.

# Controller Menu

1. Right
2. Left
3. Display
4. Reboot
5. Show Array
6. Cancel
7. Exit

# Command Descriptions
Right(n) – Move the robot n cells to the right. If out of bounds, reject the move.

Left(n) – Move the robot n cells to the left. If out of bounds, reject the move.

Display – Display the current position of the robot.

Reboot – Reset the robot’s position to cell 0.

Show Array – Print the array showing the robot’s current location with a ^ symbol.

Cancel(n) – Cancel the last n movement/reboot operations and return the robot to the starting position.

Exit – Terminate the program.

# Implementation Requirements
Each command must be implemented in a separate function.

Ensure the robot never moves outside the bounds [0, 9].

Maintain a command history to support the cancel(n) feature.

Emphasize modular design and input validation.


