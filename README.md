# Basketball Shot Detection & Tracking
A lightweight computer-vision system that automatically detects basketball shot attempts and makes using a single video input. Built using a custom-trained YOLOv8 model, trajectory interpolation, and a state-machine–based logic pipeline.

---

## Features
- Detects basketball and hoop in real time using YOLOv8  
- Tracks ball trajectory using polynomial interpolation  
- Displays live stats
- Visualizes bounding boxes, rim band, trajectory curve, and state  

---

## Project Structure
```
project/
├── data/
│   ├── videos/
│   └── Basketball-detection-for-COMPVISFINAL/
│
├── models/
│   └── yolov8n.pt
│
├── notebooks/
│   ├── 01_model_training.ipynb
│   └── ...
│
├── output/
│   └── Point_counting_results.mp4
│
└── README.md
```

---

## Getting Started

### **1. Clone the Repository**
```bash
git clone https://github.com/YourUsername/Basketball_Shots_Tracker.git](https://github.com/JMatthewK/Basketball_Shots_Tracker.git
cd Basketball_Shots_Tracker
```
### **2. Install Dependencies**
```bash
pip install -r requirements.txt
```
### **3. Run Notebooks with Videos**
