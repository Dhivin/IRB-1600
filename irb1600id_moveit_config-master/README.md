# irb1600id_moveit_config
ROS industrial package for the IRB1600ID in MoveIt

This package depends on the abb_irb1600id_support package

Everything should be working. For a demo run:
roslaunch irb1600id_moveit_config moveit_planning_execution.launch

to run with a real robot controller:
roslaunch irb1600id_moveit_config moveit_planning_execution.launch sim:=false robot_ip:=IP_ADDRESS_OF_CONTROLLER

Happy programming!

