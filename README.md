# Smart Agriculture Surveillance System

## Project Overview

The Smart Agriculture Surveillance System is an AI-powered project designed to improve farm security and monitoring. It combines Computer Vision, Object Detection, Face Recognition, and Alert Mechanisms to identify humans, animals, and vehicles in real time and generate appropriate notifications.

## Project Workflow

Camera
↓
OpenCV (Capture Frames)
↓
YOLO Object Detection
↓
Face Recognition
↓
Alerts and Notifications
↓
Logs and Reports

---

# Day 1 – Environment Setup and OpenCV Basics

## Objectives

* Set up the development environment.
* Install the required tools and libraries.
* Verify OpenCV functionality.

## Tasks Completed

* Created and activated a Python virtual environment.
* Installed Jupyter Notebook.
* Installed OpenCV (`opencv-python`).
* Verified OpenCV installation.
* Created and tested Jupyter notebooks.
* Performed basic image loading and display operations.
* Initialized the GitHub repository and pushed the initial project structure.

## Skills Learned

* Python virtual environments
* Package installation using pip
* Jupyter Notebook usage
* OpenCV basics
* Git and GitHub workflow

---

# Day 2 – OpenCV Fundamentals

## Objectives

* Learn image processing concepts using OpenCV.
* Understand how OpenCV interacts with images and videos.

## Tasks Completed

* Loaded and displayed images.
* Converted images between color spaces.
* Drew rectangles, circles, lines, and text on images.
* Accessed webcam input using OpenCV.
* Captured and displayed video frames.
* Learned how OpenCV processes visual information frame by frame.
* Uploaded completed tasks to GitHub.

## Skills Learned

* Image manipulation
* Video processing
* Webcam integration
* Drawing functions in OpenCV
* Real-time frame handling

---

# Day 3 – YOLO Object Detection Fundamentals

## Objectives

* Understand the fundamentals of object detection.
* Implement YOLO for detecting objects in images and videos.

## Concepts Learned

* What is Object Detection?
* What is YOLO (You Only Look Once)?
* Difference between Classification and Object Detection
* Bounding Boxes
* Confidence Scores
* Object Classes

## Tasks Completed

* Installed the Ultralytics YOLO package.
* Verified the installation.
* Created `yolo_basics.ipynb`.
* Loaded the pre-trained YOLOv8 Nano model (`yolov8n.pt`).
* Performed object detection on images.
* Observed bounding boxes, labels, and confidence scores.
* Detected objects such as vehicles successfully.
* Understood YOLO output results.
* Uploaded notebooks and outputs to GitHub.

## Skills Learned

* Real-time object detection
* Working with pre-trained models
* YOLOv8 implementation
* Understanding detection outputs
* Integrating AI models into applications

---

# Technologies Used

* Python
* Jupyter Notebook
* OpenCV
* Ultralytics YOLOv8
* Git
* GitHub

---

# Repository Structure

smart_agri_surveillance/

* datasets/
* logs/
* models/
* notebooks/
* outputs/
* screenshots/
* src/
* venv/
* README.md

---

# Future Scope

The upcoming stages of this project include:

* Face Recognition for identifying authorized individuals.
* Alert generation for suspicious activities.
* Logging and reporting of surveillance events.
* Integration of all modules into a complete smart agriculture surveillance solution.

---

# Conclusion

During the first three days of this project, I gained hands-on experience in setting up a computer vision development environment, working with OpenCV for image and video processing, and implementing YOLO for real-time object detection. These foundational skills will support the development of an intelligent agriculture surveillance system capable of monitoring and protecting agricultural environments effectively.
