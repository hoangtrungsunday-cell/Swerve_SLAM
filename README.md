Dowload file zip.
run the command
cd robot_ws
source install/setup.bash
ros2 launch my_robot_description test_slam.launch.py
ros2 launch my_robot_description cartographer.launch.py
Control by ps4

cd src/my_robot_description/src
python3 swerve_teleop_node.py

