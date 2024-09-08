# QuantumBot

## Install and Build
Ensure you have ROS2 installed

From the project root run:

``
source install/setup.zsh
``

``
colcon build --symlink-install
``

``
ros2 launch quantumbot rsp.launch.py  
``

In another terminal instance, run:

``
rvisz2
``