---
title: "GaussianFlow SLAM: Monocular Gaussian Splatting SLAM Guided by GaussianFlow"
authors:
  - "Dong-Uk Seo"
  - "Jinwoo Jeon"
  - "Eungchang Mason Lee"
  - "Hyun Myung†"
author_notes:
  - ""
  - ""
  - ""
  - "Advisor"
publication: "IEEE Robotics and Automation Letters (RA-L) 2026"
publication_types: ["1"]
date: 2026-04-20
url_pdf: "https://ieeexplore.ieee.org/abstract/document/11488276"
url_code: "https://gaussianflow-slam.github.io/"

image:
  placement: 3
  filename: "feature.png"
  caption: ""
  focal_point: "Center"

summary: "A monocular 3D Gaussian Splatting SLAM that uses optical flow as a geometry-aware cue: by aligning the projected motion of Gaussians (GaussianFlow) with optical flow, it regularizes both map reconstruction and pose estimation, with normalized error-based densification and pruning for higher rendering and tracking accuracy."
tags: ["Visual SLAM", "Monocular SLAM", "Gaussian Splatting", "Optical Flow"]
featured: true
reading_time: false
profile: false
show_date: false
---
We propose GaussianFlow SLAM, a monocular 3D Gaussian Splatting SLAM framework that leverages dense optical flow as a geometry-aware cue. By encouraging the projected motion of Gaussians, termed GaussianFlow, to align with optical flow, our method injects consistent structural supervision into both map reconstruction and camera pose estimation, even without depth measurements. We further introduce normalized error-based densification and pruning to refine inactive and unstable Gaussians, achieving superior rendering quality and tracking accuracy over state-of-the-art methods.
