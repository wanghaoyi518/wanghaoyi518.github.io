---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

<a href="/files/Haoyi%20Wang_CV.pdf" class="btn btn--primary">Download CV (PDF)</a>

Education
======
- **Washington University in St. Louis**, St. Louis, MO, USA  
  Thesis-Based **M.S. in Electrical Engineering (Honors Program)**, 08/2024 – Present
- **Hong Kong University of Science and Technology**, Hong Kong  
  **B.Eng. in Computer Engineering**, 08/2020 – 08/2023
- **University of California, San Diego**, San Diego, CA, USA  
  Exchange Student, 09/2022 – 12/2022
- **Washington University in St. Louis**, St. Louis, MO, USA  
  HKUST–WashU Joint Education Program, 08/2023 – 05/2024

Research experience
======
- **Integrated Embodied Multi-Agent Task and Motion Planning Framework**, Riverside, CA, USA (05/2025 – Present)  
  Supervisor: Prof. Mingyu Cai  
  Outcome: Deadlock-Free Hybrid RL-MAPF Framework for Zero-Shot Multi-Robot Navigation (L4DC 2026 submission; under review)
  - Developed an integrated multi-agent framework combining LLM-based task decomposition, RL navigation, and MAPF fallback for deadlock resolution.
  - Designed deadlock detection and an interface between decentralized RL control and a local MAPF solver to ensure feasible solutions in extreme cases.
  - Validated the framework in a near photo-realistic interactive simulator across diverse multi-agent task sequences.

- **Human Behavior-Informed Framework for Safe Robot Motion Planning**, St. Louis, MO, USA (09/2024 – 04/2025)  
  Supervisors: Prof. Bruno Sinopoli, Prof. Yiannis Kantaros
  - Built a human action prediction system combining active probing of human characteristics with reachability analysis.
  - Designed an MPC planner that integrates inferred human type and reachable sets as constraints for uncertainty-aware safety.
  - Evaluated the system in driving simulation environments and compared against baseline planners.

- **Human Trajectory Prediction in the Interaction between Human and Unmanned Vehicles**, St. Louis, MO, USA (01/2024 – 05/2024)  
  Supervisors: Prof. Bruno Sinopoli, Prof. Yiannis Kantaros
  - Developed deep learning-based human trajectory prediction and integrated predictions with robot path planning.

- **Transfer Learning in Deep Reinforcement Learning: Self-Supervised Learning for Policy Adaptation**, St. Louis, MO, USA (08/2023 – 04/2024)  
  Supervisor: Prof. Bruno Sinopoli
  - Studied DQN, DDPG, and PPO and improved adaptation via self-supervised auxiliary tasks during deployment.
  - Validated on the DeepMind Control suite with improved generalization under visual modifications.

Internship and engineering experience
======
- **Hong Kong Center for Construction Robotics**, Hong Kong (06/2022 – 12/2022)  
  Start-up firm co-founder

- **Solar Panel Cleaning Robot System**, Hong Kong (02/2023 – 08/2023)  
  Supervisor: Prof. Ling Shi

- **Development of Network Communication System for Locomotion Robots**, Hong Kong (06/2021 – 08/2022)  
  Supervisors: Prof. Ling Shi, Prof. Man Wong
  
Skills
======
- Programming: C, C++, Python, MATLAB
- Software & Tools: PyTorch, OpenAI Gym, Simulink, Solidworks, Keil, 3D Printing
- Language: Mandarin (native), English

Publications
======
{% if site.publications and site.publications.size > 0 %}
<ul>{% for post in site.publications reversed %}
  {% include archive-single-cv.html %}
{% endfor %}</ul>
{% else %}
No publications listed yet.
{% endif %}
  
Talks
======
{% if site.talks and site.talks.size > 0 %}
<ul>{% for post in site.talks reversed %}
  {% include archive-single-talk-cv.html  %}
{% endfor %}</ul>
{% else %}
No talks listed yet.
{% endif %}
  
Teaching
======
{% if site.teaching and site.teaching.size > 0 %}
<ul>{% for post in site.teaching reversed %}
  {% include archive-single-cv.html %}
{% endfor %}</ul>
{% else %}
No teaching listed yet.
{% endif %}
  
Service and leadership
======
- WashU Electrical & Systems Engineering Student Advisory Board (2023 – 2025) — International Student Ambassador
- HKUST RoboMaster Robotics Competition Team (2020 – 2021) — R&D member
