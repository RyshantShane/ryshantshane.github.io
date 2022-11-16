## Inverse kinematics solution using neural and non-neural based appraches for SCORBOT-ER-4U

![C9B1DD19-A87C-446F-B812-4F6A2489C620](https://user-images.githubusercontent.com/115636470/195352061-e06a1ddb-171f-4e06-b982-0f9726e376bc.jpeg)

Over the past years, various industries are moving towards automation, the reason is that there is a need for accuracy, efficiency in the areas of repeated tasks, high productivity and economically beneficial for the industrial process. Many challenging tasks can be achieved can be achieved at higher rate of success by introducing autonomous robotic applications. A flexible and dependable solution for industrial robotics teaching and training is the ScorBot ER-4U. Tabletop, pedestal, or linear slidebase mounting options are available for the ScorBot ER-4U robot arm. The robot is backed by ScorBase robotics programming and control software, which makes it well-suited for both stand-alone operations and integrated use in automated work cell applications including robotic welding, machine vision, CNC (computer numerical control) machine tending. Scorbot-ER-4u is used in so many experiments to analyse and control the robotic aim in regards to various purposes. There are various applications associated with Scorbot-ER-4u which includes machine tending (Milling/Turning/Laser engraver), material handling, it also can be used for Automated storage and retrieval system and machine vision system for quality control. Apart from these applications, the scorbot-ER-4u is used in the study of Robotics field to visualize more in forward kinematics, inverse kinematics of the robot. There has been a toolbox designed for MATLAB which is titled “MTIS SCORBOT toolbox”, this particular toolbox interfaces and simulates the interlink SCORBOT-ER-4U with MATLAB. This toolbox basically allows the users to control SCORBOT, retrieve sensor information from SCORBOT and also visualize the aspects of the SCORBOTS movements.


## SCORBOT-ER-4u
The SCORBOT-ER-4U is a 5 Degree of Freedom (DOF) robotic arm whose joints are revolute. For this specific robotic arm, there are a total of 6 motors which controls the base, shoulder, elbow, pitch, and roll joints. Other than that, the gripper is governed by the 6th rotor which controls the opening and closing of the gripper. The joints that associated with the SCORBOT-ER-4u are all revolute, the base is associated with the yaw angle, shoulder, elbow, wrist is associated with the pitch angle.
Kinematics is associated without taking into account the forces driving the motions. It also includes the manner in which various linkages move.
The robotic arm parts:
- Manipulator
- Pedestal
- End effectors Joints
- Revolute Joints
- Prismatic Joints
- Spherical Joints
 

![53146FC7-2CB2-459E-8098-B1F6E0A9D313](https://user-images.githubusercontent.com/115636470/195354069-fa59106a-55f9-4914-b315-ef10fced4c93.png)

## Data Generation

1) Obtained the combination of angles by combining the angles of Base, Shoulder, Elbow, Roll, Pitch. 

2) Obtain the X and Y coordinates 

3) Generate Data 1, Data 2, Data 3, Data 4, Data 5 

4) Each Data having the matrix dimension ( n x 3) which defines X: Y: Theta

5) Extracting the value of theta and arranging it in (n x 5) matrix 

6) Utilizing the forward kinematics command and inserting it a “for loop” to    obtain the values for X, Y, Z, P, R. 


![image](https://user-images.githubusercontent.com/115636470/202313649-b825bb07-a861-4f57-889e-567b6e512f26.png)

## RESULTS 

![image](https://user-images.githubusercontent.com/115636470/198419326-35269908-d668-4797-b1ed-8bb8b4e8b72d.png)

![image](https://user-images.githubusercontent.com/115636470/198419295-eefe1210-48d6-468b-a79e-02677d2ba833.png)

![image](https://user-images.githubusercontent.com/115636470/198419348-14a9e700-b5c3-4080-bbc0-3464373eed4e.png)

## Shallow Neural Network Approach


 ```tsql
 SELECT *
 FROM sys.tables
 WHERE [name] = 'SomeTable'
 ```

