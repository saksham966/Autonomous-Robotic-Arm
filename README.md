# 🤖 ROS 2 Robotic Arm

A 5-DOF robotic arm designed and simulated using **ROS 2**, **URDF/Xacro**, and **SolidWorks**. This project focuses on creating a complete digital twin of a robotic manipulator by designing custom CAD models, converting them into STL meshes, and integrating them into a ROS 2 environment for visualization, kinematic modeling, and future motion planning.

## 📌 Features

- Custom-designed robotic arm modeled in SolidWorks.
- Complete URDF/Xacro robot description.
- 5 Degrees of Freedom (DOF) articulated manipulator.
- Fixed and revolute joints with joint limits.
- TF tree generation using `robot_state_publisher`.
- Interactive joint control using `joint_state_publisher_gui`.
- Real-time visualization in RViz2.
- RGB camera mounted on the robot base.
- Modular package structure for easy expansion.

## 🛠️ Technologies Used

- ROS 2
- URDF
- Xacro
- RViz2
- robot_state_publisher
- joint_state_publisher_gui
- TF2
- SolidWorks
- Python
- Linux (Ubuntu)

## 📂 Project Structure

```
arduinobot_ws/
│── src/
│   ├── arduinobot_description/
│   │   ├── meshes/
│   │   ├── urdf/
│   │   ├── launch/
│   │   ├── rviz/
│   │   └── package.xml
```

## 🚀 Getting Started

### Clone the repository

```bash
git clone <repository_url>
```

### Build the workspace

```bash
cd arduinobot_ws
colcon build
source install/setup.bash
```

### Launch the robot

```bash
ros2 launch arduinobot_description display.launch.xml
```

## 📷 Visualization

The robotic arm can be visualized in RViz2 with interactive joint manipulation using `joint_state_publisher_gui`.

## 🔮 Future Improvements

- MoveIt 2 integration
- Gazebo simulation
- Inverse Kinematics
- Motion Planning
- Pick and Place operations
- ROS 2 Control integration
- Camera-based object detection
- Autonomous manipulation

## 👨‍💻 Author

**Saksham Badal**

If you found this project useful, consider giving it a ⭐ on GitHub.
