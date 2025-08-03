# Software Navigation Assistant

A real-time object detection and depth estimation assistant using **YOLOv11x** and **MiDaS**, designed with an interactive **Streamlit** interface. This assistant helps users identify objects in their environment along with their distance, and audibly announces them — making it useful for smart navigation and assistive technologies.

---
## 🚀 Features

- 🔍 Real-time object detection using YOLOv11x
- 📏 Depth estimation via MiDaS
- 🔊 Audio feedback for closest objects (via gTTS & pygame)
- 📷 Webcam integration with Streamlit-based GUI
- 🎯 Interactive circular start/stop detection buttons
  
---
## 📁 Folder Structure

├── main.py # Main Streamlit application
├── requirements.txt # Python dependencies
├── README.md 
├── coco.names # COCO class labels
└── models
     └── yolo11x.pt # Download separately
---

## 💻 Installation
### 1. Clone the repository

git clone https://github.com/Gayu-07/software-navigation-assistant.git
cd software-navigation-assistant

### 2. Install Python dependencies
pip install -r requirements.txt

---
### ▶️ Usage

streamlit run main.py

Click Start Detection to begin

Click Stop Detection to halt processing

The app will detect objects, estimate their distance, and announce the closest one every 5 seconds

---
### 🔧 Technologies Used
Python
Streamlit
OpenCV
PyTorch
gTTS (Google Text-to-Speech)
Pygame
Ultralytics YOLOv11x
MiDaS for depth estimation
