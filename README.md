# franka_ros2

This contains modification of original control library for franka.

If you have already installed the original one, please delete it first.

```bash
$ cd ~/ros2_ws/src
$ git clone https://github.com/Task-Intelligent-Robotics-Research-Grp/franka_ros2.git --recursive
$ rosdep install --from-paths . --ignore-src --rosdistro humble -y
$ cd ~/ros2_ws
$ colcon build --symlink-install --cmake-args -DCMAKE_BUILD_TYPE=Release
```

ROS2 topic-based torque controller can be found https://github.com/Task-Intelligent-Robotics-Research-Grp/fr3_bimanual_robot.git