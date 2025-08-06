# Robotics: Perception & Planning
<img width="1078" height="1652" alt="image" src="https://github.com/user-attachments/assets/1f670c48-1763-499a-aaae-488aea42b8a3" />

© 2025 Samuel Kinstlinger, Andrew Xu, Sameer Chawla, and Brian Fugh. All rights reserved.

[Click here to view or download the full PDF](https://github.com/sam-kinstlinger/Robotics-Perception-Planning-Textbook/blob/main/Robotics_%20Perception%20%26%20Planning%20-%20Final%20Copy%20(9).pdf)

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
# Table of Contents

- Preface ................................................... 6  
- About the Authors ......................................... 7  

## Section I: Introduction to Cognitive Robotics
- Chapter 1: Introduction to Perception & Planning .......... 8  
- Chapter 2: Machine Learning ............................... 13  
  - 2.1 - Introduction to Machine Learning ....................... 13  
  - 2.2 - Optimization ........................................... 17  
    - 2.2.1 - Iterative Optimization ............................. 17  
    - 2.2.2 - Gradient Descent ................................... 20  
  - 2.3 - Neural Networks ........................................ 23  
    - 2.3.1 - Piecewise Universal Function Approximation ......... 23  
    - 2.3.2 - Piecewise Linear Universal Function Approximation .. 25  
    - 2.3.3 - Shallow Neural Networks ............................ 30  
    - 2.3.4 - Deep Neural Networks ............................... 40  
  - 2.4 - Classification ......................................... 47  

## Section II: Planning
- Chapter 3: Path Planning and Mapping ...................... 55  
  - 3.1 - Introduction to Path Planning .......................... 55  
  - 3.2 - Introduction to Machine Planning ....................... 58  
  - 3.3 - Global Path Planning ................................... 63  
  - 3.4 - Mapping ................................................ 66  
    - 3.4.1 - Map Creation ....................................... 66  
    - 3.4.2 - Grid Mapping ....................................... 68  
  - 3.5 - Graph-Based Planning Algorithms ........................ 73  
    - 3.5.1 - Introduction to Graph Based Path Planning .......... 73  
    - 3.5.2 - Single vs. Multi-Query Path Planning ............... 78  
    - 3.5.3 - Cell Decomposition ................................. 81  
    - 3.5.4 - Probabilistic Roadmaps (PRM) ....................... 83  
    - 3.5.5 - Dijkstra’s Algorithm ............................... 88  
    - 3.5.6 - A* Algorithm ....................................... 94  
    - 3.5.7 - D* Algorithm ....................................... 95  
    - 3.5.8 - Rapidly Exploring Random Trees ..................... 98  
  - 3.6 - Local Path Planning ................................... 104  
    - 3.6.1 - Introduction to Local Path Planning ............... 104  
    - 3.6.2 - Artificial Potential Field ........................ 106  

- Chapter 4: Reinforcement Learning ........................ 114  
  - 4.1 - Introduction to Reinforcement Learning ................ 114  
  - 4.2 - Reward Functions ...................................... 116  
    - 4.2.1 - Bellman Equations ................................. 116  
    - 4.2.2 - Reward Design ..................................... 117  
  - 4.3 - Exploration vs. Exploitation .......................... 119  
  - 4.4 - Q-Learning ............................................ 124  
  - 4.5 - Deep Q-Learning ....................................... 128  
  - 4.6 - Deep Deterministic Policy Gradient (DDPG) ............. 132  

- Chapter 5: Task Execution ................................ 138  
  - 5.1 - Reactive Control ...................................... 138  
  - 5.2 - Finite State Machines (FSM) ........................... 138  
  - 5.3 - Hierarchical Finite State Machines (HFSM) ............. 140  

## Section III: Localization
- Chapter 6: Sensor Fusion ................................. 143  
  - 6.1 - Sensor Values as a Probability Distribution ........... 143  
  - 6.2 - Sensor Calibration .................................... 145  
  - 6.3 - Introduction to Sensor Fusion ......................... 148  
  - 6.4 - Recursive Estimation .................................. 151  
  - 6.5 - State Space Modeling .................................. 152  
  - 6.6 - Particle Filter ....................................... 153  
  - 6.7 - Kalman Filtering ...................................... 163  
    - 6.7.1 - Kalman Filter (KF) ................................ 163  
    - 6.7.2 - Unscented Kalman Filter (UKF) ..................... 174  

- Chapter 7: Simultaneous Localization & Mapping (SLAM) .... 180  
  - 7.1 - Introduction to SLAM .................................. 180  
  - 7.2 - Iterative Closest Point (ICP) ......................... 182  

## Section IV: Computer Vision
- Chapter 8: Image Processing .............................. 187  
  - 8.1 - Introduction to Computer Vision ....................... 187  
  - 8.2 - Cameras ............................................... 189  
  - 8.3 - Convolutional Neural Networks ......................... 194  
    - 8.3.1 - Introduction to Image Classification .............. 194  
    - 8.3.2 - Convolution Layers ................................ 195  
    - 8.3.3 - Pooling ........................................... 201  

- Chapter 9: Object Detection .............................. 204  
  - 9.1 - Introduction to Object Detection ...................... 204  
  - 9.2 - Sliding Window Approach ............................... 205  
  - 9.3 - Evaluating Object Detection Output .................... 211  
  - 9.4 - YOLO .................................................. 217  

- Chapter 10: 3D Vision .................................... 225  
  - 10.1 - Introduction to Depth Perception ..................... 225  
  - 10.2 - Camera Calibration ................................... 228  
  - 10.3 - Stereo Vision ........................................ 234  
    - 10.3.1 - Horizontal Stereo ................................ 234  
    - 10.3.2 - Block Matching ................................... 238  
    - 10.3.3 - Semi-Global Matching ............................. 239  
    - 10.3.4 - ML Approaches .................................... 244  

## Section V: Multiple Robots
- Chapter 11: Multi-Robot Systems .......................... 246  
  - 11.1 - Introduction to Multi-Robot Systems .................. 246  
  - 11.2 - Multi-Robot Coordination ............................. 247  
    - 11.2.1 - Introduction to Multi-Robot Coordination ......... 247  
    - 11.2.2 - Decentralized Control ............................ 247  
    - 11.2.3 - Centralized Control .............................. 248  
  - 11.3 - Task Allocation ...................................... 250  
  - 11.4 - Multi-Robot Communication ............................ 256  
    - 11.4.1 - Introduction to Multi-Robot Communication ........ 256  
    - 11.4.2 - Direct vs. Indirect Communication ................ 257  

- Conclusion .............................................. 260  
- Glossary ................................................ 261  
- References .............................................. 289  


---
