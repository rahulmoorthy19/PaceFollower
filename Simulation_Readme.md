These are the steps to setup the Simulation for the rover:
* Install [ROS-Humble](https://docs.ros.org/en/humble/Installation.html)
* Follow steps mentioned in [Installation Option-2](https://github.com/RoverRobotics/roverrobotics_ros2?tab=readme-ov-file#recommendedoption-1-using-the-provided-install-script-in-the-rover_install_scripts_ros2-repo) of RoverRobotics for setting up just with the simulation
  * Start the Simulation using the steps described in RoverRobotics [Simulation With Gazebo Steps](https://github.com/RoverRobotics/roverrobotics_ros2?tab=readme-ov-file#simulation-with-gazebo) with the robot as "4wd"
* This would create a maze environment with the robot spawn in the center. Press the play button to start the simulation
  * Use the velocity_publisher.py toy script to publish velocity commands to the rover
  * To perform teleop, please perform the following steps:
    * sudo apt install ros-${ROS_DISTRO}-teleop-twist-keyboard
    * ros2 run teleop_twist_keyboard teleop_twist_keyboard
