# ROS2 Middleware

This repository demonstrates setting up different rmw (ros2 middleware).

## Zenoh

**installation:** 
```bash
sudo apt install ros-jazzy-rmw-zenoh-cpp
```

For local communication, export the following environment variable in you shell.
```bash
export RMW_IMPLEMENTATION=rmw_zenoh_cpp
```

Lastly, just start the zenoh router for local discovery!
```bash
ros2 run rmw_zenoh_cpp rmw_zenohd
```

Reference: [link1](https://github.com/ros2/rmw_zenoh) [link2](https://www.youtube.com/watch?v=fS0_rbQ6KKA)
