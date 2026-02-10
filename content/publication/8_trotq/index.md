---
title: "TROT-Q: Traversability and Obstacle Aware Target Tracking System for Quadruped Robots"
authors:
  - "Eungchang Mason Lee"
  - "Jinwoo Jeon"
  - "Hyun Myung†"
author_notes:
  - ""
  - ""
  - "Advisor"
publication: "Asian Control Conference (ASCC) 2022"
publication_types: ["1"]
date: 2022-07-20
url_pdf: "https://ieeexplore.ieee.org/abstract/document/9828258"
url_code: ""

image:
  placement: 3
  filename: "feature.png"
  caption: ""
  focal_point: "Center"

summary: "A quadruped target-tracking system that jointly plans traversable, obstacle-free local trajectories using SLAM, RGB-D object detection, and QR-SCAN-style trajectory scoring, and tracks them with a hierarchical MPC+PD controller."
tags: ["Quadruped Robot", "Target Tracking"]
featured: false
reading_time: false
profile: false
show_date: false
---
We propose TROT-Q, a quadruped target-tracking framework that estimates robot state via LiDAR-inertial SLAM and target position via RGB-D object detection, selects a safe local trajectory by combining traversability/obstacle checks with target-proximity scoring, and tracks it using a hierarchical MPC+PD controller.
