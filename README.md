# Traffic Density Estimation System 🚗📊

[![CI Build](https://github.com/agmukesh/Traffic-Density-Estimation/actions/workflows/ci.yml/badge.svg)](https://github.com/agmukesh/Traffic-Density-Estimation/actions)

## 📌 Overview
This project implements a real-time traffic density estimation system utilising YOLOv8 and deep learning techniques. It leverages computer vision to detect and count vehicles in video streams, enabling smarter traffic control and congestion reduction.

---

## 💡 Features
- Real-time object detection using YOLOv8
- Traffic density estimation from video input
- Annotated video output with bounding boxes and vehicle counts
- Scalable logging and database-ready design
- Easily extendable to smart traffic light control

---

## 📦 Tech Stack

| Tool / Library       | Version       |
|----------------------|---------------|
| Python               | 3.9+          |
| YOLOv8 (Ultralytics) | 8.0.203       |
| OpenCV               | 4.9.0.80      |
| PyTorch              | 2.2.2         |
| Jupyter Notebook     | Latest        |

---

## 📁 Project Structure
├── traffic-density-estimation-with-yolov8.ipynb # Main notebook
├── processed_sample_video.mp4 # Output sample
├── yolov8n.pt # YOLOv8 model weights
├── data.yaml # Dataset configuration
├── Vehicle_Detection_Image_Dataset/ # Custom image/video dataset
├── requirements.txt # Python dependencies
├── .github/
│ └── workflows/
│ └── ci.yml # GitHub Actions CI pipeline

## ⚙️ Environment Setup

### Installation

```bash
git clone https://github.com/agmukesh/Traffic-Density-Estimation.git
cd Traffic-Density-Estimation
pip install -r requirements.txt

✅ Requirements (requirements.txt)
ultralytics==8.0.203
opencv-python==4.9.0.80
numpy==1.26.4
matplotlib==3.8.4
pandas==2.2.2
seaborn==0.13.2
PyYAML==6.0.1
torch==2.2.2

🚀 How to Run
Launch the Jupyter Notebook:

Open and run traffic-density-estimation-with-yolov8.ipynb.

Processed output (with vehicle bounding boxes and counts) is saved to processed_sample_video.mp4.

🎯 Results
Real-time vehicle detection using YOLOv8

Density metrics visualised on processed video

System is ready for smart city and edge deployment extensions

🔄 Future Enhancements
Multi-camera support

Real-time dashboard using Streamlit or Dash

Edge device deployment (Jetson Nano, Raspberry Pi)

Integration with smart traffic control systems

📄 License
This project is for academic and research use only.
