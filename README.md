# 3p71-A1

**Group Collaborators:**
+ Nico Buccilli
+ Subquat Siddiqui
+ Adam Chorzepa
+ Carter Nicholson
+ Ali Faour

Link to Word Doc Reflection: https://brocku-my.sharepoint.com/:w:/g/personal/ds23xq_brocku_ca/IQBnq-gd9DK0Rba-gxF7NBAcAb1JQxX6PXDKchGLy1_ObJg?e=S6iJmn

**HOW TO LAUNCH**
1) SSH into the robot using: ssh ubuntu@ubuntu (Password: ubuntu)
2) Position the robot in the correct starting location
3) Run: python3 test.py to run the comamnd

**APPROACH TAKEN**
We prioritized using the built-in odometry to control the robot, opting for a hard-coded open-loop (set, autonomous commands) that depends on the in-built ros2 topics. This approach not only made it quicker to develop but was a much safer approach given our collective experience and the provided assignment timeframe. 

**KNOWN LIMITATIONS**
Limitations primarily relate to the downsides of a hard-coded program. Since it is hard-coded, the solution to the problem can only be solved one way (the hard-code). The robot does not autonomously solve the problem on its own using sensors or anything similar.

**PER-MEMBER CONTRIBUTIONS**
[text goes here]
