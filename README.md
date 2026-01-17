Object Detection Evaluation and Calibration with YOLOv8 (COCO Dataset)
📌 Overview

This project evaluates a pretrained YOLOv8 object detection model on the COCO 2017 validation dataset, with a focus on detailed performance diagnostics beyond standard accuracy metrics.
In addition to detection quality, the project analyzes error types and confidence calibration, providing deeper insight into model reliability.

🚀 Key Features

Evaluated pretrained YOLOv8 on the COCO 2017 validation split

IoU-based matching of predicted bounding boxes with ground-truth annotations

Standard detection metrics using COCO evaluation (mAP, IoU-based performance)

Error analysis using TIDE to categorize detection failures (localization, classification, duplicate, background, missed detections)

Confidence calibration analysis using Expected Calibration Error (ECE)

Scale-wise evaluation of performance and calibration for small, medium, and large objects

Quantitative analysis and visualization of error distributions and calibration behavior

🛠️ Tech Stack

Python, PyTorch

Ultralytics YOLOv8

COCO API, TIDE Toolbox

NumPy, Matplotlib

📊 Results

Identified dominant detection error modes using TIDE

Observed scale-dependent performance differences across object sizes

Measured calibration quality of YOLOv8 confidence scores using ECE

Demonstrated that confidence reliability varies across object scales
