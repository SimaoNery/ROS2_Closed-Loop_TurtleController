# ROS 2 Closed-Loop Turtle Controller

A lightweight ROS 2 package implementing a closed-loop trajectory controller and asynchronous service client for `turtlesim`.

## Features
- **Closed-Loop Control:** Subscribes to `/turtle1/pose` and dynamically adjusts velocity commands on `/turtle1/cmd_vel`.
- **Asynchronous Service Calls:** Uses `rclpy` service clients to call `/turtle1/set_pen` based on spatial coordinates.
