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


### Visual Examples of the functionalities:
---


![image](https://github.com/user-attachments/assets/7bcb3088-160c-4081-bc9f-7b3b4e012a06)


![image](https://github.com/user-attachments/assets/7f9d9ada-3135-4530-a81e-5a92d74a4e8a)

![image](https://github.com/user-attachments/assets/a5bfd3aa-389e-4651-ba29-02ae2bd48ab9)





![image](https://github.com/user-attachments/assets/9cd6e5e3-b0c6-45ef-9292-612c4b134261)

![image](https://github.com/user-attachments/assets/31e0645d-a03f-4961-be7e-f448ac0de56f)


## Technologies
Python 3.x

YOLOv5 (Ultralytics, PyTorch-based)

OpenCV, Pillow

Pandas, NumPy

Matplotlib

Jupyter Notebooks
