# Refueling_Robot

This project was developed by **Akhilrajan Vethirajan** and **Vishaal Kanna Sivakumar** as the final project for the ENPM 662 Course at the UNiversity of Maryland, USA

1.  Extract the robot_arm.zip file.
2.  Copy robot_arm folder into the src folder of your catkin workspace.
3.  Navigate to catkin work space and open a terminal. Enter catkin_make.
4.  Source your workspace using ~/catkin_ws/devel/setup.bash to update all changes.
5.  In your catkin work space, execute : ```roslaunch robot_arm project2.launch```
6.  Go to the src folder inside robot_arm and open a terminal. Do ```chmod +x trajectory_publisher.py``` to make it an executable file.
7.  Then enter ```rosrun robot_arm trajectory_publisher.py``` to launch the controller.
8.  The robot arm stabilizes at the default configuration, then starts  to follow the predefined trajectory.
9.  Code execution ends once the task is done.  


### Execution video link ###
https://drive.google.com/file/d/1OrHhpGoBn2qK5oGbAFsT2hGMDXmJHmIB/view?usp=sharing
