# -multi-UAV-simulator
GNC of a SWARM of UAVs in a SITL by Tom Antoine, Alex Martinez and Charalampos Efstratiou- Cranfield University AVDC MSc 2021

This project is composed of two independant but similar repositories:

Simulation_Python : it is used to do numerical simulations on the guidance algorithm fully on Python (https://github.com/tomAntoine/multi-UAV-simulator.git)
Simulation_Gazebo : here, the python code for guidance and navigation is used as SITL, for a Gazebo/ROS/Ardupilot world (below) and in (https://github.com/alexMarFar/multi-UAV-simulator.git)

# -Simulation_Gazebo
Prerequisites:
Python 3.8.5 was employed, so full compability with that or after version Basic Python libraries such as matplotlib, math, etc

Install Ubuntu (version 20.04 employed, but 18.04 should also work)

Install Gazebo and ArduPilot Plugin (https://github.com/Intelligent-Quads/iq_tutorials/blob/master/docs/installing_gazebo_arduplugin.md)

Install ArduPilot and MAVProxy (https://github.com/Intelligent-Quads/iq_tutorials/blob/master/docs/Installing_Ardupilot_20_04.md)

Install ROS and Setup Catkin (noetic employed https://github.com/Intelligent-Quads/iq_tutorials/blob/master/docs/installing_ros_20_04.md, melodic should also work)

Repositories (iq_sim https://github.com/Intelligent-Quads/iq_sim)

Recommended: QGroundControl

All can be easily installed by following the tutorials below: https://github.com/Intelligent-Quads/iq_tutorials and https://www.youtube.com/channel/UCuZy0c-uvSJglnZfQC0-uaQ
