# Ros2_tutorial
ROS Basic Guide
Create by Vu Van Son
base on: ROS 2 Humble Hawksbill
Tutorial to create a package

The command syntax for creating a new package in ROS 2 is:
	ros2 pkg create --build-type ament_cmake --license Apache-2.0 <package_name>
	
but in this example, we will create the new package:
	ros2 pkg create --build-type ament_cmake --license Apache-2.0 tutorial_interfaces
	
How to confirm msg and srv creation:
	open new terminal: set environment and run cmd "source install/setup.bash"
	run cmd to check: ros2 interface show tutorial_interfaces/msg/Num
	
Note*: In this tutorial, the tutorial interface must be built before all. if error, pls only build tutorial_interface after that set environment and build all again
	

	
