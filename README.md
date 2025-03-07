Localization commands:
1:
	source ~/ros_noetic_base/catkin_ws/devel/setup.bash
	roscore
2:
	source ~/ros_noetic_base/catkin_ws/devel/setup.bash
	roslaunch block_localization run_newer.launch		OR		roslaunch block_localization run_glil.launch
3:
	source ~/ros_noetic_base/catkin_ws/devel/setup.bash
	cd ~/Desktop
	rosbag play 2021-07-01-10-37-38-quad-easy_fixed.bag
