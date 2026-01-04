# 🚀 YOLOv8 Object Detection Project

This repository demonstrates **object detection using YOLOv8** (You Only Look Once – Version 8) with the Ultralytics framework. The project includes Jupyter notebooks for performing object detection on images and real-time video streams such as traffic and junction scenes using a pretrained YOLOv8 model.
YOLOv8 is a state-of-the-art real-time object detection model known for its speed and accuracy. This project showcases how to use a pretrained YOLOv8 Nano model to detect common objects in images and live webcam feeds without training a custom model.
Technologies used in this project include Python, Ultralytics YOLOv8, OpenCV for image and video processing, Matplotlib for visualization, and Jupyter Notebook for experimentation and demonstration.

Project Structure:
Yolov8/
│
├── junction.jpg            # Sample input image
├── traffic.jpg             # Sample traffic image
├── result.jpg              # Output image with detections
├── yolo.ipynb              # YOLOv8 image detection notebook
├── live_video.ipynb        # Real-time webcam detection notebook
├── yolov8n.pt              # Pretrained YOLOv8 Nano model
└── README.md

Requirements:
- Python 3.x
- ultralytics
- opencv-python
- matplotlib
- notebook (for Jupyter)

Installation:
pip install ultralytics opencv-python matplotlib notebook

Usage:
To run image detection, open `yolo.ipynb` in Jupyter Notebook and execute the cells to perform object detection on sample images.  
For real-time detection, open `live_video.ipynb`, connect a webcam, and run the notebook cells to see live object detection.

Applications:
- Traffic and junction monitoring  
- Real-time object detection systems  
- Smart surveillance applications  
- Computer vision learning and experimentation  
- AI-based safety and automation projects  

Future Enhancements:
- Training YOLOv8 on custom datasets  
- Object tracking integration (DeepSORT / ByteTrack)  
- Video file and live stream processing  
- Exporting detection results to JSON or CSV  
- Web or mobile application integration  
- Performance optimization for edge devices  


