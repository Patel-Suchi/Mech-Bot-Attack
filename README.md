A computer graphics assignment to demonstrate an understanding of OpenGL, by modelling an interactive Robot & Cannon.

## Introduction
The goal of this project was to model a  bot and cannon in OpenGL given a picture. In this project, I created the enemy robot that moves towards the cannon from which user can fire bullet and kill it. The robot each time should follow new path as after every 3s the new angle is calculated for robot and it is translates on that angles direction using Eular Formula. On the other hand the cannon can be rotated and fires the bullet any time when loaded, the bullet rotates as the cannon rotates around its center and when space key is hitted the bullet shoots in direction cannon is facing and using same Eular formula bullet proceed to given direction. If bullet hits the robot then robots are moved back to initial point and bullet is loaded else if bullet misses the shot it translated to -35 in direction of cannons angle and then reloads, in case the robot is save from bullet shot it translates to +z axis until 3 and then moves back to initial point from where it started motion.

## General Information
Extract the shared zip file.

If you have x86 System:

- Find .sln file from the extracted file.
- Open .sln file
- From visual studio at top select x86 instead of x64 and Debug option
- Then press Local Windows Debugger

If you have x64 System:

- Find .sln file from the extracted file.
- Open .sln file
- From visual studio at top select x64 and Debug option
- Then press Local Windows Debugger

Libraries Used:
- GLUT: It is used to generate the window to render all the animations and render objects in graphics pipeline.
- GLEW: It is used with glut to render light effects and some objects in the scene.

As we have loaded OBJ Models for Cannon and Bullet it can take some time to load output.

## Bot Controls

Using Animations:

 - A Key: A key is used to move cannon on left.
 - D Key: D key is used to move the cannon on right 
 - Space Bar: It is used to shoot the ball where arrow is facing.

## Views
 - Robot movement on path 
 - Cannon and bullet rendering 
 - Cannon firing bullet 
 - Bullet and any of 2 robot collision detection 
 - 2 Robots 
 - Help menu in start 


