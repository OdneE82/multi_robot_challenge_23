# multi_robot_challenge_23

For the first commits for the navigation algorithm, see: https://github.com/OdneE82/DAT160-SemesterProject

division of work:

odne: navigation.

knut: ar tags.

keyser: communication.


running:

colcon build --symlink-install

source install/setup.bash

ros2 launch multi_robot_challenge_23 rescue_robots_w1.launch.py

ros2 launch controller.launch.py
