# safety-percentage-prediction

This research-oriented project analyzes real-time vehicle footage to determine vehicle count, speed, model classification, and overall road safety percentage. It uses YOLOv8, Roboflow-trained models, and OpenCV-based tracking techniques. Ideal for smart traffic monitoring, accident prevention studies, and AI safety research.

---

## Features

- **Vehicle Detection** with YOLOv8
- **Speed Estimation** using pixel movement and time between frames
- **Vehicle Model Classification** using a Roboflow-trained object detection model
- **Pixel Distance Calculation** between vehicles
- **Traffic Density Assessment**
- Optional: **Pothole Detection**
- Optional: **Helmet Detection**
- **Safety Percentage Calculation** based on:
  - Vehicle speed
  - Distance from other vehicles
  - Traffic density
  - Detected potholes or helmet usage (optional)
- Works on pre-recorded video input
- Fully Colab-compatible


## Research Goal

This project is developed as part of a computer vision research initiative to:
- Predict vehicle behavior and safety levels in real-time
- Improve road safety metrics through automated analysis
- Integrate multi-model outputs (YOLOv8, Roboflow) into a single pipeline


## Tech Stack

- YOLOv8 (Ultralytics)
- Roboflow for custom object detection (vehicle model)
- OpenCV for tracking & speed estimation
- NumPy & PIL for processing
- Google Colab for deployment

