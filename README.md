ENPM661 Planning: Project 4 - Baxter robot pick and place

Authors:
Nupur Nimbekar, Markose Jacob (Group 30)

File:
ik_pick_and_place_demo.py

Instructions for running the code:
1. We have used Gazebo for this project
2. Copy the py file to your_workspace/src/baxter_simulator/baxter_sim_examples/script
3. Make sure the file is executable 
4. Make sure the models (.urdf) files has been copied to your_workspace/src/baxter_simulator/baxter_sim_examples/models/block
5. Do catkin_make in the workspace
6. Open Gazebo using below commands - 
   a. $ cd ros_ws
   b. $ ./baxter.sh sim
   c. $ roslaunch baxter_gazebo baxter_world.launch
6. Run the python file using following commands -
   a. $ cd ros_ws
   b. $ source devel/setup.bash
   c. $ rosrun baxter_sim_examples ik_pick_and_place_demo.py 

Result:
You will be able to see Baxter robot pick up the red box and place it on the second table and pick up the white box from the second table and place on the first table successfully.




