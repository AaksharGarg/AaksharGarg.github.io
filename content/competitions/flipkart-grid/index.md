---
title: "Flipkart GRID 5.0 — Robotics Manipulator Theme"
summary: "Finalist project involving a vision-guided 6-DOF robotic arm with perception-driven manipulation."
date: 2024-01-01
tags: ["Competition", "Robotics", "Manipulation", "Computer Vision"]

links:
  - title: YouTube
    url: https://youtube.com/YOUR_VIDEO_LINK
    icon: youtube
  - title: GitHub
    url: https://github.com/YOUR_REPO_LINK
    icon: github
---

## Overview
Finalist project in **Flipkart GRID 5.0 (Robotics Manipulator Theme)**, focused on designing
and developing a **6-DOF robotic arm** capable of perception-driven manipulation using
computer vision and 3D point cloud processing.

The objective was to detect payloads, segment graspable surfaces, and accurately compute
transforms for manipulation under real-world constraints.

## Key Contributions
- Designed and implemented a **6-DOF robotic arm** from scratch using Python and C++.
- Implemented **YOLOv8-based object detection and instance segmentation** to identify and
  isolate payload surfaces.
- Performed **surface extraction** using segmentation masks to remove irrelevant regions
  from point clouds.
- Generated **OctoMap representations** of the environment for spatial understanding.
- Computed precise **TF (transform) frames** for object localization and manipulation.
- Applied **clustering techniques** (DBSCAN, K-Means) for noise filtering and nearest-neighbor
  analysis in point cloud data.

## Technical Stack
- **Perception:** YOLOv8, OpenCV  
- **3D Processing:** Point Cloud Library (PCL), Open3D  
- **Robotics Middleware:** ROS, MoveIt  
- **Simulation & Visualization:** Gazebo, RViz  
- **Programming:** Python, C++  

## Outcome & Impact
- Achieved **Finalist position** among national-level teams.
- Reduced perception-to-action latency by ~60%.
- Improved payload surface detection accuracy by ~50%.
- Demonstrated a complete perception → planning → manipulation pipeline under
  competition constraints.

## Learnings
This project strengthened my understanding of:
- Vision-guided robotic manipulation
- 3D perception and spatial reasoning
- ROS-based system integration
- Designing robust pipelines under strict evaluation criteria
