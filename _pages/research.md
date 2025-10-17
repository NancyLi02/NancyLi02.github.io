---
layout: archive
title: "Research and Publications"
permalink: /research/
author_profile: true
---

## Publications

{% include pub_card.html id='oath' title='Adaptive Obstacle-Aware Task Assignment and Planning for Heterogeneous Robot Teaming' authors='Nan Li, Jiming Ren, Haris Miller, Samuel Coogan, Karen M. Feigh, and Ye Zhao' venue='Submitted to Transaction on Automation Science and Engineering (T-ASE)' video='https://www.youtube.com/embed/e4uDbfz8S1s' video_external='https://youtu.be/e4uDbfz8S1s' abstract='Multi-Agent Task Assignment and Planning (MATP) has attracted growing attention but remains challenging in terms of scalability, spatial reasoning, and adaptability in obstacle-rich environments. To address these challenges, we propose OATH — Adaptive Obstacle-Aware Task Assignment and Planning for Heterogeneous Robot Teaming — which advances MATP by introducing a novel obstacle-aware strategy for task assignment. First, we develop an adaptive Halton sequence map, the first known application of Halton sampling with obstacleaware adaptation in MATP, which adjusts sampling density based on obstacle distribution. Second, we propose a cluster–auction–selection framework that integrates obstacle-aware clustering with weighted auctions and intra-cluster task selection. These mechanisms jointly enable effective coordination among heterogeneous robots while maintaining scalability and nearoptimal allocation performance. In addition, our framework leverages an LLM to interpret human instructions and directly guide the planner in real time. We validate OATH in NVIDIA Isaac Sim, showing substantial improvements in task assignment quality, scalability, adaptability to dynamic changes, and overall execution performance compared to state-of-the-art MATP baselines.' paper='https://arxiv.org/abs/2510.14063' website='https://llm-oath.github.io/' %}

{% include pub_card.html id='resilient' title='A Hierarchically Integrated Framework for Resilient Task Allocation and Planning in Heterogeneous Multi-Robot Systems' authors='Nan Li, Haris Miller, Jiming Ren, Alagappan Swaminathan, Samuel Coogan, Karen M. Feigh, and Ye Zhao' venue='IEEE ICRA Workshop on Robust Planning and Decision-Making for Autonomous Systems' year='2025' video='https://www.youtube.com/embed/7pSYnkK5tDU' video_external='https://youtu.be/7pSYnkK5tDU' abstract='Traditional methods for task allocation and planning in multi-robot teams are typically offline, assuming that all tasks are known in advance and assigned before mission execution. However, real-world environments require resilient planning algorithms capable of handling unexpected scenarios such as task failures, unstructured environments, robot failures, and low battery levels. To address these challenges, we propose a resilient task allocation and planning framework tailored for heterogeneous multi-robot systems, specifically incorporating drones and ground robots such as Turtlebots. The framework combines a high-level task allocation and planning module with a mid-level behavior tree architecture to manage unexpected events during execution. The task allocation problem involves assigning different types of tasks to a heterogeneous robot team, where each robot has specific capabilities suited to certain tasks. The environment includes both known and unknown elements, such as static and dynamic obstacles, adding uncertainty to planning and execution. The goal is to improve resilience to unexpected situations while keeping mission time short. A video has been prepared to present our algorithm, supplementary technical details, and preliminary experimental results.' paper='/files/ICRA_workshop.pdf' %}

<!-- website='https://sites.google.com/view/robust-planning-icra2025-ws/home?authuser=0' -->

{% include pub_card.html id='tiltrotor' title='Singularity Free Dynamic Control Allocation for Tilt-rotor Multirotor UAVs' authors='Xinyi Liu∗, Nan Li∗, Yifan Wang, Yuanye Dong, Beining Fu, Qi Lu' venue='IEEE International Conference on Automation Science and Engineering (CASE)' year='2023' img='/images/IEEE CASE.png' img_alt='CASE figure' abstract='Tilt-rotor multirotor unmanned aerial vehicles (UAVs) provide flexible flight capability and pose-omnidirectionality. Although numerous control allocation algorithms have been presented with relatively good reliability, some singularity configurations of tilt-rotor UAVs can cause the algorithm to fail in generating a stable solution. This paper proposes a singularity-free dynamic control allocation algorithm that improves the stability of tilt-rotor multirotor UAVs in 6 degrees of freedom (DOFs). The control allocation is formulated as a constrained optimization problem by introducing inequality constraints derived from singular configurations. A barrier function is embedded into the objective function for constraints enforcement. The Lagrange function is then used to form the unconstrained optimization objective function. A Lyapunov-like function is proven to be negative semidefinite, time invariant and bounded. Through Barbalat’s lemma, the algorithm is uniformly globally stable. Simulation results obtained from trajectory tracking at singularities of the tilt-rotor multirotor UAVs in 6 DOFs demonstrate the validity of the proposed dynamic control allocation approach.' paper='https://ieeexplore.ieee.org/abstract/document/10260455' %}

{% include pub_card.html id='exosuit' title='A Segmented Dynamic Movement Primitives-Based Gait Assistive Strategy for Soft Ankle Exosuit' authors='Fashu Xu, Wenjun Huang, Hao He, Nan Li, Hongchen He & Kang Li' venue='International Conference on Intelligent Robotics and Applications' year='2023' img='/images/exoskeleton.png' img_alt='Soft exosuit' abstract='The soft exosuit has been proven to improve the pilot’s walking ability and reduce metabolic consumption, yet its gait assistance strategy still suffers from insufficient personalized adaptation. This paper proposes a Segmented Dynamic Movement Primitives (SDMPs)-based gait assistive strategy. A gait detection algorithm divides a complete gait cycle into four segments, and independent DMPs learn each segment. The normal gait trajectory is referenced and the personalized gait is generated with the spatial-temporal parameters of each DMP automatically adjusted according to sensor data. Experimental results show that the gait of SDMPs is superior to those generated by the traditional method and vanilla DMPs. Force feedback indicates that the gait generated using SDMPs can quickly pull the joint to the desired position in the plantar flexion phase and then quickly complete tension release, which is better than other methods. This method can serve as a new personalized gait assistance strategy for soft ankle exosuits.' paper='https://link.springer.com/chapter/10.1007/978-981-99-6480-2_38' %}

## Robotics Hardware & Demos

{% include proj_card.html id='slam' title='SLAM — TurtleBot Mapping & Goal Navigation' desc='Using TurtleBot to explore an unknown environment and build a map. Tuned navigation parameters for smooth motion, and executed multi-goal navigation to three target waypoints while avoiding obstacles.' video='https://www.youtube.com/embed/2tSF3ZpoCjc' video_external='https://youtu.be/2tSF3ZpoCjc' %}

{% include proj_card.html id='multimodal' title='Multi-Modal Sensing & Navigation — Vision + LiDAR' desc='CNN and OpenCV detect traffic signals for turn/stop decisions; LiDAR wall-following maintains safe clearance and prevents collisions in narrow corridors.' video='https://www.youtube.com/embed/yh35NX4DkwM' video_external='https://youtu.be/yh35NX4DkwM' %}

## Skills

<style>
.skills{display:grid;grid-template-columns:repeat(auto-fit,minmax(230px,1fr));gap:14px;margin-top:10px}
.skill-box{border:1px solid #e8e8e8;border-radius:12px;background:#fff;padding:12px}
.skill-title{font-weight:700;margin-bottom:8px;font-size:1rem}
.skill-tags{display:flex;flex-wrap:wrap;gap:8px}
.tag{border:1px solid #ddd;border-radius:999px;padding:4px 10px;font-size:.9rem;background:#f7f7f7;white-space:nowrap}
</style>

<div class="skills">
  <div class="skill-box">
    <div class="skill-title">Programming</div>
    <div class="skill-tags">
      <span class="tag">Python</span>
      <span class="tag">MATLAB</span>
    </div>
  </div>

  <div class="skill-box">
    <div class="skill-title">Robotics / Autonomy</div>
    <div class="skill-tags">
      <span class="tag">ROS</span>
      <span class="tag">SLAM</span>
      <span class="tag">Multi-Robot</span>
      <span class="tag">Path Planning</span>
    </div>
  </div>

  <div class="skill-box">
    <div class="skill-title">ML / Perception</div>
    <div class="skill-tags">
      <span class="tag">PyTorch</span>
      <span class="tag">OpenCV</span>
    </div>
  </div>

  <div class="skill-box">
    <div class="skill-title">Modeling & Tools</div>
    <div class="skill-tags">
      <span class="tag">SolidWorks</span>
      <span class="tag">CATIA</span>
      <span class="tag">MuJoCo</span>
      <span class="tag">Isaac Lab/Sim</span>
    </div>
  </div>
</div>
