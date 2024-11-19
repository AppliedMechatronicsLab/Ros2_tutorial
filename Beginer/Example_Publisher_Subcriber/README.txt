# Ros2_tutorial
ROS Basic Guide
Create by Vu Van Son
base on: ROS 2 Humble Hawksbill
Tutorial to create applications for publisher and subcriber

in this example, we will create a package, that have 2 node.
	ros2 pkg create --build-type ament_cmake --license Apache-2.0 cpp_pubsub # to create a package with name cpp_pubsub
	
build: colcon build
set environment: source install/setup.bash
run example: ros2 run cpp_pubsub talker
	     ros2 run cpp_pubsub listener
	
