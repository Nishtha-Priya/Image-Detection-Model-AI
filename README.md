# Indian Sign Language Detection Model AI (Real-Time)
A real-time hand sign detection system that uses a live webcam feed to recognize
Indian Sign Language (ISL) gestures using machine learning and computer vision. <br>
This repository contains a real-time computer vision system that detects Indian Sign Language
hand gestures from a live webcam feed. The model is trained using a curated dataset,
and is integrated into a webcam application for real-time inference.
## Dataset
- Indian Sign Language Dataset (Kaggle)  
- https://www.kaggle.com/datasets/soumyakushwaha/indian-sign-language-dataset  

Dataset is not included due to size and licensing constraints.

## Features
- Real-time hand gesture recognition
- Live webcam input processing
- Preprocessed and trained on labeled ISL data
- End-to-end integration with Python and OpenCV

## How It Works
- Train ML models on ISL hand sign data
- Integrate the trained model with a live camera feed
- Perform real-time gesture detection

## Quick Setup
1. Clone the repository:
```bash
git clone https://github.com/Nishtha-Priya/Indian-Sign-Language-Detection-Model-AI.git
cd Indian-Sign-Language-Detection-Model-AI
```
2. Install dependencies:
```bash
pip install -r requirements.txt
```
4. Download dataset from Kaggle
5. Open Jupyter Notebook:<br>
Run:

`Models used.ipynb` to train/experiment <br>
`Real Time Detection.ipynb` for live webcam detection

## Files
- Models used.ipynb-> Model experiments <br>
- Real Time Detection.ipynb-> Live webcam detection <br>
- app.ipynb-> Application workflow <br>

## Limitations
- Low real-time accuracy
- Sensitive to lighting and background conditions
- Limited dataset and tuning

## Future Improvements
- Increase dataset size
- Try deeper CNN architectures
- Add data augmentation
- Improve preprocessing and segmentation

## Tech Stack
Python, OpenCV, Machine Learning, Computer Vision

## Requirements
- Python 3.x
- OpenCV
- TensorFlow / Keras
- NumPy
- Jupyter Notebook<br>
```bash
pip install opencv-python numpy tensorflow
```

## Teammate
- Aisha Aijaz-(https://github.com/aishaaijaz)
