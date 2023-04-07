# Path Planning for a mobile Robot and turtlebot3 with obstacle avoidance and non holonomic constraints using A-star Search Algorithm
Project - 03 (Phase 02) for the course ENPM661 - Planning for Autonomous Robots

## Team Members
- Mothish Raj Venkatesan Kumararaj (mr2997@umd.edu)   Directory ID: mr2997    UID: 117553727 


- Satish Vennapu (satish@umd.edu)    Directory ID : satish     UID : 118306759

## Project Description
Implement A* Algorithm to find a path between the start and end point on a given map for a mobile
robot and Turtlebot3 with non-holonomic constraints in ROS, Gazebo. 

* **A-star** : A* Search algorithm is one of the best and popular technique used in path-finding and graph traversals.




### Dependencies

* NumPy
* cv2
* Matplotlib
* math
* heapq
* pygame
* time
* itertools
* threading
* sys
* rospy
* geometry_msgs




### Steps to run the implementation
```
git clone:  
```

#### Part1:
1. Run the python file
2. The program prompts for user inputs and takes the user inputs from the console

#### Part2:
1. Clone the repository
2. Install latest version of Python and the required libraries mentinoned above prior to running the code
3. Add the ros package into the src folder of the catkin_ws and run the catkin_make command 
4. roslaunch the launch file and run the python file 
5. The program prompts for user inputs and takes the user inputs from the console
6. Exploration of nodes starts and the optimal path is displayed in 2D map and gazebo



 ```
 python3 sourceCode.py
 ```
## Results


ADD THE screenshots here

### Test Case for Part 1: 
Please enter the clearance: 10
Please enter the x-coordinate of start: 11
Please enter the y-coordinate of start: 11
Please enter the orientation of start: 0
Please enter the x-coordinate of goal: 400
Please enter the y-coordinate of goal: 25
Please enter the orientation of goal: =30
Please enter the left wheel rpm: 30
Please enter the right wheel rpm: 40

### Test Case  for Part 2: 
Please enter the clearance: 22
Please enter the x-coordinate of start: 100
Please enter the y-coordinate of start: 24
Please enter the orientation of start: 0
Please enter the x-coordinate of goal: 400
Please enter the y-coordinate of goal: 24
Please enter the orientation of goal: 0
Please enter the left wheel rpm: 50
Please enter the right wheel rpm: 50



### Constraints in the program
1. The sum of the clearance and the robot always equals to 22  for part 2
2. The map is scaled down by 10 and its in cms
3. Gazebo origin is located at the center and the robot spawning in our case is shifted to the bottom left corner



### Video URL

