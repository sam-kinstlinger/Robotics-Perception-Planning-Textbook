# Robotics: Perception & Planning
<img width="1078" height="1652" alt="image" src="https://github.com/user-attachments/assets/1f670c48-1763-499a-aaae-488aea42b8a3" />

© 2025 Samuel Kinstlinger, Andrew Xu, Sameer Chawla, and Brian Fugh. All rights reserved.

[Click here to view or download the full PDF](https://github.com/sam-kinstlinger/Robotics-Perception-Planning-Textbook/blob/main/Robotics_%20Perception%20%26%20Planning%20-%20Final%20Copy%20(7).pdf)

[Buy Paperback or Hardcover on Amazon, or EBook for $1.99 to Support the Authors](https://www.amazon.com/dp/B0FK4LLW8Z/ref=sr_1_1?crid=1FNGP465TW7TF&dib=eyJ2IjoiMSJ9.dHFvSIh2AXNGwvnk_qjJRy4wc4uu1bAgmn4Cqtv1ANXQ1HlEH_qzxJurLKOratjFxMCGiNtX-MXX_kclcvyo4p0d-MqSEBxwn7GRyxZCO-MFmEeaJ7Kiuwx96Y8MmJ9TfMbxj-1gyGu9nYPUXKXPKtzZWGu9-KFJz8A5RNW_MjdDdMLcyeJ7MpnWu3S4o1jxnraJ0k5VxQUZEP_Yj6fBtLe30_Vr37OzPlxLTuQog6g.8ZoDE4m2r2GnQg884-OO2vXM6R5SjyG6zQaOo2XUhq8&dib_tag=se&keywords=robotics%3A+perception+and+planning&qid=1753760885&sprefix=robotics+perception+and+planning%2Caps%2C225&sr=8-1)



## 📘 Preface

This textbook is designed to comprehensively cover the core algorithms and paradigms in robotics, with a focus on machine perception and planning. It is intended for both undergraduate and graduate students seeking a deep, principled understanding of robotics.

The central teaching philosophy of this book is to justify each algorithm from first principles, showing when and why it is optimal. Rather than treating techniques as black boxes, we begin with the foundational goals of robotics and derive each algorithm as a solution to those goals. This derivational approach enables students not only to apply algorithms effectively, but also to understand the specific conditions under which they are optimal. It also empowers them to recognize when an algorithm may be suboptimal due to missing or flawed insights. Once students identify these gaps in justification, they are equipped to address them—potentially leading to improved or novel algorithms. In this way, the book not only teaches existing techniques but also cultivates the analytical mindset necessary to advance the field. Throughout the text, we support this learning process with concrete examples, intuitive explanations, and visualizations that illuminate key insights and clarify the rationale behind each method.

> **Note**: If at any point while reading this textbook you cannot recall a term’s definition, please refer to the glossary at the end. To fully benefit from this textbook, it is essential to have the equivalent of one university class in statistics, multivariable calculus, linear algebra, computer programming, and robotics.

---

## 👥 About the Authors

This textbook is a joint effort by four educators and researchers in robotics, machine learning, perception, and planning at the University of Maryland, College Park: **Samuel Kinstlinger**, **Andrew Xu**, **Sameer Chawla**, and **Brian Fugh**.

Each author brings research and industry experience spanning both perception and planning, contributing complementary expertise to the project. The textbook originated as an internal guide for students joining their research team. Frustrated by the prevalence of black-box explanations—where textbooks often present only the procedural steps of algorithms without conveying the underlying reasoning—the authors set out to create a resource that emphasizes deep, principled understanding. This textbook reflects their commitment to transparent, derivation-driven pedagogy that equips students not only to use robotics algorithms, but to truly understand and improve them.

Contact for Questions or Comments: sammypaulk@icloud.com

---

## 📘 Table of Contents

### Preface  
- Preface – p.6  
- About the Authors – p.7

---

### **Section I: Introduction to Cognitive Robotics**

#### Chapter 1: Introduction to Perception & Planning – p.8

#### Chapter 2: Machine Learning – p.15  
- 2.1 Introduction to Machine Learning – p.15  
- 2.2 Optimization – p.22  
  - 2.2.1 Iterative Optimization – p.22  
  - 2.2.2 Gradient Descent – p.25  
- 2.3 Neural Networks – p.31  
  - 2.3.1 Piecewise Universal Function Approximation – p.31  
  - 2.3.2 Piecewise Linear Universal Function Approximation – p.34  
  - 2.3.3 Shallow Neural Networks – p.39  
  - 2.3.4 Deep Neural Networks – p.54  
- 2.4 Classification – p.64

---

### **Section II: Planning**

#### Chapter 3: Path Planning and Mapping – p.75  
- 3.1 Introduction to Path Planning – p.75  
- 3.2 Introduction to Machine Planning – p.81  
- 3.3 Global Path Planning – p.88  
- 3.4 Mapping – p.94  
  - 3.4.1 Map Creation – p.94  
  - 3.4.2 Grid Mapping – p.96  
- 3.5 Graph-Based Planning Algorithms – p.104  
  - 3.5.1 Introduction to Graph Based Path Planning – p.104  
  - 3.5.2 Single vs. Multi-Query Path Planning – p.111  
  - 3.5.3 Cell Decomposition – p.117  
  - 3.5.4 Probabilistic Roadmaps (PRM) – p.120  
  - 3.5.5 Dijkstra’s Algorithm – p.129  
  - 3.5.6 A* Algorithm – p.136  
  - 3.5.7 D* Algorithm – p.139  
  - 3.5.8 Rapidly Exploring Random Trees – p.143  
- 3.6 Local Path Planning – p.154  
  - 3.6.1 Introduction to Local Path Planning – p.154  
  - 3.6.2 Artificial Potential Field – p.156  

#### Chapter 4: Reinforcement Learning – p.167  
- 4.1 Introduction to Reinforcement Learning – p.167  
- 4.2 Reward Functions – p.170  
  - 4.2.1 Bellman Equations – p.170  
  - 4.2.2 Reward Design – p.173  
- 4.3 Exploration vs. Exploitation – p.176  
- 4.4 Q-Learning – p.184  
- 4.5 Deep Q-Learning – p.190  
- 4.6 Deep Deterministic Policy Gradient (DDPG) – p.198  

#### Chapter 5: Task Execution – p.207  
- 5.1 Reactive Control – p.207  
- 5.2 Finite State Machines (FSM) – p.207  
- 5.3 Hierarchical Finite State Machines (HFSM) – p.211

---

### **Section III: Localization**

#### Chapter 6: Sensor Fusion – p.215  
- 6.1 Sensor Values as a Probability Distribution – p.215  
- 6.2 Sensor Calibration – p.218  
- 6.3 Introduction to Sensor Fusion – p.223  
- 6.4 Recursive Estimation – p.227  
- 6.5 State Space Modeling – p.229  
- 6.6 Particle Filter – p.232  
- 6.7 Kalman Filtering – p.246  
  - 6.7.1 Kalman Filter (KF) – p.246  
  - 6.7.2 Unscented Kalman Filter (UKF) – p.263  

#### Chapter 7: Simultaneous Localization & Mapping (SLAM) – p.272  
- 7.1 Introduction to SLAM – p.272  
- 7.2 Iterative Closest Point (ICP) – p.275  

---

### **Section IV: Computer Vision**

#### Chapter 8: Image Processing – p.282  
- 8.1 Introduction to Computer Vision – p.282  
- 8.2 Cameras – p.287  
- 8.3 Convolutional Neural Networks – p.293  
  - 8.3.1 Introduction to Image Classification – p.293  
  - 8.3.2 Convolution Layers – p.295  
  - 8.3.3 Pooling – p.304  

#### Chapter 9: Object Detection – p.307  
- 9.1 Introduction to Object Detection – p.307  
- 9.2 Sliding Window Approach – p.309  
- 9.3 Evaluating Object Detection Output – p.317  
- 9.4 YOLO – p.326  

#### Chapter 10: 3D Vision – p.337  
- 10.1 Introduction to Depth Perception – p.337  
- 10.2 Camera Calibration – p.341  
- 10.3 Stereo Vision – p.348  
  - 10.3.1 Horizontal Stereo – p.348  
  - 10.3.2 Block Matching – p.354  
  - 10.3.3 Semi-Global Matching – p.355  
  - 10.3.4 ML Approaches – p.364  

---

### **Section V: Multiple Robots**

#### Chapter 11: Multi-Robot Systems – p.366  
- 11.1 Introduction to Multi-Robot Systems – p.366  
- 11.2 Multi-Robot Coordination – p.367  
  - 11.2.1 Introduction to Multi-Robot Coordination – p.367  
  - 11.2.2 Decentralized Control – p.368  
  - 11.2.3 Centralized Control – p.370  
- 11.3 Task Allocation – p.373  
- 11.4 Multi-Robot Communication – p.384  
  - 11.4.1 Introduction to Multi-Robot Communication – p.384  
  - 11.4.2 Direct vs. Indirect Communication – p.385  

---

### Conclusion – p.388  
### Glossary – p.389  
### References – p.435
