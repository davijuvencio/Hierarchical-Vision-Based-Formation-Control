# Hierarchical Vision-Based Formation Control (HVFC)

This repository contains the implementation of the **Hierarchical Vision-Based Formation Control (HVFC)** method for Unmanned Aerial Vehicles (UAVs). The HVFC is designed to enable precise and scalable formation control of UAVs using only a monocular camera and ArUco markers. The method is based on relative visual information, eliminating the need for direct communication between drones.

## About the Project

The HVFC method allows each UAV in a formation to follow a leader drone using visual feedback from ArUco markers. It ensures that drones maintain predefined geometric formations while navigating through various scenarios. The method has been validated in simulated environments with formations like narrow paths, lateral formations, and more complex setups such as the "T" formation.

### Features:
- **Scalable:** Can be applied to 'n' drones, forming different geometric patterns.
- **Monocular Camera-Based:** No need for multiple sensors or direct communication.
- **Formation Control:** Ensures robust formation maintenance even in challenging environments.
- **Simulations:** Validated with different mission scenarios including narrow spaces, terrain variations, and obstacles.

## Getting Started

The simulation environment and the controller code will be available once the accompanying article is published. 

### Prerequisites

- ROS Noetic Ninjemys
- PX4 Autopilot
- Gazebo Simulator
- OpenCV (for ArUco marker detection)
- Python (for auxiliary scripts)

## How to Use

Once the code is available, instructions for setting up the environment and running simulations will be provided here.

## Video Demonstration

A video showcasing the simulation will be available here soon:  
[Link to Video Demonstration]()

## Article

The detailed description of the method and experimental results will be available in our article, soon to be published in IEEE Access. Stay tuned for the publication link.

## License

This project will be released under the MIT License after the article publication.

## Contact

For questions or more information, feel free to contact the project team.
