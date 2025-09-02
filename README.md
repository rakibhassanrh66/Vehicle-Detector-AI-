# 🚦 Vehicle-Detector-AI

[![Python](https://img.shields.io/badge/Python-3.9%2B-blue?logo=python&logoColor=white)](https://www.python.org/)  
[![YOLOv8](https://img.shields.io/badge/YOLOv8-Ultralytics-green?logo=ultralytics)](https://github.com/ultralytics/ultralytics)  
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

> **AI-powered vehicle detection with futuristic visualization and pathfinding algorithms!** 🚘✨

---

## 🎬 Demo

[▶️ Watch Demo Video](sample_videos/rst.mp4)
---

## ✨ Features
- 🚗 Detect vehicles in traffic videos using **YOLOv8**  
- 🔍 Analyze object relationships using **BFS, DFS, UCS algorithms**  
- 🌌 Futuristic neon-style bounding box visualization  
- 📹 Outputs annotated traffic video with paths overlayed  

---

## 📂 Setup Instructions

### 1. Clone Repository
```bash
git clone https://github.com/YOUR_USERNAME/Vehicle-Detector-AI.git
cd Vehicle-Detector-AI

2. Install Dependencies
pip install -r requirements.txt

3. Download YOLOv8 Weights
from ultralytics import YOLO
model = YOLO("yolov8m.pt")  # downloads automatically

4. Add Input Video

Place your video in the sample_videos/ folder and update main.py:

VIDEO_SOURCE = "sample_videos/T1.mp4"
VIDEO_OUT = "outputs/traffic_output.mp4"

5. Run
python main.py

📊 Output

✅ Annotated traffic video with detected vehicles

✅ BFS, DFS, UCS paths displayed on frames

✅ Neon/futuristic bounding box visualization


🔮 Future Improvements

Real-time detection with webcam feed 🎥

Lane and traffic light recognition 🛑

Integration with reinforcement learning for traffic optimization 🤖

📜 License

MIT License – free to use and modify

❤️ Acknowledgments

Ultralytics YOLOv8

OpenCV & NumPy libraries

ChatGpt

---
