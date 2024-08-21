# toy-robot-simulator

## Description

This application simulates a toy robot moving on a 5x5 tabletop. The robot can be placed on the table, moved, rotated, and can report its position and facing direction.

## Commands

PLACE X,Y,F: Place the robot on the table at position (X, Y) facing direction F (NORTH, SOUTH, EAST, or WEST).
MOVE: Move the robot one unit forward in the direction it is currently facing.
LEFT: Rotate the robot 90 degrees to the left.
RIGHT: Rotate the robot 90 degrees to the right.
REPORT: Output the current position and facing direction of the robot.

## Constraints

The robot must not fall off the table.
Any move that would cause the robot to fall must be ignored.

## For the code test
python
commands = [
    "PLACE 0,0,NORTH",
    "MOVE",
    "REPORT"
]
process_commands(commands)