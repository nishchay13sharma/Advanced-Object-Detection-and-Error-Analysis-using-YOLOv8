# Object Detection and Model Evaluation with YOLOv8 (COCO Dataset)

## 📌 Overview
This project implements an advanced **object detection pipeline** using **YOLOv8** pretrained on the **COCO 2017 dataset**.  
Beyond detection, the project focuses on **model evaluation, calibration, and error analysis** using modern benchmarking tools.  

## 🚀 Key Features
- Trained & evaluated YOLOv8 on **COCO 2017 validation split**  
- **mAP, Precision, Recall, IoU** metrics computation  
- **Error analysis** with TIDE toolbox (localization, classification, duplicate errors)  
- **Confidence calibration** using Expected Calibration Error (ECE) across object scales  
- Automated results logging and visualization  

## 🛠️ Tech Stack
- Python, PyTorch  
- Ultralytics YOLOv8  
- COCO API, TIDE Toolbox  
- NumPy, Matplotlib  

## 📊 Results
- Detailed evaluation across small, medium, and large objects  
- Error classification to identify model weaknesses  
- Calibration statistics showing prediction confidence quality  

---

# Image Stitching and Panorama Creation using SIFT & Homography

## 📌 Overview
This project builds an **image stitching pipeline** that takes unorganized sets of images, clusters them into groups, and generates seamless panoramas.  
It leverages classical **computer vision techniques** such as SIFT, feature matching, homography estimation, and blending.

## 🚀 Key Features
- **Keypoint extraction** using SIFT  
- **Feature matching** with BruteForce and FLANN-based matchers  
- **Homography estimation** with RANSAC  
- **Perspective warping and blending** for seamless panoramas  
- **Clustering (K-Means, BoVW)** to separate unorganized images into panorama groups  

## 🛠️ Tech Stack
- Python, OpenCV  
- NumPy, Scikit-learn  
- Matplotlib  

## 📊 Results
- Generated 3 complete panoramas from mixed datasets  
- Visualized keypoints, matches, and homographies  
- Compared matching algorithms (BruteForce vs FLANN)  
