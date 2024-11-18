# Ros2_tutorial
ROS Basic Guide
Create by Vu Van Son
base on: ROS 2 Humble Hawksbill
Tutorial to create a package

The command syntax for creating a new package in ROS 2 is:
	ros2 pkg create --build-type ament_cmake --license Apache-2.0 <package_name>
	
ros2 pkg create --build-type ament_cmake --license Apache-2.0 cpp_launch_example

ros2 launch cpp_launch_example my_script_launch.py