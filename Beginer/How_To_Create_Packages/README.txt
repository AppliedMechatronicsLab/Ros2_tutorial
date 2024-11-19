# Ros2_tutorial
ROS Basic Guide
Create by Vu Van Son
base on: ROS 2 Humble Hawksbill
Tutorial to create a package

The command syntax for creating a new package in ROS 2 is:
	ros2 pkg create --build-type ament_cmake --license Apache-2.0 <package_name>
	
but in this example, we will use the optional argument --node-name which creates a simple Hello World type executable in the package:
	ros2 pkg create --build-type ament_cmake --license Apache-2.0 --node-name my_node my_package

to build, run cmd:
	colcon build
note: To build only the my_package package next time, you can run:
	colcon build --packages-select my_package
	
to run: open another terminal and setup environment:
	source install/local_setup.bash
	run: ros2 run my_package my_node
