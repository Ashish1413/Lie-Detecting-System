## Deception Detection using Facial Micro-Expressions 

This project is a machine learning and computer vision-based system designed to detect deception by analyzing **facial micro-expressions** from video data. It uses deep learning techniques to identify subtle, involuntary facial movements that may indicate lying or truth-telling.

## 🔍 Project Objective

The goal is to build an AI-powered tool that can assist in identifying deceptive behavior through facial analysis. The system processes facial features from video frames and applies classification models (such as CNN and SVM) to determine the likelihood of deception.

---

## 🚀 Features

- Facial detection and tracking using OpenCV
- GUI-based interaction for video input and analysis (`lie_GUI.py`)
- Pretrained model support for expression classification
- Micro-expression extraction and temporal feature analysis
- Real-time or batch video analysis support

---

## 🧠 Technologies Used

- Python
- OpenCV
- PyTorch
- scikit-learn (SVM)
- PyQt5 (for GUI)
- NumPy, PIL, etc.

---

## 🗂 Project Structure

Deception_detection/
│
├── lie_GUI.py # Main GUI script
├── detect_expression.py # Facial expression recognition logic
├── model/ # Contains trained model weights
├── utils/ # Utility scripts (e.g., preprocessing, feature extraction)
├── images/ # Sample images or icons for GUI
└── README.md


---

## ▶️ How to Run

1. Clone the repository:

git clone https://github.com/Ashish1413/Lie-Detecting-System.git

cd Lie-Detecting-System

2. Install the pre trained model below:

https://drive.google.com/drive/folders/1izJQF5bcbqNdDpYAdFvLCG0qJnHlicAg?usp=sharing

3. Install the required packages:

pip install -r requirements.txt

4. Run the GUI:

python lie_GUI.py

