**Task Aware Dynamic Resource Allocation in
Industrial Private 5G Networks**

**GROUP 9 - Afreen Haider, Soham Guha Mazumder, Aditya Mallick**

HOW TO RUN:
-->Install SUMO along with NetEdit

-->Just click on run.bat!

CODE WORKFLOW:
--> setup_network.py sets up the SUMO factory
--> Multiple iterations of the phy_downlink.py files exist. Current it runs the phy_downlink_5r_rl. This can be changed by changing the USE_RL variable in run_sim.py to FALSE

--> run_sim.py calls phy_downlink_5r_rl.py and setup_network.py and spawns the robots and does the main simulation sequence forever until the user stops in the SUMO GUI
--> run.bat just runs run_sum.py

--> robot_trajectories_5r.csv is compiled after the user exits the simulation and displays the runtime events and all the parameters involved in the simulation for all the robots.
