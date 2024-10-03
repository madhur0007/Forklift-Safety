## Introduction
This repository provides a solution for detecting safety violations around forklifts using the YOLOv8 object detection model. Forklift safety is critical in industrial environments, and this project aims to automate the detection of safety breaches such as improper worker proximity, missing safety gear, or incorrect forklift operation. YOLOv8 (You Only Look Once, version 8) is a state-of-the-art, real-time object detection model, perfectly suited for detecting safety violations in fast-paced environments.

## Features
Real-time detection of forklifts, workers, and safety hazards.
Configurable to detect various safety violations (e.g., missing helmets, workers too close to forklifts).
Supports both image and video input, as well as live webcam detection.
Easy to train with custom datasets.
Exports trained models for use in different environments.
Integration with popular frameworks such as PyTorch.

##Prerequisites
To use this repository, ensure you have the following installed:

Python 3.x: Python version 3.8 or higher.
PyTorch: Install the appropriate PyTorch version for your system and GPU.
YOLOv8: Install YOLOv8 from the ultralytics package.
OpenCV: Used for handling image and video processing.
Additional Libraries: NumPy, Matplotlib, etc.
