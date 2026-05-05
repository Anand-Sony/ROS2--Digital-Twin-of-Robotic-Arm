# 🤖 ROS2 Digital Twin of Robotic Arm

---

## 🎥 Demo Video  

[Click here to watch the demo](https://github.com/Anand-Sony/ROS2--Digital-Twin-of-Robotic-Arm/raw/main/Demonstration.mp4)

[Click here to watch the demo with real-time data](https://github.com/Anand-Sony/ROS2--Digital-Twin-of-Robotic-Arm/raw/main/Demo%20with%20real-time%20data.mp4)

## 📌 Overview  
This project focuses on developing a **Digital Twin of a Robotic Arm using ROS2**, integrating virtual simulation with real-world robotic system concepts.  
The system enables **real-time visualization, joint control, and simulation**, demonstrating core principles of **robotics, automation, and smart manufacturing**.

## 🚀 Key Features  
- 🔧 Digital Twin development using ROS2  
- 🦾 Robot modeling using URDF/Xacro  
- 🎮 Real-time joint state publishing and control  
- ⚙️ Integration with ros2_control for actuation  
- 🔄 Conceptual virtual–physical synchronization  
- 📊 Scalable for industrial automation applications  

---

## 🏗️ Project Structure  


ROS---Digital-Twin-of-Robotic-Arm/
│
├── twin_description/ # Robot model (URDF/Xacro files)
├── twin_firmware/ # Control and firmware logic
├── README.md # Project documentation


---

## 🛠️ Tech Stack  
- ROS2 (Robot Operating System 2)  
- Python  
- URDF / Xacro  
- Arduino IDE
- ros2_control  

---

## ⚙️ Working Principle  

The digital twin is created by simulating a robotic arm in a ROS2 environment:

1. Robot structure is defined using URDF/Xacro (links and joints)  
2. Kinematic relationships are established between components  
3. ros2_control is used to simulate actuator behavior  
4. Joint states are published and controlled via ROS2 topics  
5. Real-time movement is visualized in simulation tools  

This creates a **virtual replica (digital twin)** of the robotic arm that mimics real-world behavior.

---

## ▶️ How to Run  

### Prerequisites  
- ROS2 (Humble/Foxy recommended)  
- Python 3.x  
- Colcon build tools  

### Steps  

```bash
# Clone the repository
git clone https://github.com/Anand-Sony/ROS---Digital-Twin-of-Robotic-Arm.git

# Navigate to workspace
cd ROS---Digital-Twin-of-Robotic-Arm

# Build the package
colcon build

# Source the workspace
source install/setup.bash

# Launch the simulation (example)
ros2 launch twin_description display.launch.py
```
🎯 Applications
Industrial Automation
Smart Manufacturing
Robotics Simulation
Digital Twin Systems
Cyber-Physical Systems (CPS)
🔮 Future Improvements
Integration with physical robotic hardware
Real-time IoT data synchronization
AI-based predictive maintenance
Web dashboard for monitoring and control
👨‍💻 Author

Anand Soni
Mechanical Engineering Student, MNIT Jaipur

### ⭐ Support

### If you found this project useful, consider giving it a ⭐ on GitHub!
