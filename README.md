# 🤖 Industrial Robotic Wheel Assembly (Mitsubishi RV-2F-D)

## 📌 Project Overview
This project involves programming a **6-Axis Mitsubishi RV-2F-D Industrial Robot** to perform an automated wheel assembly operation. The system simulates a real-world manufacturing line where rims and hubcaps are assembled with high precision.

## ⚙️ Hardware & Tools
* **Robot:** Mitsubishi RV-2F-D (6-Axis)
* **Controller:** CR750-D
* **End-Effector:** Pneumatic Gripper
* **Programming Interface:** Teaching Box (R56TB) & RT ToolBox3

## 🛠️ Key Features
* **Point-to-Point Control:** Optimized trajectory planning for pick-and-place operations.
* **I/O Management:** Synchronization with external feeders and pneumatic systems.
* **Safety Protocols:** Emergency stop logic and collision detection zones.

## 📄 Algorithm Logic
1.  **Initialize:** Robot moves to HOME position.
2.  **Pick Rim:** Move to feeder -> Activate Gripper -> Lift.
3.  **Place:** Move to assembly fixture -> Deactivate Gripper.
4.  **Pick Hubcap:** Change orientation -> Grip hubcap.
5.  **Assembly:** Insert hubcap into rim with defined tolerance.
6.  **Cycle End:** Return to SAFE position.
