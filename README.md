# Helmet Detection using YOLOv8

A beginner-friendly Computer Vision project demonstrating **Helmet / Hard-Hat Detection for Safety Monitoring** using YOLOv8.

## Project Overview

In industrial and construction environments, wearing a helmet or hard hat is an important safety requirement.

This project demonstrates how Computer Vision and object detection can be used to identify whether a helmet or hard hat is visible in an image.

The project uses a **pre-trained YOLOv8 hard-hat detection model** and focuses on applying the model rather than training a new model from scratch.

## Objectives

This project demonstrates:

* Loading a pre-trained YOLOv8 model
* Detecting helmets / hard hats in images
* Identifying helmet and no-helmet cases
* Displaying bounding boxes around detected objects
* Displaying class labels and confidence scores
* Testing the model using sample images or user-uploaded images
* Understanding how object detection can support industrial safety monitoring

## Detection Classes

The pre-trained model detects two classes:

* **Hardhat** — helmet / hard hat detected
* **NO-Hardhat** — helmet / hard hat not detected

## Technologies Used

* Python
* YOLOv8
* Ultralytics
* OpenCV
* Matplotlib
* Hugging Face Hub
* Google Colab

## Model

The project uses the pre-trained model:

`keremberke/yolov8n-hard-hat-detection`

The model weights are downloaded automatically from Hugging Face Hub.

## Project Workflow

1. Install the required libraries
2. Download the pre-trained hard-hat detection model
3. Load the model using YOLO
4. Select or upload a test image
5. Run object detection
6. Display bounding boxes, class labels and confidence scores
7. Save and display the detection result

## Notebook

The complete implementation is available in:

`helmet_detection_yolov8.ipynb`

The notebook contains explanatory text along with executable Python code, making it suitable for learning and demonstration.

## Applications

The concept can be extended to applications such as:

* Construction-site safety monitoring
* Industrial workplace safety
* PPE compliance monitoring
* Entry-gate safety checking
* Real-time camera-based monitoring

## Important Note

This project is an **educational demonstration** intended to explain the use of Computer Vision for helmet detection.

It is not a complete production-level safety or access-control system. A real-world deployment would require additional training, testing, validation and integration with appropriate hardware and safety systems.

