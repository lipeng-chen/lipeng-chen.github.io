---
title: "Gatekeeper: Online Safety Verification and Control for Nonlinear Systems in Dynamic Environments"
authors: "Devansh Agrawal, Ruichang Chen, Dimitra Panagou"
venue: "IEEE Transactions on Robotics"
year: 2024
volume: ""
number: ""
pages: "1-17"
doi: "10.1109/TRO.2024.3454415"
pdf: "gatekeeper2024.pdf"
abstract: "This paper presents the gatekeeper algorithm, a real-time and computationally-lightweight method that ensures that trajectories of a nonlinear system satisfy safety constraints despite sensing limitations. Gatekeeper integrates with existing path planners and feedback controllers by introducing an additional verification step to ensure that proposed trajectories can be executed safely, despite nonlinear dynamics subject to bounded disturbances, input constraints and partial knowledge of the environment. Our key contributions include: (A) an algorithm to recursively construct safe trajectories by numerical forward propagation, and (B) a proof that tracking such trajectories ensures system safety beyond the finite horizon. We demonstrate the method in simulations and physical experiments with quadrotors navigating dynamic obstacle environments."
bibtex: |
  @ARTICLE{10665919,
    author={Agrawal, Devansh Ramgopal and Chen, Ruichang and Panagou, Dimitra},
    journal={IEEE Transactions on Robotics}, 
    title={Gatekeeper: Online Safety Verification and Control for Nonlinear Systems in Dynamic Environments}, 
    year={2024},
    volume={},
    number={},
    pages={1-17},
    doi={10.1109/TRO.2024.3454415},
    keywords={Trajectory;Safety;Robots;Logic gates;Robot sensing systems;Nonlinear dynamical systems;Quadrotors;Collision Avoidance;Motion and Path Planning;Aerial Systems: Applications;Safety-Critical Control}
  }
tags:
  - Safety-Critical Control
  - Motion Planning
  - Quadrotors
  - Nonlinear Systems
  - Formal Verification
code: "https://github.com/agrawaldevansh/gatekeeper"
video: "https://youtube.com/watch?v=gatekeeper_demo"
award: "Best Paper Finalist, IROS 2023"
---