# Deep_reinforcement_learning_move_cube_robot
This package just for description of moving_cube robot. <br>
In order to run this robot model 3D with Gazebo environment, following instruction: <br>
  $ roscore <br>
  $ roslaunch gazebo_ros empty_world.launch <br>
  $ roslaunch my_moving_cube_description spawn_moving_cube.launch <br>
<br> <br>
In order to run moving cube control, following instruction to kick the robot: <br>
  $ roslaunch my_moving_cube_description moving_cube_control.launch <br>
  $ rostopic pub /my_moving_cube/inertia_wheel_roll_joint_velocity_controller/command std_msgs/Float64 "data: 100.0"

  
