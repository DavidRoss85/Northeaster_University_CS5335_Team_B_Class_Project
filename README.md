# TurtleBot Semantic Mapping (CS5335 Class Project)

> **Looking for the continued and improved version of this project?**  
> See the follow-on repository with refactored structure and extended navigation work here:  
> [https://github.com/DavidRoss85/Turtlebot_Semantic_Mapping_Navigation](https://github.com/DavidRoss85/Turtlebot_Semantic_Mapping_Navigation)

---

## Northeastern University — CS5335: Robotic Science & Systems  
**Team B**

---

## Overview

This repository contains the **original course project implementation** for CS5335 at Northeastern University.  
The focus of this project was **semantic mapping**, specifically augmenting a traditional occupancy grid map with semantic object information derived from perception.

This repository represents the *course-complete* version of the project and is preserved here for reference, comparison, and academic context.

A more recent and expanded continuation of this work—including improved structure, refactoring, and custom navigation—can be found in the newer repository linked above.

---

## Project Scope (Class Version)

The primary goal of this project was to:

- Detect objects in the environment using a perception pipeline
- Estimate object locations in the world frame
- Overlay semantic object information onto an occupancy grid map
- Visualize the resulting semantic map for the user

The system successfully demonstrates **semantic mapping**, though the implementation reflects the exploratory and time-constrained nature of a semester project.

---

## Implementation Notes

- The semantic mapping pipeline is functional but **not fully optimized**
- Some components are tightly coupled due to project deadlines
- Object placement and inflation behavior can be inconsistent in edge cases
- The system was validated primarily in controlled test environments

Despite these limitations, the project met all course requirements and demonstrated end-to-end semantic mapping.

---

## Running the Project

This repository includes a basic `scripts/` directory intended to help launch the project.

**Important:**  
Running the project assumes that all required dependencies, ROS 2 packages, and system configurations are already installed and correctly set up. The scripts do **not** perform environment setup or dependency resolution.

As a result:
- This repository is best used as a **reference implementation**
- Users attempting to run it should already be familiar with ROS 2, Nav2, and perception pipelines

---

## Technologies Used

- **ROS 2**
- **Python-based ROS nodes**
- **YOLO-based object detection**
- **Occupancy grid mapping**
- **Semantic overlay visualization**
- **TurtleBot platform (simulation and/or hardware)**

---

## Relationship to the Continued Project

This repository represents the **starting point** for the continued work found in:

[https://github.com/DavidRoss85/Turtlebot_Semantic_Mapping_Navigation](https://github.com/DavidRoss85/Turtlebot_Semantic_Mapping_Navigation)

Key differences in the continuation include:
- Major directory and module restructuring
- Cleaner separation between perception, mapping, and navigation
- More configurable and robust semantic mapping
- Introduction of a custom navigation module

This repository is intentionally left unchanged to preserve the original course submission.

---

## Notes

This project reflects a realistic academic robotics workflow:
- Rapid iteration
- Tradeoffs between robustness and scope
- Emphasis on demonstrating concepts rather than production-level polish

It is shared for transparency, learning, and comparison with the later, more refined implementation.
