# Gazebo-Environment
How to Load up a new Gazebo Environment:
----------------------------------------
1) Put Quadrotor Launch File in Package Launch location
1a) For Simple world (test_simple_world.launch) put it into hector_quadrotor/hector_quadrotor_demo/launch
2) Put the Gazebo Launch File in the Gazebo package Launch location
2a) For Simple world (simple_test_world.launch) put it into hector_gazebo/hector_gazebo_worlds/launch
3) Put the Gazebo World File in the Gazebo Package World Location
3a) For the Simple world (test_simple_world.world) put it into hector_gazebo/hector_gazebo_worlds/worlds


Things to note:
The Quadrotor Launch File loads the :
A) Gazebo Launch file
B) Quadrotor into the gazebo world
C) RVIZ
D) Xbox Controller

The Gazebo Launch File loads the :

A) Gazebo World file

The Gazebo World File loads the :

A) Gazebo World, objects, etc.


How to Run the environment:
---------------------------
1) Launch Roslaunch with package and launch file
1a) roslaunch hector_quadrotor_demo test_simple_world.launch
