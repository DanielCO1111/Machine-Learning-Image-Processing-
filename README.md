# Infant Visual Recognition Analysis

## Image Processing & Machine Learning Pipeline with YOLO, Python, and Pandas


## Overview
This project analyzes infant visual recognition behavior from video data using a fully automated image processing and machine learning pipeline.
The pipeline combines video frame extraction, object detection with YOLOv5, feature engineering, and statistical comparison of experimental conditions (such as blurred vs. unblurred video). The codebase leverages Python, Pandas, NumPy, and OpenCV for robust, reproducible analysis.


## Main Components

### Frame Extraction:
Automated splitting of video files into frames for downstream analysis.

### Object Detection (YOLOv5):
Using YOLOv5 to identify and locate relevant features in each frame (such as faces or specific visual targets).

### Feature Engineering:
Extracting and aggregating key data points from detected objects (e.g., position, size, detection confidence).

### Statistical Analysis:
Using Pandas and NumPy to compare visual behavior across different experimental setups (e.g., blurred vs. unblurred videos), generating clear visualizations and CSV reports.

### Automation:
Scripts and notebooks for running the full pipeline in batch mode, supporting reproducibility for future experiments.

![image](https://github.com/user-attachments/assets/7bcb3088-160c-4081-bc9f-7b3b4e012a06)


![image](https://github.com/user-attachments/assets/3f6c5453-6028-4cf0-9576-1e1b17f8608b)


![image](https://github.com/user-attachments/assets/9cd6e5e3-b0c6-45ef-9292-612c4b134261)


## Technologies
Python 3.x

YOLOv5 (Ultralytics, PyTorch-based)

OpenCV, Pillow

Pandas, NumPy

Matplotlib

Jupyter Notebooks
