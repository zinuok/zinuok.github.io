---
title: "AIM-SLAM: Dense Monocular SLAM via Adaptive and Informative Multi-View Keyframe Prioritization with Foundation Model"
authors:
  - "Jinwoo Jeon"
  - "Dong-Uk Seo"
  - "Eungchang Mason Lee"
  - "Hyun Myung†"
author_notes:
  - ""
  - ""
  - ""
  - "Advisor"
publication: "IEEE International Conference on Robotics and Automation (ICRA) 2026"
publication_types: ["1"]
date: 2026-03-05
url_pdf: "https://arxiv.org/abs/2603.05097"
url_code: "https://aimslam.github.io/"

image:
  placement: 3
  filename: "feature.png"
  caption: ""
  focal_point: "Center"

summary: "A dense monocular SLAM framework that adaptively prioritizes informative multi-view keyframes from a geometric foundation model (VGGT), combining voxel-overlap and information-gain-based selection (SIGMA) with a joint multi-view Sim(3) optimization for state-of-the-art pose estimation and dense reconstruction."
tags: ["Visual SLAM", "Monocular SLAM", "Dense Reconstruction", "Foundation Model"]
featured: true
reading_time: false
profile: false
show_date: false
---
We propose AIM-SLAM, a dense monocular SLAM framework that leverages dense pointmap predictions from a geometric foundation model (VGGT) and adaptively prioritizes informative multi-view keyframes. Our SIGMA module retrieves a candidate keyframe set via voxel overlap and information gain and adaptively determines its size, while a joint multi-view Sim(3) optimization enforces consistent alignment across the selected views, achieving state-of-the-art pose estimation and accurate dense reconstruction with ROS integration.
