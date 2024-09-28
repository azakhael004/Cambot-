# CamBot
CamBot is a 7 Dof robot with a depth camera and a multicamera system attached to its tool flange.
This repository contains the files needed to simulate it in a ros2 environment

![image](https://github.com/user-attachments/assets/d3fa243e-48c7-4421-beb0-f233fe32fcd5)

Make sure that you have properly installed ros2 and gazebo within your system.
Create a workspace folder and a src folder within and add this package to the src folder.
Build it using the colcon build command on your terminal


To visualize the robot in gazebo execute the following command

ros2 launch cambot_description gazebo.launch.py

You should expect an output like this

![image](https://github.com/user-attachments/assets/71228a6f-9420-409d-9f28-57bcf8e25a28)



To visualize the robot in rviz2 execute the following command

ros2 launch cambot_description display.launch.py

You should expect an output like this

![image](https://github.com/user-attachments/assets/c69bf809-fd4d-42cb-b15f-40f48c9e056b)




