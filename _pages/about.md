---
permalink: /
title: "About Me"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I'm currently the Research Scholarship Block Postdoctoral Fellow (RSB-PDF) at Nanyang Technolgoical University with Prof. [Yang Liu](https://www.ntu.edu.sg/home/yangliu/). 
I obtained my Ph.D. degree at 2019 from Nanyang Technological University, Singapore, under the supervision of Profs. [Hesuan Hu](https://web.xidian.edu.cn/hshu/), [Yang Liu](https://www.ntu.edu.sg/home/yangliu/), and [Shang-Wei Lin](https://www.ntu.edu.sg/home/shang-wei.lin/), and
the Master degree at 2015 from Zhejiang Sci-Tech Universitory, Hangzhou, China, under the supervision of Prof. Zuohua Ding.

My research aims to provide safety and security (S&S) guarantees for Autonomous Unmanned Systems (AUSs, such as mobile robots, autonomous vehicles, and unmanned aerial vehicles) during their whole life cycles, from system design and system testing to run-time monitoring and self-adaptation.

- **S&S-By-Design Algorithms**. We focus on designing novel and efficient motion planning algorithms for AUSs to guarantee their safety and security in dynamic, complex, open, and unpredictable environments using various technologies, such as discrete event systems, mathematical programming, and deep learning.

  - **Distributed motion planning of multi-Robot systems**. 
  To guarantee the safety, performance, and flexibility of a multi-robot system, we focus on distributed algorithm design for motion control of multi-robot systems. (1) Based on discrete event systems and supervisory control theory, we design distributed algorithms to avoid collisions and deadlocks, especially higher-order deadlocks, as well as guarantee motion permission; (2) Based on kinematic equations of robots and optimization, we will design fully distributed algorithms to generate collision-free continuous control commands to robots, so each robot can move in a distributed manner with robustness; (3) Combining discrete and continuous parts, we design distributed hybrid algorithms to deal with collisions and deadlocks, as well as guarantee computation efficiency. 

  - **Robust motion  planning against robot failures and attacks**. 
   We are addressing the following problems: (1) In case of failed robots, we will design robust control algorithms such that the failed robots block the minimum number of robots in the systems; (2) In case that a robot is under attack, we will design algorithms such that the robot can continue its motion safely to escape the attack region or reach a safe station; (3) When a robot is completed attacked and cannot move well, we will design algorithms such that other normal robots in the system can avoid collisions with the attacked robot and finish the given tasks assigned to the system.

  - **AI-aided motion planning**. 
  In case of obstacle-clustered and/or dynamic environments, real-time motion planning is usually time-consuming. AI technologies leverage an offline learning procedure to offload online computation. However, its predictability and interpretability is still a challenge, so we cannot apply AI technologies directly to control safety-critical systems. Hence, it is significant to investigate what and how AI technologies can give aid to traditional motion planning methods. Detailedly, we are exploring the integration of AI technologies and traditional motion methods.

  - **Requirement-adaptation motion planing**.
  Due to its open and complex environments, a multi-robot system may suffer from conflicts among different motion requirements. Hence, a multi-robot system needs to adapt its requirements during its motion. We focus on the following tasks along this direction: (1) Deep understanding of different requirements (e.g., safety, security, performance, privacy, ethic, regulations) for a multi-robot systems; (2) Detection of conflict requirements during robot motion; and (3) Self-adaptation for conflict requirements. 

- **Safety and Security Testing**.
Using AI testing, traditional software testing, and control theory, we focus on efficient methods to generate critical scenarios and evaluate the safety and security of AUSs.
  - **Autonomous Driving System (ADS) Testing Framework**. To facilitate ADS testing, we focus on the design of a unified testing framework, which includes: (1) A language to describe scenarios, (2) A langugate to describe test specifications, and (3) Algorithms to generate critical scenarios. 
  - **Map-Driven Autonomous Driving System (ADS) Testing**. Currently, the motion of an autonomous vehicle relies on the HD maps. How to evaluate the safety of the ADS on the whole map is challenging due to the complexity of the map structures. To guarantee test sufficiency and efficiency, we focus map-model driven ADS testing, including (1) topology modeling and classification of a map, (2) scenario characterization under the topology classification, and (3) scenario generation.
  - **Guided ADS Testing**. We focus on designing different metrics to guide the generation of diverse and critical scenarios.  For example, we have proposed a behavior-guided fuzzing technique to explore the different behaviors of the autonomous vehicle, where an efficient unsupervised model is proposed to characterize the behavior of the autonomous vehicle.
  - **Security of ADS**. We investigate potential attacks and threats against AUSs. (1) We investigate the potential threats in ROS and ROS2, which are widely used in industrial robots. (2) We investigate potential physical-world backdoor attacks against different modules in an ADS, such as the lane detection module.

- **Safe and Secure Operation**. After AUSs are deployed in the real world, we investigate real-time anomaly detection and mitigation using deep learning technologies with the MAPE (Monitor-Analyse-Plan-Execute) framework.

Contact
======
**Address**: N4-B2C-06, Cyber Security Lab, 
School of Computer Science and Engineering, Nanyang Technological University,
50 Nanyang Avenue, Singapore 639798

**Email**: y.zhou AT ntu DOT edu DOT sg
