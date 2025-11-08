# Turtlebot

Task1:
Launch TurtleBot3 navigation
 Install TurtleBot package
 Install TurtleBot simulation package
Create map and launch navigation

all the steps in this link
https://emanual.robotis.com/docs/en/platform/turtlebot3/slam_simulation/
then we run it 
https://emanual.robotis.com/docs/en/platform/turtlebot3/quick-start/#pc-setup
after runing the simulator to move the robot around to draw the map 
then we can save the map



Task2:
Study the differences between classic navigation stack and the navigation with reinforcement machine learning.
Applying on ROS not required.

Classic Navigation Stack:
  Uses fixed algorithms like A*, Dijkstra, and SLAM.
  Needs a predefined map and rules.
  Robot follows programmed instructions.
  Does not learn from mistakes.

Reinforcement Learning Navigation:
  Robot learns by trying and getting rewards.
  Does not need all rules predefined.
  Can adapt to new environments.
  Needs long training and many trials.

In short:

Classic = Fixed rules, no learning
Reinforcement learning = Learns from experience and improves over time
