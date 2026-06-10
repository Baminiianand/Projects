**Underwater Plastic Debris Detection using Edge AI**

## Project Overview
This project focuses on detecting underwater plastic waste using Artificial Intelligence and Computer Vision techniques. A YOLOv8 deep learning model is trained to identify plastic debris from images and live video streams in real-time.

The system uses ESP32-CAM for live video streaming and OpenCV for video frame processing. The detected plastic objects are highlighted using bounding boxes.


## Objectives
- Detect underwater plastic debris automatically
- Perform real-time object detection using YOLOv8
- Reduce manual monitoring effort
- Support environmental monitoring applications
- Integrate Edge AI using ESP32-CAM


## Technologies Used
- Python
- YOLOv8
- OpenCV
- Google Colab
- ESP32-CAM
- Arduino IDE



## Methodology
1. Collect underwater plastic image dataset
2. Annotate images using bounding boxes
3. Train YOLOv8 model in Google Colab
4. Use trained model (`best.pt`) for detection
5. Capture live video using webcam or ESP32-CAM
6. Detect plastic debris in real-time
7. Display bounding boxes around detected objects



## Features
- Real-time plastic detection
- Bounding box visualization
- Live camera streaming
- Edge AI integration
- Simple and low-cost implementation



## Output
The system detects underwater plastic waste and displays bounding boxes with confidence scores in real-time video frames.

