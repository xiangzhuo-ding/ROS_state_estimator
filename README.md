# ROS state estimator
This is the repository for robotics course projects.

For more infomantion please go to https://xiangzhuo-ding.github.io/ROS_Projects.html

## Requirements:
1. Environment: Ubuntu 16.04
2. ROS Kinetic
3. xterm


## Set up the workspace:
1. Go to each project.
2. Run ```catkin_make```

## Let's run it!
1. Run ```source devel/setup.bash``` for each terminal
2. Start GUI
    ```rosrun state_estimator gui.py```
3. Start robot
    ```rosrun state_estimator robot.py```
4. Start estimator
    ```rosrun state_estimator est.py```
