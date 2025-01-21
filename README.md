# VeggyTally-Tomato-Sorting-and-Detection-System

VeggyTally is a machine learning-powered solution designed to sort tomatoes based on their ripeness and detect defects. This project leverages the YOLO (You Only Look Once) object detection model for precise classification and integrates with a user-friendly Streamlit app for real-time deployment.

## Features
- Real-time tomato detection using webcam feed
- Classification into three categories (ripe, unripe, defective)
- Adjustable confidence threshold
- Live count tracking
- Color-coded bounding boxes
- Cumulative counting over 10-second intervals

## Prerequisites
- Python 3.8 or higher
- CUDA-capable GPU (recommended)
- Webcam

## Installation
# Clone repository
git clone https://github.com/Omadithya07/VeggyTally-Tomato-Sorting-and-Detection-System.git
cd VeggyTally

# Install requirements
pip install ultralytics
pip install streamlit
pip install opencv-python
pip install numpy

## Project Structure
VeggyTally/
│
├── custom.ipynb           # Model training notebook
├── app.py                # Streamlit deployment application
├── best_custom.pt        # Trained YOLO model weights
└── README.md

  
