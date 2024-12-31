# rsx_arm_moveit_2025

This is the MoveIt 1 package of the 2025 RSX arm. It was generated using the MoveIt setup assitant. Make sure to clone the [2025 Arm URDF package](https://github.com/rsx-utoronto/Arm_URDF_2025)!

## Setup

This is under the assumption that you're following the format set in the main rsx [rsx-rover](https://github.com/rsx-utoronto/rsx-rover).
```
cd ~/rover_ws/src
git clone git@github.com:rsx-utoronto/Arm_URDF_2025.git
git clone git@github.com:rsx-utoronto/rsx_arm_moveit_2025.git
```

Then build and source you workspace.

## Running
```
roslaunch rsx_arm_moveit_2025 demo.launch
roslaunch rsx_arm_moveit_2025 demo_gazebo.launch
```
