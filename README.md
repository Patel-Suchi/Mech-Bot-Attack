# Robot-Animation -A computer graphics assignment to demonstrate an understanding of OpenGL, by modelling an interactive Robot.

In this Project the enemy robot moves towards the cannon from which user can fire bullet and kill it. The robot each time should follow new path as after every 3s the new angle is calculated for robot and it is translates on that angles direction using Eular Formula. On the other hand the cannon can be rotated and fires the bullet any time when loaded, the bullet rotates as the cannon rotates around its center and when space key is hitted the bullet shoots in direction cannon is facing and using same Eular formula bullet proceed to given direction. If bullet hits the robot then robots are moved back to initial point and bullet is loaded else if bullet misses the shot it translated to -35 in direction of cannons angle and then reloads, in case the robot is saved from bullet shot and it translates to +z axis until 3 and then moves back to initial point from where it started motion.

Libraries Used:
GLUT: To generate the window to render all the animations and render objects in graphics pipeline.
GLEW: Used with glut to render light effects and some objects in the scene.
