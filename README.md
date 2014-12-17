PlugNPlayNXT
============

Automatic Histogram Filter For NXT LeJOS Mindstorms Robots

This project attempts to faciliate the learning process of implementing filtering algorithms for the autonomous driving
of NXT Mindstorms Robots in a closed environment. HelloRobot uses a Histogram Filter to localize the robot in its
environment and later perform path planning via Dynamic Programming in order to navigate to the appropriate goal.

The environment for the robot must be specified in the HelloRobot.java file, and can be made easier using a threshold
based Occupancy-Grid mapping algorithm to automatically deduce maps of an environment based on measurements. Other 
variables such as tire width and vehice length must be specified within the code, and is well explained/documented
in the comments. 

Of course this filter isn't perfect, but it provides a way for actually visualizing a filter in a real demo while
still being able to learn from the source code.

For an excellent course on AI and programming robots, visit Udacity.com and take Professor Thrun's "Artificial Intelligence for Robotics"
class, CS373.

