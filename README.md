# 3p71-A1

**Group Collaborators:**
+ Nico Buccilli
+ Subquat Siddiqui
+ Adam Chorzepa
+ Carter Nicholson
+ Ali Faour

Link to Word Doc Reflection (VIEW ONLY FOR INSTRUCTORS): https://brocku-my.sharepoint.com/:w:/g/personal/ds23xq_brocku_ca/IQBnq-gd9DK0Rba-gxF7NBAcAb1JQxX6PXDKchGLy1_ObJg?e=S6iJmn

**HOW TO LAUNCH**
1) SSH into the robot using: ssh ubuntu@ubuntu (Password: ubuntu)
2) Position the robot in the correct starting location
3) Run: python3 test.py to run the comamnd

**APPROACH TAKEN**
We prioritized using the built-in odometry to control the robot, opting for a hard-coded open-loop (set, autonomous commands) that depends on the in-built ros2 topics. This approach not only made it quicker to develop but was a much safer approach given our collective experience and the provided assignment timeframe. 

**KNOWN LIMITATIONS**
Limitations primarily relate to the downsides of a hard-coded program. Since it is hard-coded, the solution to the problem can only be solved one way (the hard-code). The robot does not autonomously solve the problem on its own using sensors or anything similar.

**PER-MEMBER CONTRIBUTIONS**
+ Subquat Siddiqui:
  - Created written reflection, measured the distance robot needed to travel during test runs and assisted in calibrating those measurements into code.
+ Adam Chorzepa:
  - Helped develop and implement the robot's code, translating our planned sequence of actions into a working program.
  - Worked with teammates during testing to verify measurements and ensure the robot moved as expected.
  - Proposed using odometry-based movement to drive the robot to it's target positions instead of fixed movement durations or hard-coded distances.
+ Nico Buccilli:
  - Helped develop initial robot movement
  - Worked with teammates during testing to verify measurements and ensure the robot moved as expected.
  - Created and organized GitHub repo inital setup as well as inital document organization
+ Carter Nicholson + Ali Faour:
  - Helped getting the robot working initially, setting up ssh and tailscale.
  - Spent last lab getting proper robot movements set up, and getting the actual code working.
  - Wrote the code to finalize robots movements.
  - Got robot to be able to pick up cube without adjustments
+ Ali Faour:
  - Helped develop and debug the robot's code, contributing to the implementation and refinement of its movement logic.
  - Worked with teammates to troubleshoot the robot, making multiple test attempts and code adjustments to get it running correctly.
  - Assisted in testing and verifying the robot's movements to ensure it completed the required tasks as expected.

