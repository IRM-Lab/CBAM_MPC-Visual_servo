# CBAM_MPC-Visual_servo
Robust MPC Visual Servoing System Based on Consensus Rotation Prior
# Robust MPC Visual Servoing System Based on Consensus Rotation Prior

> **Confidentiality Notice:** > This repository serves as a preliminary visual showcase for an ongoing research project. The associated manuscript is currently in preparation/under review. To protect intellectual property, the source code, detailed mathematical formulations (CDMR framework), and MPC cost function designs are temporarily withheld. 
> *Full details and open-source code will be released upon publication.*

## 📌 Project Overview

Visual servoing in complex environments often fails due to feature matching degradation. This project introduces a novel perception-control synergy framework that robustly handles extreme visual conditions. 

**Key Capabilities Demonstrated:**
* **Extreme Robustness:** Maintains stable tracking and servoing under strong illumination changes and large rotations.
* **Low Inlier Ratio Tolerance:** Effectively filters outliers with $O(N)$ linear complexity, securing accurate pose estimation even when the inlier ratio is extremely low.
* **Safety-Aware Control:** Dynamically adjusts Model Predictive Control (MPC) safety penalty weights based on real-time visual-geometric confidence.

---

## 🔍 Visual-Geometric Matching Performance

The following comparison illustrates the performance of our Consensus Directional Matching and Rotation Prior (CDMR) framework against baseline methods under challenging conditions (strong light interference and large rotational viewpoints).

*(请在此处放入你的特征匹配对比图)*
![Feature Matching Comparison Under Extreme Conditions](assets/你的匹配对比图文件名.png)
*Figure 1: Feature matching comparison. Our method reliably extracts consensus inliers despite extreme illumination and severe rotation, outperforming standard RANSAC-based pipelines in low-inlier scenarios.*

---

## 🎥 Real-World Servoing Demonstration

The video below demonstrates the closed-loop MPC visual servoing system in action. Notice the smooth and safe control responses even when visual observations are heavily corrupted.

*(请在此处放入你的系统运行录屏或实验视频)*
<video src="assets/你的伺服实验视频文件名.mp4" controls width="100%"></video>

---

## 📬 Contact

For academic inquiries or discussions regarding the general approach and experimental setup, please feel free to reach out via email.
