# ERC-hackathon-2025

This repository contains all the required documentation, design files, and code for the **ROS2 Robotics Hackathon: Warehouse Automation Quest**.

The hackathon focuses on the design of an **autonomous warehouse management robot** capable of navigating a warehouse environment, detecting misplaced packages, and organising inventory on designated shelves.

Your solution should consist of:
- **Mechanical design**
- **Electronics interfacing**
- **Autonomous behaviour implementation**

All three tasks are aimed toward a single final goal, yet can be worked on independently.

📅 **Submission Deadline:** **16th August, 11:59 PM**

---

#### Teams with complete submissions will be eligible for evaluation and rewards 🙂
___

## Problem Statement

With the rapid growth of e-commerce, warehouse automation has become essential. Manual sorting and organisation are no longer scalable, motivating the need for intelligent robotic systems.

Robotics as a domain can broadly be divided into:

1. **Design**  
   (Mechanical structure and electronics: what components and sensors make up the robot)
2. **Perception**  
   (Understanding the environment using sensors and vision)
3. **Planning**  
   (Deciding actions based on tasks and environment)
4. **Control**  
   (Executing actions accurately and safely)

All four aspects are closely linked in real-world systems.  
This hackathon introduces at least one task from each domain, while keeping tasks modular to encourage focused learning and experimentation.

___

## Setting Up the Environment

### Mechanical Design and Analysis
- Use **Fusion 360** or **OnShape** for CAD modelling  
- Perform structural analysis using **ANSYS**  
- Include torque calculations, gear ratios, and safety factors  

---

### Electronics Design and Interfacing
- Circuit simulation using **TinkerCAD**
- Dual microcontroller architecture:
  - Master controller: communication & decision making  
  - Slave controller: motor and sensor interfacing  
- PCB design using **KiCad**
- Clearly document power calculations and component choices  

---

### Automation (Perception, Planning & Control)

**System Requirements:**
1. Linux (Ubuntu 22.04 recommended)
2. **ROS2 Humble**
3. **Gazebo Fortress**
4. **OpenCV**

**Core Tasks:**
- Autonomous navigation in a warehouse environment  
- Path planning (A*, RRT, RRT*)  
- Dynamic obstacle avoidance  
- Colour-based box detection (RGBY)  
- ArUco marker-based shelf identification  

All automation code should be well-commented and tested in simulation.

___

## Submission Requirements

Your repository should include:
- CAD files and design screenshots  
- Electronics simulation files and PCB designs  
- ROS2 workspace and source code   
- Proper documentation of assumptions and decisions  

Ensure the repository is well-organised and easy to navigate.

___

## Contact Information

### Automation
- Kevin B Mathew – 7776063339  
- Dev Thacker – 9819824645  
- Aryan Goyal – 8872251132  
- Indrajit Mandal – 8016070647  

### Electronics
- Saransh Agrawal – 7389076379  
- Dev Thacker – 9819824645  
- Aryan Goyal – 8872251132  
- Parth Jaju – 8310685729  

### Mechanical
- Kevin B Mathew – 7776063339  
- Parth Jaju – 8310685729  
- Ranadip Chakraborty – 9315053413  
- Nilesh Bhatia – 9967039969  



