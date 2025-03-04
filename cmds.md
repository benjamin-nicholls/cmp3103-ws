# Commands

Connect DevContainer to robot

```bash
zenoh-bridge-ros2dds -e tcp/10.82.0.XXX:7447
```

List topics

```bash
ros2 topic list -v
```

Teleop

```bash
ros2 run teleop_twist_keyboard teleop_twist_keyboard
```

Open rviz

```bash
rviz2 -d /opt/ros/lcas/install/share/limo_description/share/rviz/model_sensors_real.rviz
```
