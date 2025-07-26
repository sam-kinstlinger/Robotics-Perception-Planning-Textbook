# Robotics: Perception & Planning
<img width="1078" height="1652" alt="image" src="https://github.com/user-attachments/assets/1f670c48-1763-499a-aaae-488aea42b8a3" />


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

## 📑 Table of Contents

- **Preface** - 5  
- **About the Authors** - 6  

### Section I: Introduction to Cognitive Robotics
- Chapter 1: Introduction to Perception & Planning – 7  
- Chapter 2: Machine Learning – 14  
  - 2.1 Introduction to Machine Learning – 14  
  - 2.2 Optimization – 21  
    - 2.2.1 Iterative Optimization – 21  
    - 2.2.2 Gradient Descent – 24  
  - 2.3 Neural Networks – 29  
    - 2.3.1 Piecewise Universal Function Approximation – 29  
    - 2.3.2 Piecewise Linear Universal Function Approximation – 32  
    - 2.3.3 Shallow Neural Networks – 37  
    - 2.3.4 Deep Neural Networks – 51  
  - 2.4 Classification – 61  

### Section II: Planning
- Chapter 3: Path Planning and Mapping – 70  
  - 3.1 Introduction to Path Planning – 70  
  - 3.2 Introduction to Machine Planning – 77  
  - 3.3 Global Path Planning – 83  
  - 3.4 Mapping – 89  
    - 3.4.1 Map Creation – 89  
    - 3.4.2 Grid Mapping – 92  
  - 3.5 Graph-Based Planning Algorithms – 99  
    - 3.5.1 Intro to Graph-Based Path Planning – 99  
    - 3.5.2 Single vs. Multi-Query Planning – 106  
    - 3.5.3 Cell Decomposition – 112  
    - 3.5.4 Probabilistic Roadmaps (PRM) – 115  
    - 3.5.5 Dijkstra’s Algorithm – 123  
    - 3.5.6 A* Algorithm – 131  
    - 3.5.7 D* Algorithm – 133  
    - 3.5.8 RRT – 138  
  - 3.6 Local Path Planning – 148  
    - 3.6.1 Intro to Local Planning – 148  
    - 3.6.2 Artificial Potential Field – 151  

- Chapter 4: Reinforcement Learning – 161  
  - 4.1 Introduction – 161  
  - 4.2 Reward Functions – 165  
    - 4.2.1 Bellman Equations – 165  
    - 4.2.2 Reward Design – 168  
  - 4.3 Exploration vs. Exploitation – 171  
  - 4.4 Q-Learning – 179  
  - 4.5 Deep Q-Learning – 186  
  - 4.6 DDPG – 194  

- Chapter 5: Task Execution – 202  
  - 5.1 Reactive Control – 202  
  - 5.2 Finite State Machines – 203  
  - 5.3 Hierarchical FSM – 206  

### Section III: Localization
- Chapter 6: Sensor Fusion – 210  
  - 6.1 Sensor Values as Probability Distributions – 210  
  - 6.2 Sensor Calibration – 213  
  - 6.3 Intro to Sensor Fusion – 218  
  - 6.4 Recursive Estimation – 222  
  - 6.5 State Space Modeling – 224  
  - 6.6 Particle Filter – 227  
  - 6.7 Kalman Filtering – 241  
    - 6.7.1 KF – 241  
    - 6.7.2 UKF – 257  

- Chapter 7: SLAM – 266  
  - 7.1 Introduction – 266  
  - 7.2 Iterative Closest Point (ICP) – 269  

### Section IV: Computer Vision
- Chapter 8: Image Processing – 275  
  - 8.1 Intro to Computer Vision – 276  
  - 8.2 Cameras – 280  
  - 8.3 Convolutional Neural Networks – 286  
    - 8.3.1 Image Classification – 286  
    - 8.3.2 Convolution Layers – 288  
    - 8.3.3 Pooling – 297  

- Chapter 9: Object Detection – 300  
  - 9.1 Introduction – 300  
  - 9.2 Sliding Window – 302  
  - 9.3 Evaluating Output – 309  
  - 9.4 YOLO – 318  

- Chapter 10: 3D Vision – 327  
  - 10.1 Depth Perception – 327  
  - 10.2 Camera Calibration – 331  
  - 10.3 Stereo Vision – 338  
    - 10.3.1 Horizontal Stereo – 338  
    - 10.3.2 Block Matching – 343  
    - 10.3.3 Semi-Global Matching – 344  
    - 10.3.4 ML Approaches – 353  

### Section V: Multiple Robots
- Chapter 11: Multi-Robot Systems – 355  
  - 11.1 Introduction – 355  
  - 11.2 Coordination – 356  
    - 11.2.1 Introduction – 356  
    - 11.2.2 Decentralized Control – 357  
    - 11.2.3 Centralized Control – 359  
  - 11.3 Task Allocation – 362  
  - 11.4 Communication – 372  
    - 11.4.1 Introduction – 372  
    - 11.4.2 Direct vs. Indirect – 374  

- **Glossary** – 377  
- **References** – 423  
