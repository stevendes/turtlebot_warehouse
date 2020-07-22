# turtlebot_warehouse
Package that contains Turtlebot models for Gazebo and a Warehouse world.

## How to launch any turtlebot on the Warehouse world

In general

`TURTLEBOT3_MODEL=<model of the turtlebot> roslaunch t_gazebo  launch_gazebo.lauch gui:=<"true" or "false" depending if you want to lauch gazebo with graphics or not>`

For example

`TURTLEBOT3_MODEL=waffle_pi roslaunch t_gazebo  launch_gazebo.lauch gui:=true`

The model that has the cameras added for the demo is the *waffle_pi*
