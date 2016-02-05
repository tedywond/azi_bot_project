# Robotics

## azi bot project
### STRUCTURE

The **mobile robot** we will be using for this project will have the structure sketched in the picture

The major components of the robot are 
1. Four wheels  
2. Gripper  
3. Depth camera with 270 degrees of rotation 
4. Sonar sensors

The robot will be equipped with four wheels from which 2 are powered and the other 2 are free rotating wheels which will be helpful for the stability by making the center of gravity inside the rectangle of the robot surface. Steering will be handled by **differential steering** method by altering the speed of the wheels to change direction as follows.


The position of the wheels is specified inside to make the wheels distinguishable from the boarders. The robot will also contain a gripper which will increase the ability of the mobile robot by making it do more than moving around. The sonar sensor on the front side of the robot sense the proximity of the robot from anything in front of the robot which will be used to measure distance for things that are not in the views of the depth camera. The depth camera helps the robot interact with the environment by giving it the ability of ‘seeing’ and understanding the distance of the objects in a defined coordinate plane.