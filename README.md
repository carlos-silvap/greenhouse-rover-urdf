# greenhouse-rover-urdf

ROS robot description package for the UMA Grover rover. Contains the URDF model, meshes, and configuration used in the [greenhouse-rover-ros](https://github.com/carlos-silvap/semestre_i) simulation.

![ROS](https://img.shields.io/badge/ROS-22314E?style=flat&logo=ros&logoColor=white)

---

## Repository Structure

```
├── config/      # Robot configuration files
├── launch/      # Launch files for loading the robot model
├── meshes/      # 3D mesh files for visualization
├── urdf/        # URDF robot description
├── CMakeLists.txt
└── package.xml
```

---

## Usage

This package is a dependency of [greenhouse-rover-ros](https://github.com/carlos-silvap/semestre_i). Clone both packages into your catkin workspace:

```bash
cd ~/catkin_ws/src
git clone https://github.com/carlos-silvap/uma_grover
git clone https://github.com/carlos-silvap/semestre_i
cd ~/catkin_ws && catkin_make
```
