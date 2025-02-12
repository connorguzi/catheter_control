# Roboendo ROS2 Repo
This is all of the code written to control the Maxon EPOS2 motors using ROS2. Currently the code is updated to be able to set the motors to a set position given the user input.
## How to test the motors:
In one terminal run: `$ source install/setup.bash` and then `$ ros2 run maxon_driver maxon_driver`. Then in another terminal run `$ source install/setup.bash` again, and after: `$ ros2 run motor_test motor_test`. The program will then prompt you to give motor position inputs - maybe in units of 10^-5 rad???