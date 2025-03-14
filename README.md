
# Fire Detection System

- 👋 Welcome to the Fire Detection System project by @Bilalboubeka  
- 👀 This project uses YOLOv5 and OpenCV to detect fire in real-time video streams from a webcam.  
- 🌱 Built with embedded systems and AI in mind, this is a lightweight solution for fire detection.  

## Overview
This project implements a real-time fire detection system using a pre-trained YOLOv5 model. It captures video from a webcam, processes frames to detect fire, and draws bounding boxes around detected regions with labels.

## Features
- Real-time fire detection using YOLOv5
- Displays bounding boxes and labels on detected fire regions
- Supports CUDA-enabled GPUs for faster processing

## Prerequisites
- Python 3.7+
- PyTorch (`torch`)
- OpenCV (`cv2`)
- A webcam
- The pre-trained model file (`best.pt`)

## Installation
1. **Clone the Repository**  
   ```bash
   git clone https://github.com/Bilalboubeka/fire-detection-system.git
   cd fire-detection-system
