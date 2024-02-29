# Plate Detection in Video


https://github.com/agung-madani/plate-detection/assets/121701309/e12b8b76-8a85-445b-89d3-62a80c8150c8


Plate Detection in Video is a project aimed at detecting and recognizing license plates in videos using computer vision techniques. This repository contains code to perform object detection, tracking, and license plate recognition in video streams.

## Overview

The project utilizes state-of-the-art deep learning models for object detection, particularly YOLO (You Only Look Once), to detect vehicles and license plates within each frame of a video. Additionally, the SORT (Simple Online and Realtime Tracking) algorithm is employed to track the detected vehicles across consecutive frames.

## Features

- Object Detection: Utilizes YOLO model to detect vehicles and license plates.
- Tracking: Implements the SORT algorithm for online object tracking.
- License Plate Recognition: Processes detected license plates to extract text using OCR (Optical Character Recognition).
- Visualization: Draws bounding boxes around detected vehicles and license plates, and overlays recognized license plate text on video frames.
- Output Generation: Generates a new video with annotated bounding boxes and recognized license plate text.

## Requirements

- Python 3.x
- OpenCV
- Ultralytics
- EasyOCR
- FilterPy

## Installation

Download the Repository and open in Google Colab

## Usage

1. Place your video file in the repository directory.
2. Update the paths to the video file in the code (if necessary).
3. Run main.ipynb
4. The processed video with detected vehicles and recognized license plates will be saved in the output directory.

