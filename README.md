# Inverse-kinematic-modeling-using-robo-analyzer-

 
## AIM: 
To analyze the inverse kinematics using DH parameters for a 3 dof planer and 3 dof articulated robot using roboanalyzer and polt the graph of joint angle for a given  input end effector position .


### COMPONENTS REQUIRED:
1.Robo analyzer software  


### THEORY: 
  
### Inverse Kinematics
 

Inverse kinematics is the use of kinematic equations to determine the motion of a robot to reach a desired position. For example, to perform automated bin picking, a robotic arm used in a manufacturing line needs precise motion from an initial position to a desired position between bins and manufacturing machines. The grasping end of a robot arm is designated as the end-effector. The robot configuration is a list of joint positions that are within the position limits of the robot model and do not violate any constraints the robot has.

 Most industrial robots are constructed of several independently controllable articulated joints. Each joint is connected to one or more of the other joints, sometimes in complex configurations. The end effector is attached at the end of the entire “kinematic chain”. When you move any one joint, this will affect the end effector’s pose in various ways.

This means that there is no simple, direct relationship between the end effector position and any one particular joint.

For example, if you want the robot’s end effector to move 1 mm linearly along the Z-axis, you may need to move all of the joints by a different amount.

Finally, inverse kinematics algorithms calculate the exact position of each of the robot’s joints required to reach your desired end effector pose.

### solving inverse kinematic model 
![image](https://user-images.githubusercontent.com/36288975/170622829-3fe97ef7-8ef1-44af-afae-b0954871aa0c.png)


![image](https://user-images.githubusercontent.com/36288975/170622902-f48fd9c7-f2ec-4fd5-904b-ea51be8298c3.png)

![image](https://user-images.githubusercontent.com/36288975/170622934-a3fd7f77-7eb2-4408-b66d-d6e3adbd1f99.png)

![image](https://user-images.githubusercontent.com/36288975/170622982-9c4d8b23-1563-4e17-9616-87bcc4f4501d.png)
![image](https://user-images.githubusercontent.com/36288975/170623020-f27efc12-bb58-4f62-840d-af544ac6689e.png)

### PROCEDURE:
1.Open the roboanalyzer software.

2.Select the robot and its degrees of freedom.

3.Change the values of X and Y wherever necessary.

4.Stimulate the model for inverse kinematics.

5.Plot the graph between the joints.

6.Update the DH parameters of the link configuration and end effector configuration.






### SIMULATION :
RPR ROBOT:

![image](https://github.com/Naveenaa28/Inverse-kinematic-modeling-using-robo-analyzer-/assets/131433133/c4b5cebb-c20a-475a-a664-d0c81fbea2fe)
![image](https://github.com/Naveenaa28/Inverse-kinematic-modeling-using-robo-analyzer-/assets/131433133/d2d9401f-6416-4fe6-bb1c-611f61e558c3)
3R ROBOT:
![image](https://github.com/Naveenaa28/Inverse-kinematic-modeling-using-robo-analyzer-/assets/131433133/3252bd2d-73be-4e15-ae94-0c79e159ec22)
![image](https://github.com/Naveenaa28/Inverse-kinematic-modeling-using-robo-analyzer-/assets/131433133/5f4fe75f-5ffc-4b44-a318-f8717db431a2)





 
 
 
 
 
 ### PLOT 
RPR ROBOT:
![image](https://github.com/Naveenaa28/Inverse-kinematic-modeling-using-robo-analyzer-/assets/131433133/94fee6bd-99c0-47ab-9165-e8d3f35d99af)
![image](https://github.com/Naveenaa28/Inverse-kinematic-modeling-using-robo-analyzer-/assets/131433133/a77fbaed-0c6a-4305-b914-9cddabb106ef)
3R ROBOT:
![image](https://github.com/Naveenaa28/Inverse-kinematic-modeling-using-robo-analyzer-/assets/131433133/07a57feb-1c55-4821-b0ae-526859f3c933)
![image](https://github.com/Naveenaa28/Inverse-kinematic-modeling-using-robo-analyzer-/assets/131433133/8550ff21-13a5-44c8-81fe-87a4799269ca)

 
 
 
 
 
 
 
 
 
 
 

 
 














### RESULTS :  Thus,the inverse kinematics using DH parameters for a 3 dof planer and 3 dof articulated robot using roboanalyzer is analysed and the graph of joint angle for a given input end effector position is plotted.
