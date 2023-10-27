#Simple Publisher and Subscriber Node
This folder is used to store the key codes, setup files and package.xml
other common files are not stored. 

Here the following were created,
1. Subscriber pose_subscriber_ /turtle1/pose
2. Publisher cmd_vel_ /turtle1/cmd_vel

 The above two created in the node of robot_control

 ROS2 commands used,
 1. ros2 topic list
 2. ros2 topic info <topic_name>
 3. ros2 interface show <msg_type>
 4. colcon build --symlink-install
 5. touch <proram_name>
 6. chmod +x <program_name>
 7. source install/setup.bash
 8. ros2 run turtlesim turtlesim_node
 9. ros2 run turtlesim turtle_teleop_key
 10. ros2 run <package_name> <program_name>
 11. rqt_graph

