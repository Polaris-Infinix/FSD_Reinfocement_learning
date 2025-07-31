# 🧠 FSD_Reinforcement_Learning

This repository showcases an **end-to-end autonomous driving system** trained using **reinforcement learning** in simulation. The agent learns to drive, maneuver, and make intelligent decisions in challenging environments using AWSIM (Autonomous Vehicle Simulation).

---

## 🚗 Overview

- Trained in **AWSIM** (Unity + ROS2 based simulation)
- Uses **Proximal Policy Optimization (PPO)** for control
- Reward functions crafted for realistic lane-keeping, turning, and obstacle avoidance
- End-to-end pipeline from **LiDAR point cloud to control output**
- Perception handled by **PointNet++** as the front-end encoder

---

## 🎥 Demo

Watch the trained agent in action:

📽️ [Link to Demo Video](#)  
📁 `model_final.pth` – Final trained policy weights (download from Releases tab)

---

## 🧪 Setup

To reproduce the results, you will need to:

1. Clone [AWSIM](https://github.com/tier4/AWSIM) and follow its setup instructions
2. Install ROS 2 Humble and dependencies (`ros-foxy-*` if you used a different distro)
3. Bridge Unity and ROS 2 via ros2-for-unity
4. Plug in the trained model weights (`model_final.pth`) into the inference node
5. Launch the simulation and inference pipeline

*Note: Code is not public. For collaboration or detailed implementation queries, feel free to contact me.*

---

## 📦 Contents

- `/models` – Trained policy weights  
- `/videos` – Sample runs and result recordings  
- `/config` – PPO training config (reward shaping, learning rate, etc.) *(optional)*
- `/README.md` – This file  

---

## 🤖 Technologies Used

- Unity + AWSIM (simulation)
- ROS 2 (communication)
- PyTorch (RL + perception)
- PPO algorithm (custom implementation)
- PointNet++ for point cloud processing

---

## 📬 Contact

Want to collaborate or learn more?

📧 email@example.com  
🔗 [LinkedIn](https://linkedin.com/in/your-profile)  
🌐 [Portfolio](https://your-site.com)

---

## ⚠️ License

Trained model and results are released for **non-commercial, research, and educational use only.**
