# Object-Prediction
# 🛰️ Object Detection from Satellite Imagery

This project is a web-based AI application that uses the **YOLOv8** deep learning model to automatically detect multiple objects—such as bridges, windmills, ships, and vehicles—from high-resolution satellite images.

---

## 📌 Project Objective

To automate the analysis of satellite imagery using deep learning and provide users with real-time object detection and visualization via a simple web interface.

---

## 🧠 Key Features

- Upload satellite images via browser
- Detect 20+ object categories using YOLOv8
- View annotated image with bounding boxes and labels
- Download detection results for offline use
- Simple and responsive frontend interface

---

## ⚙️ Tech Stack

| Layer        | Technology                        |
|--------------|------------------------------------|
| **Frontend** | HTML, CSS, JavaScript, Tailwind CSS |
| **Backend**  | Python, Flask, OpenCV, Matplotlib  |
| **Model**    | YOLOv8 (Ultralytics)               |
| **Dataset**  | DIOR Dataset                       |
| **Tools**    | Google Colab, VS Code              |
| **Database** | SQLite3 *(optional for logging)*   |

---

## 🚀 Setup Instructions

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/satellite-object-detection.git
   cd satellite-object-detection










**Create a virtual environment and install dependencies**


   python -m venv venv
source venv/bin/activate  # Windows: venv\Scripts\activate

**Download the YOLOv8 model**
pip install -r requirements.txt


**Run the Flask server**
python app.py



## 🖼️ Supported Object Classes
Airplane

Airport

Bridge

Dam

Harbor

Windmill

Ship

Vehicle

Expressway

Toll Station

Basketball Court

Tennis Court

Baseball Field

Stadium

Golf Field

Train Station

Overpass

Chimney

Storage Tank

Ground Track Field




