# ecse473_f23_sxw1127_navvis_rosbag
## Dependencies
1. ROS(Noetic)
2. gazebo-plugins
3. ROS map server
4. ROS velodyne-description
5. map file(not contained here)
## Launch the robot model in map
1. Download both this package and the package of lab2 into the ros workspace, such as `catkin_ws/src`
2. Download Map Server into the ros workspace
3. Download the map data into a folder named `bags` under this directory
4. Build all the package with `catkin_make` in the root directory of ros workspace
5. Source all the packages with `souce devel/setup.bash`
6. Change the `bag_path` in `launch/ros_bag.launch` to the path to the map data
7. Launch the model with `roslaunch navvis_rosbag ros_bag.launch`
## Launch the robot model as Lab 2
`roslaunch navvis_rosbag update_display.launch use_xacro:=true`


