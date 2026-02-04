# Monocular Visual Odometry (VO) using OpenCV

## Overview
This project implements Monocular Visual Odometry using OpenCV to estimate camera motion from a monocular video stream. The system extracts feature points, matches them across frames, estimates the Essential Matrix, and recovers camera pose.

## Technologies Used
- Python
- OpenCV
- NumPy
- Matplotlib
- Jupyter Notebook

## Pipeline
1. Frame extraction from video
2. Feature detection and matching (ORB)
3. Essential matrix estimation
4. Camera pose recovery
5. Motion visualization

## Results
The system successfully estimates relative camera motion between consecutive frames in urban driving scenarios.

## Limitations
- Scale ambiguity due to monocular setup
- Sensitive to motion blur and low texture

## Future Improvements
- Scale recovery using depth cues
- Integration with SLAM
- Robust outlier rejection

## Author
Debjit Ghosh

