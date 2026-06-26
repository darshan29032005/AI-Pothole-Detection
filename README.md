# 🚧 AI-Based Pothole Detection and Severity Estimation using YOLOv5

## 📌 Overview

This project is an AI-powered Computer Vision application developed using **YOLOv5**, **Python**, **PyTorch**, and **OpenCV** to detect potholes from road videos.

The system identifies potholes and estimates their severity (Low, Medium, or High) based on the detected bounding box size.

This project aims to support smart road maintenance by assisting authorities in identifying damaged roads efficiently.

---

## ✨ Features

* Detects potholes in videos using a custom-trained YOLOv5 model
* Classifies pothole severity into:

  * 🟢 Low
  * 🟡 Medium
  * 🔴 High
* Supports custom video input
* Displays bounding boxes around detected potholes
* Works with custom-trained weights
* Built entirely in Python

---

## 🛠 Tech Stack

* Python
* YOLOv5
* PyTorch
* OpenCV
* Git
* GitHub

---

## 📂 Project Structure

AI-Pothole-Detection/

├── detect.py

├── train.py

├── requirements.txt

├── weights/

│ └── best.pt

└── README.md

---

## ⚙️ Installation

Clone the repository:

```bash
git clone https://github.com/darshan29032005/AI-Pothole-Detection.git
cd AI-Pothole-Detection
```

Install dependencies:

```bash
pip install -r requirements.txt
```

---

## ▶️ Run Detection

```bash
python detect.py --weights weights/best.pt --source road.mp4
```

Replace **road.mp4** with your own input video.

---

## 📊 Severity Classification

The severity estimation is based on the detected pothole bounding box area.

| Area   | Severity |
| ------ | -------- |
| Small  | Low      |
| Medium | Medium   |
| Large  | High     |

---

## 📸 Sample Output

(Add screenshots of your detection results here)

---

## 🚀 Future Improvements

* Real-time webcam detection
* Raspberry Pi deployment
* GPS integration
* Road damage analytics dashboard
* Web application using Flask
* Depth estimation using AI

---

## 👨‍💻 Author

**Darshan Kumar P D**

B.Tech Robotics Engineering Student

Interested in Artificial Intelligence, Robotics, Computer Vision, and Web Development.

GitHub:
https://github.com/darshan29032005

---

## ⭐ Support

If you found this project helpful, consider giving it a ⭐ on GitHub.
