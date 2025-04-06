# 🛡️ Protex - Smart CCTV Dashboard with Real-Time Threat Detection

Protex is an AI-powered CCTV surveillance dashboard designed to detect potential threats in real time using computer vision techniques. It intelligently identifies dangerous scenarios such as weapons, fire, or suspicious behavior and provides a centralized dashboard for monitoring and alerting.

![Protex Preview](https://github.com/nagnitin/Protex/raw/main/preview.gif)

## 🚀 Features

- 🔍 **Real-Time Threat Detection** using YOLOv8  
- 🔫 **Weapon, Fire, and Anomaly Detection**  
- 📹 **Multiple Camera Feed Integration**  
- 🧠 **AI-Powered Object Detection**  
- 📊 **Interactive Dashboard Interface**  
- 🚨 **Alert System** (Visual & extendable to SMS/Email notifications)  
- 📦 **Modular and Scalable Architecture**

## 🧠 Tech Stack

- **Frontend:** Streamlit (Python)
- **Backend:** Python
- **Model:** YOLOv8 (Ultralytics)
- **Libraries:** OpenCV, NumPy, Pillow, Ultralytics

## 📂 Project Structure

Protex/ │ ├── weights/ # YOLOv8 model weights ├── utils/ # Utility scripts (e.g., preprocessing) ├── uploads/ # User-uploaded videos for testing ├── icons/ # Custom UI icons ├── sample_videos/ # Sample footage for testing ├── dashboard.py # Main Streamlit dashboard script ├── detection.py # Detection and processing logic ├── requirements.txt # Python dependencies └── README.md # Project documentation



## 🛠️ Installation

1. **Clone the Repository**

```bash
git clone https://github.com/nagnitin/Protex.git
cd Protex
pip install -r requirements.txt

