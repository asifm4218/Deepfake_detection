# 🚀 Deepfake Detection System

![GitHub repo size](https://img.shields.io/github/repo-size/asifm4218/Deepfake_detection)
![GitHub stars](https://img.shields.io/github/stars/asifm4218/Deepfake_detection?style=social)
![GitHub forks](https://img.shields.io/github/forks/asifm4218/Deepfake_detection?style=social)
![GitHub issues](https://img.shields.io/github/issues/asifm4218/Deepfake_detection)
![GitHub license](https://img.shields.io/github/license/asifm4218/Deepfake_detection)

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python)
![TensorFlow](https://img.shields.io/badge/TensorFlow-orange?logo=tensorflow)
![OpenCV](https://img.shields.io/badge/OpenCV-green?logo=opencv)
![Pandas](https://img.shields.io/badge/Pandas-purple?logo=pandas)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-yellow?logo=scikit-learn)

![Deep Learning](https://img.shields.io/badge/AI-Deep%20Learning-red)
![Project Status](https://img.shields.io/badge/Status-Completed-brightgreen)
![Model Accuracy](https://img.shields.io/badge/Accuracy-85%25-success)

![Visitors](https://visitor-badge.laobi.icu/badge?page_id=asifm4218.Deepfake_detection)

> Detecting fake faces in a world full of digital illusions 🎭🚀 Deepfake Detection System

Detecting fake faces in a world full of digital illusions 🎭

👤 Author
Asif (GitHub: asifm4218)
🤝 Collaborator
Harsha
📌 Overview

Deepfakes are AI-generated manipulations where faces are swapped or altered to create highly realistic fake media. This project focuses on building a deep learning system that can detect whether a video is REAL or FAKE.

🎯 Objectives
Detect deepfake videos using AI models
Analyze facial inconsistencies frame-by-frame
Build a reliable classification system (REAL vs FAKE)
Explore integration into social media platforms for real-time warnings
⚠️ Why This Matters

Deepfakes can be used for:

Fake news & misinformation
Financial fraud
Political manipulation
Social media abuse

This project aims to act as a digital lie detector 🧠🔍

🧪 Demo

🎥 https://www.youtube.com/watch?v=wy8mVnBZ6pY

⚙️ Project Pipeline
Load dataset
Extract videos
Convert videos → frames
Detect faces
Extract facial landmarks
Analyze frame sequences
Classify as REAL / FAKE
🧠 Models Used
🔹 CNN Models
MesoNet – Good for images, weaker for video frames
ResNet50 – Trained on cropped deepfake images
EfficientNetB0 – Optimized feature extraction
🔹 CNN + RNN Models (🔥 Best Performance)
✅ InceptionV3 + GRU
Accuracy: ~82%
Combines spatial + temporal learning
✅ EfficientNetB2 + GRU
Accuracy: ~85%
Best performing model
⚠️ Limitations
Struggles with multiple faces in a frame
Performance drops in low-light/dark backgrounds
▶️ How to Run
pip install -r requirements.txt
python deploy/main.py

💡 Tip: Run on GPU for faster results

🛠️ Tech Stack
Python 🐍
TensorFlow
OpenCV
Pandas
Scikit-learn
🧾 Conclusion

This project demonstrates how combining CNN (feature extraction) and RNN (sequence learning) improves deepfake detection accuracy.

Final model achieved:
👉 ~85% accuracy on DFDC dataset

🌟 Future Improvements
Multi-face detection
Real-time browser plugin
API integration for social platforms
🙌 Acknowledgment

Special thanks to contributors and collaborators who supported this project.

⭐ Support

If you found this useful:
👉 Star the repo
👉 Fork it
👉 Build on it

🧠 Pro tip (important)

After updating README, run:

git add README.md
git commit -m "Updated README with credits and improved structure"
git push origin main