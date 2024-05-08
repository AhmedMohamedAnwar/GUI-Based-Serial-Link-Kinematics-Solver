# MATLAB App Designer Robot Kinematics Solver

This MATLAB App Designer project tackles robot kinematics for serial manipulators. It offers a user-friendly interface divided into two tabs:

Tab 1: Forward Kinematics
* Specify Link Count: Choose the number of links your robot manipulator possesses.
* Input DH Parameters: Enter the Denavit-Hartenberg (DH) parameters for each link of the manipulator. These parameters are crucial for defining the relationship between frames attached to the links.
* Calculate Forward Kinematics: Compute the robot's end-effector position and orientation based on the provided DH parameters.<br>
Tab 2: Inverse Kinematics (2-Link Robot Only)**
* Limited to 2-Link Robots: This tab's functionalities are currently restricted to robots with two links.
* Define End-Effector Pose: Specify the desired end-effector position and orientation for the robot arm.
* Calculate Inverse Kinematics: Determine two possible solutions for the joint angles (theta1 and theta2) that achieve the given end-effector pose.
* Optional Workspace Visualization: Visualize the robot's workspace by plotting either the manipulator's links or the reachable points within its workspace.

This application is designed with an educational purpose in mind. It serves as a tool to aid users in grasping the concepts of robot kinematics through a user-friendly interface.

Feel free to explore the code and customize the app further to suit your specific needs!




In order to run application you should install Peter Corke toolbox you can install it from this link :)<br>
https://petercorke.com/<br>
In code of WorkSpace in option 2D you should download this folders and set path to this folders and you will find code and explanation there :) <br>
https://github.com/NiklasZ/robotic_arm_workspace/tree/main<br>
Very helpful Link in Inverse Kinematics:<br>
https://www.youtube.com/watch?v=MrR9iVlwlow&t=158s<br>

