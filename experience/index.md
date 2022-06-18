---
layout: default
title: Experience
heading: Experience
---


# Machine Learning Engineer (Perception, Localization, and Mapping) @ [Dematic](https://www.dematic.com/en-us/products/products-overview/agv-systems/), [Kion Mobile Automation](https://www.kiongroup.com/en/Landing-Pages/KION-Mobile-Automation/)
- Developing intelligent, automated solutions for manufacturing, warehouse, and distribution environments, sold by [KION Group](https://www.kiongroup.com/en/About-us/KION-at-a-glance/) and its operating units [Dematic](https://www.dematic.com/en-us/products/products-overview/agv-systems/), [STILL](https://www.still.de/en-DE/intralogistics-systems/automation-systems.html) and [Linde](https://www.linde-mh.com/en/Products/Automated-Trucks/). 
- Directly involved with developing on-vehicle Simultaneous Localization and Mapping (SLAM) software for [AGVs](https://www.kiongroup.com/en/News-Stories/Stories/Automation/Story-Detail_19968.html) and [AMRs](https://www.kiongroup.com/en/News-Stories/Stories/Growing-in-China/Story-Detail_34432.html). Also contributing to automated driving algorithms for [collaborative AGVs](https://www.kiongroup.com/en/News-Stories/Press-Releases/Press-Releases-Detail.html?id=33024&type=internal&title=Excellent%20picking%20performance:%20STILL%20OPX%20iGo%20neo%20triumphs%20at%20Telematics%20Award) performing order picking.
- Improved accuracy and robustness of the reflector extraction algorithm leading to sub-centimeter accuracy.
- Developed a Gazebo-based virtual testing pipeline to improve line extraction algorithm using hyperparameter tuning.
- Improved speed of feature-based association algorithm by 50%, leading to a 30% faster localization pipeline. Analyzed real-time CPU utilization of SLAM processes and threads using Valgrind, LTTng, and perf.
- Standardized the pallet pick/drop testing at physical warehouses. The accuracy-repeatability analysis was done using an external laser tracking system by Faro. Also, a procedure to calibrate lidar, steering encoder, and traction encoder was created.
- Developed a python-based tool to visualize recorded SLAM logs, and automated their offline performance analysis.
- Evaluated the use of Visual Inertial Odometry and GraphSLAM to improve AGV navigation in warehouse environments.
- Certified [SAFe (Scaled Agile Framework) Practitioner](https://www.youracclaim.com/go/eCNozIcD) and trained to use Scrum, Kanban, and XP in a SAFe environment.
- To see the AGVs in action at customer sites, check out the videos [here](https://www.youtube.com/watch?v=qnB6AhUDGwE), [here](https://www.youtube.com/watch?v=kYLGAisXTNk), [here](https://www.youtube.com/watch?v=MRJD1L6-Q1M) and [here](https://www.youtube.com/watch?v=KZww5lcbfNk).

<div class="center">
    <video autoplay loop playsinline muted style="width:49%;">
        <!--https://www.youtube.com/watch?v=_zAH9TiMPgU-->
        <source src="../assets/experience/AGVs.mp4" type="video/mp4">
        Your browser does not support the video tag.
    </video>
    <video autoplay loop playsinline muted style="width:49%;">
        <source src="../assets/experience/AMRs.mp4" type="video/mp4">
        Your browser does not support the video tag.
    </video>
</div>
<br />


# [Robotics Software Engineer Nanodegree Program](https://www.udacity.com/course/robotics-software-engineer--nd209) @ Udacity 
- ## Localization, Mapping, and Path Planning for Autonomous Vehicles in Factories [(repo)](https://github.com/ssharma1991/factorybot)
    - Simulated Automated Guided vehicles (AGVs) and Autonomous Mobile Robots (AMRs) in a warehouse environment.
    - Mapped a virtual environment, by manually moving an AGV and creating an occupancy grid map. The AGV only had a 2D lidar sensor on it. Localized an AMR using the same map while controlling it manually or autonomously using path planning. Simulated a complete pick and drop operation. ROS packages like gmapping, AMCL, and move_base were used.
    - Used SLAM to manually move an AMR through a virtual environment and create a loop-closed 3D graph map using RTAB-Map. The AMR used a 3D camera and a 2D lidar sensor to create the map for localization.
    - Programmed an AMR to autonomously follow a moving reflective ball target using a 2D camera.

<div class="center">
    <img src="../assets/experience/robo1_mapping_gmapping.gif" style="width:99%;">
</div>
<div class="center">
    <img src="../assets/experience/robo2_mapping_RTABMap_viewer.png" style="width:99%;">
</div>
<div class="center">
    <img src="../assets/experience/robo3_pick_and_place.gif" style="width:99%;">
</div>
<br />

- ## Path Planning for KUKA robotic arm [(repo)](https://github.com/ssharma1991/kuka-robotics-challenge)
    - Used A-star path planning to move a payload through a 2D maze using a KUKA industrial robotic arm as part of [KUKA Robotics Challenge](https://www.udacity.com/kuka-robotics-challenge).

<div class="center">
    <img src="../assets/experience/robo4_maze_solving.gif" style="width:99%;">
</div>
<br />


# [Self-Driving Car Engineer Nanodegree Program](https://www.udacity.com/course/self-driving-car-engineer-nanodegree--nd0013) @ Udacity
- ## Lane Detection [(repo1)](https://github.com/ssharma1991/autonomous-car-basic-lane-detection), [(repo2)](https://github.com/ssharma1991/autonomous-car-advanced-lane-detection)
    - Created a robust image processing pipeline to detect a highway lane in an image, pre-recorded video, or live feed from a dashcam.
    - Calculated the car's position within lane and lane curvature using perspective transform and polynomial fitting.

- ## Traffic Sign Classification [(repo)](https://github.com/ssharma1991/autonomous-car-traffic-sign-classification)
    - Developed a LeNet inspired convolution neural network using TensorFlow to classify the GTSRB traffic sign dataset.
    - Achieved 94.8% accuracy on test dataset by data augmentation and image enhancement using OpenCV.

- ## Traffic Light Awareness
    - Used SSD Mobilenet for real-time traffic light detection and classification.

- ## Behavioral Cloning [(repo)](https://github.com/ssharma1991/autonomous-car-behavioral-cloning)
    - Designed an end-to-end convolution neural network using Keras that predicts steering angles from dash-cam images.
    - Successfully cloned human driving behavior to autonomously steer a car around a virtual test track after neural network tuning and data augmentation.

- ## Sensor Fusion [(repo)](https://github.com/ssharma1991/autonomous-car-sensor-fusion)
    - Implemented car location estimation algorithm using extended Kalman Filter based on LIDAR and RADAR sensor data.

- ## Localization [(repo)](https://github.com/ssharma1991/autonomous-car-localization)
    - A 2D particle filter for sparse localization is designed and uses GPS and sensor data with a landmark map.

- ## Trajectory Planning [(repo)](https://github.com/ssharma1991/autonomous-car-highway-driving)
    - A Finite State Machine based planner is created to achieve autonomous highway driving with other cars.
    - Jerk minimized trajectories are considered to enhance occupant safety.

- ## Control [(repo)](https://github.com/ssharma1991/autonomous-car-PID-control)
    - A PID controller is implemented to maneuver a vehicle around a virtual track using steering, throttle, and brake. 

- ## System Integration
    - Robot Operation System (ROS) is used to robustly combine Perception, Planning, and Control.

<div class="center">
    <img src="../assets/experience/car1_behavioral_cloning.gif" style="width:55%;">
    <img src="../assets/experience/car2_highway_driving.gif" style="width:42%;">
</div>
<div class="center">
    <img src="../assets/experience/car3_basic_lane.gif" style="width:37%;">
    <img src="../assets/experience/car4_PID.gif" style="width:26.5%;">
    <img src="../assets/experience/car5_sensor_fusion.gif" style="width:33%;">
</div>
<br />


# Research Assistant @ CAD Innovation and Engineering Lab
- ## Robotics
    - Developed [SnappyXO](http://snappyxo.com/), a laser-cut design-driven robotics platform that enables designing mechanisms, structures, and robots. It has successfully raised $16K+ on [Indiegogo](https://www.indiegogo.com/projects/snappyxo-a-design-driven-robotics-education-kit) for a crowdfunding campaign.
    - Organized workshop "Designing, Prototyping and Programming Robot Motions using MotionGen and SnappyXO" at [IDETC 2018](https://archive.asme.org/events/idetccie2018/program/workshops-tutorials) and "Kinematic Summer School" at [IDETC 2019](https://sites.google.com/stonybrook.edu/2019kiss).
    - Mentored multiple teams, as part of the Vertically Integrated Projects [(VIP)](https://www.stonybrook.edu/commcms/vertically-integrated-projects/teams/_team_page/team_page.php?team=Robotics-driven%20Engineering%20Design%20Exploration) program, for Robotics-driven Engineering Design Exploration. Some of the projects were Walking Robots, Self-driving Car, Sumo/Battle Bot, Biomimetic Robots, Drones, and Bots with Arduino alternative microcontrollers.
    - Assisted in developing and improving [Rehabilitation Robots](https://www.stonybrook.edu/commcms/mobilityassist/) for sit-to-stand assist and gait correction. 
    - Collaborated with [ROAR lab](https://roar.me.columbia.edu/home) at Columbia University on the design of spatial robots for neck rehabilitation. 
    <!-- -Used Xbox Kinect to detect 2D hand pose and synthesized planar mechanisms with similar motion. -->

    <div class="center">
    <img src="../assets/experience/snappyxo1.gif" style="width:42%;">
    <img src="../assets/experience/snappyxo2.gif" style="width:56%;">
    </div>
    <br />


- ## Mechanism Design Software [(repo)](https://github.com/ssharma1991/MotionGen-Server)
    - Developing a Computational Framework for Data-Driven Mechanism Design Innovation supported by $450K [NSF grant](https://nsf.gov/awardsearch/showAward?AWD_ID=1563413).
    - Created [MotionGen](https://www.stonybrook.edu/commcms/motiongen/), a web-based mechanism design framework. Try it out [here](http://cadcam.eng.sunysb.edu/).
    - It uses MEAN (MongoDB, Express.js, Angular.js, Node.js) stack to create a RESTful web service based on MVC architecture. 
    - Both [iOS](https://apps.apple.com/us/app/motiongen/id1065657088) and [Android](https://play.google.com/store/apps/details?id=com.stonybrookuniversity.motiongen&hl=en&gl=US) apps have been created using Apache Cordova framework.

    <div class="center">
    <img src="../assets/experience/MotionGen1.gif" style="width:36%;">
    <img src="../assets/experience/MotionGen2.gif" style="width:32%;">
    <img src="../assets/experience/MotionGen3.gif" style="width:29%;">
    </div>
    <br />
    

- ## Research and Algorithms
    - Path synthesis of mechanisms based on Fourier descriptor fitting using Nelder-Mead and Simulated Annealing optimization.
    - Mixed motion and path mechanism synthesis using optimal non-uniform DFT and Singular Value Decomposition.
    - Real-time simulation of planar, spherical, and spatial mechanisms with prismatic and revolute joints using Newton-Raphson optimization.
    - Developed unified planar, spherical, and spatial mechanisms synthesis techniques using Homotopy continuation method for simultaneous type and dimensional synthesis.
    - Developing machine learning based techniques for path synthesis using spatial platform linkages.
    
    <div class="center">
    <img src="../assets/experience/Simulation1.gif" style="width:48%;">
    <img src="../assets/experience/Simulation2.gif" style="width:50%;">
    </div>
    <div class="center">
    <img src="../assets/experience/MotionGen_Motion.gif" style="width:25%;">
    <img src="../assets/experience/MotionGen_path.gif" style="width:38%;">
    <img src="../assets/experience/MotionGen_Mixed.gif" style="width:34%;">
    </div>
    <div class="center">
    <img src="../assets/experience/Sph1.gif" style="width:34%;">
    <img src="../assets/experience/Sph2.gif" style="width:31%;">
    <img src="../assets/experience/Sph3.gif" style="width:31%;">
    </div>
    <br />


# Product Design @ Vivonics, Inc.
- Coordinated with the design team on developing PMT Monitor, a portable medical headset that detects head trauma.
- Generated concepts for a mechanism that adjusts the interpupillary distance between the lenses focusing on manufacturability and robustness.

<div class="center">
    <img src="../assets/experience/vivonics_PMT1.jpg" style="width:70%;">
    <img src="../assets/experience/vivonics_PMT2.png" style="width:28.5%;">
</div>
<br />


# Design and Manufacturing @ Leviathan Energy
- Designed and manufactured a Hydro-kinetic turbine with an improved airfoil design that produces 50% more power in collaboration with Leviathan Energy.
- Created engineering models using Solidworks and Autodesk Inventor and fabricated parts by FDM based 3D printing.

<div class="center">
    <img src="../assets/experience/leviathan_blade1.png" style="width:53%;">
    <img src="../assets/experience/leviathan_blade2.jpg" style="width:45.5%;">
</div>
<br />


# Research Fellow @ IIIT Jabalpur
- Led a $70k+ research project funded by the Science and Engineering Research Board titled “Development of Additive-Subtractive Integrated Rapid Prototyping System for Improved Part Quality”.
- Spearheaded design and manufacturing teams to create a new hybrid 3D printing process using Pellet based Screw Extruder with CNC machines. Created Toolpath Planning strategies to manufacture CAD models using Hybrid Manufacturing techniques.

<div class="center">
    <img src="../assets/experience/JRF1.jpg" style="width:36%;">
    <img src="../assets/experience/JRF2.PNG" style="width:61.5%;">
</div>
<div class="center">
    <img src="../assets/experience/JRF3.jpg" style="width:99%;">
</div>
<br />

# Design @ Sara Sae
- Involved with product development of Hydraulic Tongs used in the oil and gas industry.
- Carried out Kinematic and Dynamic analysis to find the most probable failure regions.
<div class="center">
    <img src="../assets/experience/hydraulic_tongs.gif" style="width:43%;">
    <video autoplay loop playsinline muted style="width:56%;">
        <source src="../assets/experience/hydraulic_tongs.mp4" type="video/mp4">
        Your browser does not support the video tag.
    </video>
</div>
<br />