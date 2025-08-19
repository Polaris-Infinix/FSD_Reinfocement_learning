# FSD_Reinforcement_Learning

This repository documents the development of an **end-to-end autonomous driving system** using **reinforcement learning** in simulation. The goal is to train a car to drive intelligently through complex environments using **AWSIM** (Autonomous Vehicle Simulation).
The car's is conitunously getting updated. New environemnt scenarious are being added and the reward function is being refined 

---

## Project Overview

- Simulation powered by **AWSIM** (Unity + ROS2)
- Control policy trained using **Proximal Policy Optimization (PPO)**
- Designed reward functions for realistic driving behavior:  
  lane keeping, smooth turning, obstacle avoidance
- **End-to-end architecture**: from **LiDAR point clouds** to **drive commands**
- Perception encoded with **PointNet++**

---

## Demo

A video showing the environment and simulation is available here:  


https://github.com/user-attachments/assets/573ad777-109f-4e1b-9f94-d49e136a111f



This is in the initial video of the training. As the training progess better results are expected .
---

## Setup Instructions

To replicate this project, you will need:

1. Clone and set up [AWSIM](https://github.com/tier4/AWSIM)
2. Install **ROS 2 Humble** and required dependencies
3. Integrate **ros2-for-unity** bridge between Unity and ROS
4. Insert trained model weights (coming soon) into the inference node
5. Launch the simulator and run the RL inference pipeline

> Note: Codebase is currently private. If you're interested in collaboration or details, feel free to reach out.

---

## Technologies Used

- Unity + AWSIM for simulation
- ROS 2 for inter-process communication
- PyTorch for training the PPO agent
- Custom PPO implementation
- PointNet++ for LiDAR-based perception

---

## Contact

Interested in collaborating or learning more?  
Reach out via:

- **Email**:pastaysaisagar@gmail.com  
- **LinkedIn**: [linkedin.com/in/saisagarsp ](http://www.linkedin.com/in/sai-sagar-s-p-18b1b5236)

---

## License & Usage

This project and its outputs are intended for **non-commercial, research, and educational use only**.  
Full model and training results will be released soon.
