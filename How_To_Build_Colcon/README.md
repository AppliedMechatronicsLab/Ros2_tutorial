# Ros2_tutorial
ROS Basic Guide
Create by Vu Van Son
base on: ROS 2 Humble Hawksbill
Tutorial to build project using colcon build

step 1: refer directory_tree.jpg
step 2: how to build, run cmd:
	colcon build --symlink-install
step 3: run test:
	colcon test
step 4: run project:
	source install/setup.bash # to set env
	ros2 run examples_rclcpp_minimal_subscriber subscriber_member_function # run subcriber application
	ros2 run examples_rclcpp_minimal_publisher publisher_member_function   # run publisher application
