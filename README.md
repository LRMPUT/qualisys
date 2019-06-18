# Qualisys ROS driver

## Changes done from original KumarRobotics/qualisys:
* Fixed code so it compiles on Ubuntu 18.04 with ROS Melodic
* Updated to latest qualisys cpp sdk from https://github.com/qualisys/qualisys_cpp_sdk
* Added new topic with geometry_msgs::PoseStamped
* Each topic (TF/Subject/Pose) can now all be enabled/disabled in launch file, not just TF

## License
Apache 2.0 if not specified otherwise
