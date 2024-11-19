# Ros2_tutorial
ROS Basic Guide
Create by Vu Van Son
base on: ROS 2 Humble Hawksbill
Tutorial to create a package

The command syntax for creating a new package in ROS 2 is:
	ros2 pkg create --build-type ament_cmake --license Apache-2.0 <package_name>
	
but in this example, we will use the optional argument --node-name which creates a simple Hello World type executable in the package:
	ros2 pkg create --build-type ament_cmake --license Apache-2.0 cpp_parameters --dependencies rclcpp

run: 
	ros2 run cpp_parameters minimal_param_node
	ros2 param list #check list param
	ros2 param set /minimal_param_node my_parameter earth #set param

