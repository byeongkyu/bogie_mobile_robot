# bogie_mobile_robot
The mobile robot platform which has a rocker-bogie machanism


# Launch

    $ roslaunch bogie_mobile_robot_gazebo bringup.launch
    $ roslaunch bogie_mobile_robot_control bringup_controller.launch
    $ rosrun teleop_twist_keyboard teleop_twist_keyboard.py cmd_vel:=base_controller/cmd_vel
