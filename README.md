# -Robot-robot-servo-motion-Tinkercad-simulator-and-practical-implementation


# Project Description

This project demonstrates the basic control of a humanoid robot's movement using four servo motors programmed through Arduino Uno. The simulation was designed and tested using Tinkercad, and the same setup was implemented in a real-world (physical) circuit.

The program begins by running a synchronized sweep motion on all four servo motors for 2 seconds, mimicking initial movement in a humanoid robot. After the sweep, all motors hold at 90 degrees, representing a neutral standing position. This forms the foundation for developing a simple walking behavior in robotics.

# Objectives


Control 4 servo motors using Arduino.

Run a synchronized sweeping motion for 2 seconds.

After 2 seconds, stop the motion and hold all motors at 90°.

Understand servo timing and position control for humanoid movement.

# Components Used


Arduino Uno

4x Servo Motors

Breadboard

Jumper Wires




# Algorithm



1- Start the Program

2- Initialize the 4 servo motors

Attach Servo1 to pin 9

Attach Servo2 to pin 10

Attach Servo3 to pin 11

Attach Servo4 to pin 12

3- Store the current time as the starting point

4- Repeat the following steps as long as 2 seconds haven’t passed:

For positions from 0° to 90°:

Move all 4 servos to the current position

Wait a small delay (e.g. 10ms)

For positions from 90° to 0°:

Move all 4 servos to the current position

Wait a small delay

5- After 2 seconds, move all 4 servos to 90° and hold them there

6- Repeat Step 5 forever (keep holding at 90°)














