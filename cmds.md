# Commands

Connect DevContainer to robot
zenoh-bridge-ros2dds -e tcp/10.82.0.XXX:7447

List topics
ros2 topic list -v

Teleop
ros2 run teleop_twist_keyboard teleop_twist_keyboard

Open rviz
rviz2 -d /opt/ros/lcas/install/share/limo_description/share/rviz/model_sensors_real.rviz
