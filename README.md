# FaceMask-Detection
# Face Mask Detection System

A real-time face mask detection system using TensorFlow/Keras and OpenCV.

## Features
- Real-time mask detection using webcam
- Transfer learning with MobileNetV2
- Visual feedback with bounding boxes and confidence scores

## Installation
1. Clone this repository
2. Install dependencies: `pip install -r requirements.txt`
3. Download the Haar Cascade file (will be automatically handled by OpenCV)

## Usage
Run the Jupyter notebook or use the detection function directly:

```python
from detect_mask import detect_mask
detect_mask()
