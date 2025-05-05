# Mycobot_280jn_description
This is a simple urdf description of the mycobot 280jn with gripper and camera.

# DESCRIPTION
This is a simple custom mycobot configuration for pick and place.

# INSTALLATION
```
mkdir -p mycobot_ws/src
cd mycobot_ws/src
git clone https://github.com/logesh1516/Mycobot_280jn_description.git
cd ..
colcon build 
```
# URDF

![mycobot_urdf](https://github.com/user-attachments/assets/8dbc6458-5efb-498d-98ed-4563bffb1cc2)

# SIMULATION
```
cd mycobot_ws
source install/setup.bash
ros2 launch mycobot_description mycobot_280_jn.launch.py
```
