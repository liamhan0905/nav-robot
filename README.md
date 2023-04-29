# nav-robot

`source nav-robot/install/setup.bash`

terminal 1
`ros2 run micro_ros_agent micro_ros_agent serial --dev /dev/ttyACM0`

terminal 2
`ros2 run teleop_twist_keyboard teleop_twist_keyboard --remap cmd_vel:=robot/cmd_vel`
