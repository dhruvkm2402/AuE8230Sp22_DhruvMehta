# AuE8230Sp22_DhruvMehta
Hi, My name is Dhruv Mehta. I'm a PhD in Automotive Student at CU-ICAR under Dr. Venkat Krovi. My research focuses on enhanced mobility for Autonomous Ground Vehicles in off-road environment.
This repo consists of all the codes related to AuE8230 Autonomy Science and Systems taught by Dr. Venkat Krovi in Spring 2022.

Each Assignment/Project will be stored in Catkin_ws
Route is catkin_ws/src/assignments.

  For Assignment 2 it is:
    catkin_ws/src/assignment2_ws
    Turtlebot codes:
      assignment2_ws/turtlesim_cleaner/src
      1) Move_in_circle - This code makes turtlebot sim move in a circle of constant angular velocity and radius of 3
              ![Circle](https://user-images.githubusercontent.com/99369975/153435762-09e621ff-d08c-4a06-9903-e59243d00d6b.png)

              
      2) square_openLoop - This code makes the bot move in a square based on length, speed and angular velocity  
          ![squareopenloop](https://user-images.githubusercontent.com/99369975/153435828-4406102a-4b01-4475-b777-a865c60b2c57.png)

          
      3) GotoGoal - This code make the bot move in a square with proportional control and predefined coordinates as goals.
          
          ![gotogoal](https://user-images.githubusercontent.com/99369975/153435867-d137458d-29d6-48b2-9979-e8a8a89ef887.png)

      To run these files:
      first: roscore
      In new terminal: rosrun turtlesim turtlesim_node
      In new terminal: rosrun turtlesim_clenaer example.py
