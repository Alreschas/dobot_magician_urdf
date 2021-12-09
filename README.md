# dobot_magician_urdf

dobot magician robot model with suction cup.

![dobot_magician_urdf](https://user-images.githubusercontent.com/29659091/145319979-ef698dc4-961c-4366-af46-5bacf9f9f4ff.png)


# About This package
This package can display dobot magician robot model on rviz.
This package only contains robot model, so you have to make controller(or use another package) when you control the robot.

# Getting Started
```
mkdir -p ros/src
cd ros
git clone [this repository] src/dobot_magician_urdf
catkin_make (or catkin build)
source devel/setup.bash
roslaunch dobot display.launch
```

you can use joint_state_publisher_gui to check the behavior.
```
rosrun joint_state_publisher_gui joint_state_publisher_gui
```

