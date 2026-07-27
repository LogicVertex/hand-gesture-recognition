🖐️ Gesture-Based Volume Control System
A real-time touchless volume control system built using Python, OpenCV, and MediaPipe.

![Python](https://img.shields.io/badge/Python-3.10-blue) ![OpenCV](https://img.shields.io/badge/OpenCV-4.x-green) ![MediaPipe](https://img.shields.io/badge/MediaPipe-Latest-orange)

## 📑 Table of Contents

- [Objectives](#-objectives)
- [Features](#-features)
- [Requirements](#-requirements)
- [Technologies Used](#-technologies-used)
- [Project Structure](#-project-structure)
- [Demo](#-demo)
- [Installation](#️-installation)
- [Working](#-working)
- [Future Scope](#-future-scope)
- [Author](#-author)
  
## 📂 Project Structure

gesture-volume-control/
│
├── screenshots/
├── volume_control.py
├── hand_landmarker.task
├── requirements.txt
└── README.md
  
## 📌 Objectives

- Detect hands in real time using a webcam.
- Track hand landmarks using MediaPipe.
- Control system volume through hand gestures.
- Demonstrate computer vision for touchless interaction.

## 🚀 Features
- Real-time hand detection using MediaPipe
- Hand landmark tracking
- Gesture-based volume control
- Dynamic volume adjustment
- Live webcam integration
- Smooth and responsive user interaction

## 💻 Requirements
- Python 3.10 or above
- Windows Operating System (Pycaw is Windows-specific)
- Webcam
  
## 🛠 Technologies Used
- Python 3.x
- OpenCV
- MediaPipe
- NumPy
- Pycaw (System Volume Control)
- comtypes

## 📸 Demo

### Hand Detection & Volume Control

![Hand Detection ](screenshots/output1.png)

## ⚙️ Installation
### Clone the Repository

```bash
git clone https://github.com/LogicVertex/hand-gesture-recognition.git
```

### Navigate to the Project Folder

```bash
cd hand-gesture-recognition
```
### Install Required Libraries

```bash
pip install opencv-python mediapipe numpy pycaw comtypes
```

### Download MediaPipe Model

```bash
curl -o hand_landmarker.task https://storage.googleapis.com/mediapipe-models/hand_landmarker/hand_landmarker/float16/1/hand_landmarker.task
```

Alternatively, download the file manually and place it in the project folder.
 
### Run the Application

```bash
python volume_control.py
```

## 🔄 Working

1. Webcam captures live video.
2. MediaPipe detects hand landmarks.
3. Distance between thumb and index finger is calculated.
4. The distance is mapped to the system volume.
5. Volume changes instantly based on the hand gesture.
   
## 🔮 Future Scope

- Gesture-based media player controls
- Virtual mouse implementation
- Brightness control using hand gestures
- Sign language recognition
- Contactless presentation controller

## 👨‍💻 Author

**LogicVertex**

AI • Machine Learning • Computer Vision • Big Data

---

⭐ If you found this project interesting, consider giving it a star.

Made with ❤️ using Python, OpenCV and MediaPipe.
