# Ros2_tutorial
ROS Basic Guide
Create by Vu Van Son
base on: ROS 2 Humble Hawksbill
Tutorial to create a package

The command syntax for creating a new package in ROS 2 is:
	ros2 pkg create --build-type ament_cmake --license Apache-2.0 <package_name>
	
but in this example, we will use the optional argument --node-name which creates a simple Hello World type executable in the package:
	ros2 pkg create --build-type ament_cmake --license Apache-2.0 more_interfaces
	mkdir more_interfaces/msg

to run application: source install/local_setup.bash
		    ros2 run more_interfaces publish_address_book
		    
To confirm the message is being published on the address_book topic, open another terminal, source the workspace, and call topic echo:
	source install/setup.bash
	ros2 topic echo /address_book
