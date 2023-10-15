# Design of Cartesian-based Cylindrical Manipulator
## MarsQuest: Robotic Arm for Red Planet Exploration

*Pawan Maddheshiya, Shirshak Ghatak, Kumar Ujjawal, Vivek Kumar, Shrijal, Raj Mehta, Devyanshu Singhal*

- **Department of Mechatronics and Automation Engineering,** Indian Institute of Information Technology, Bhagalpur, Bihar
- **Department of Computer Science & Engineering,** Indian Institute of Information Technology, Bhagalpur, Bihar

**Keywords:** Cylindrical Manipulator, OpenCV, GRBL

**Abstract:**
Our latest creation, The Vision-Guided Cylindrical Manipulator, is crafted for Mars Rover missions. Displaying streamlined kinematics that utilizes G-code, this device operates seamlessly and calibrates with ease via limit switches. With an end effector designed for collecting samples and, sensors and computer vision tools for onboard testing, this manipulator collects valuable data that is promptly transmitted to the base station through its onboard computer.

## Introduction

- Cylindrical manipulator robots have a cylindrical workspace and consist of linear and rotational movements.
- Features vertical linear axis (Z-axis), radial linear axis (R-axis), and rotational axis (θ-axis) around the vertical axis.
- Structure includes a vertical column mounted on a revolute joint at the base, with an arm extending radially and rotating around the column.
- Advantages:
  - Ability to reach around obstacles within the cylindrical workspace.
  - Suitable for applications where access to the target object may be obstructed.
  - Compact footprint due to vertical column and radial arm design.
  - Cost-effective due to simplicity.

- Common Applications:
  - Industries: assembly, packaging.
  - Tasks: loading, unloading machines where access to target object may be limited.

- **Incorporating Vision Control with OpenCV:**
  - Elevates robotic system capabilities.
  - Enables real-time perception and interaction with the environment.
  - Facilitates tasks: object recognition, tracking, manipulation.
  - Enhances autonomy and versatility.
  - Meets demand for automation in complex environments.