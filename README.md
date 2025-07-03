# Real-Time Face Detection with OpenCV DNN

This project implements a real-time face detection system using OpenCV's DNN module with a webcam stream.  
It leverages a pre-trained Single Shot MultiBox Detector (SSD) with a ResNet-10 backbone, provided by the OpenCV team.   
The code is structured for readability and has been modified and extended beyond the original tutorial for clarity and personal learning.

---

## Features

- Real-time face detection from webcam feed
- SSD-based deep learning face detector using OpenCV DNN
- Confidence score and inference time overlay
- Frame flipping for natural camera preview
- Self-contained model loading and input checks

---

## Project Files

* **face_detection.ipynb**   
The main notebook containing the implementation of the face detection pipeline using OpenCV’s DNN module.
Performs live face detection with bounding boxes, confidence scores, and inference timing.

* **deploy.prototxt**   
Defines the layer structure and configuration of the deep learning model used for face detection.
Used together with the .caffemodel file to load the model in OpenCV.

* **res10_300x300_ssd_iter_140000_fp16.caffemodel**   
Contains the pre-trained weights for the SSD face detection model with a ResNet-10 backbone.
Compatible with OpenCV's cv2.dnn.readNetFromCaffe() function.

---

## Author

**Ishan Zadbuke**   
Developed as part of a computer vision learning project using OpenCV.

