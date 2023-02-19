# ros_mobile_robot
Simulate and drive a mobile robot in Gazebo and rviz. This package is used in [chapter 10 and 11](https://robodev.blog/simulate-a-mobile-robot-in-ros-part-1) of the series ROS 101 in my blog [robodev.blog](https://robodev.blog/).

Clone this repo to a catkin workspace and do `catkin build` or `catkin_make`. To run it, open 2 terminals. In the first one, launch the file drive_robot.launch:

`roslaunch ros_mobile_robot drive_robot.launch`

Wait a few seconds for Gazebo to be fully loaded. In the second terminal, run the rqt_robot_steering package which provides a GUI to steer robots.

`rosrun rqt_robot_steering rqt_robot_steering`

Change the linear and angular velocities in the GUI to steer the robot:

![mobile-robot-gazebo](https://user-images.githubusercontent.com/19979949/219981336-483be8ba-f465-431e-b6b4-164ac40c5814.gif)
