This is like a delivery robot

you can download this repository by fallowing bellow steps

cd catkin_ws/src

git clone https://github.com/Aravind8967/robot_e_description.git

cd ..

catkin_make

------------ To see the robot command is ----------------------

roslaunch robot_e_description gazebo.lauch 

---------------------------- to move the robot command is ----------

rosrun teleop_twist_keyboard teleop_twist_keyboard.py

------------------ for slam and moveit operation ( in another terminal type) ------------

roslaunch robot_e_description display.launch

these are the command to see

this robot has cmd_vel imu laser camera also functionality

---------- you can check publishing topic by ------------

rostopic list

you can check this by publishing

--------------- for imu ----- rostopic echo /imu

---------- for odom ----------- rostopic echo /odom
