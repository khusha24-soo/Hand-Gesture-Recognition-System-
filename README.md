# Hand-Gesture-Recognition-System-


# Hand Gesture Recognition using Webcam

## Overview
This project implements a **real-time hand gesture recognition system** using a webcam. Unlike many demo projects that rely on prebuilt datasets, this system is trained on a **custom dataset created by me**, ensuring originality and adaptability to real-world conditions.  

The application detects and classifies hand gestures in live video streams, enabling gesture-based control of applications (e.g., play/pause media, navigate slides, adjust volume).

---

##  Features
- Real-time gesture detection via **OpenCV** and **TensorFlow/Keras**.  
- Custom dataset captured using webcam (self-prepared).  
- Supports multiple gesture classes (e.g.,  Palm,  Thumbs Up, peace).  
- Lightweight `.tflite` model for fast inference.  
- Modular codebase for easy extension (add new gestures).  

---

##  Tech Stack
- **Languages**: Python  
- **Libraries**: OpenCV, TensorFlow/Keras, NumPy, Mediapipe (optional)  
- **Environment**: PyCharm / VS Code  
- **Hardware**: Standard laptop webcam  

---

##  Project Structure
```
├── dataset/                # Custom dataset (captured via webcam)
│   ├── gesture_1/          # Images for Gesture 1
│   ├── gesture_2/          # Images for Gesture 2
│   └── ...
├── train.py                # Model training script
├── webcam_test.py          # Real-time gesture recognition
├── hand_gesture.tflite     # Trained model (exported)
├── requirements.txt        # Dependencies
└── README.md               # Project documentation
```

---

##  Installation & Setup
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/hand-gesture-recognition.git
   cd hand-gesture-recognition
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Train the model on your dataset:
   ```bash
   python train.py
   ```
4. Run real-time recognition:
   ```bash
   python webcam_test.py
   ```

---

##  Dataset
- Captured manually using webcam.  
- Each gesture class contains **500–1000 images** for reliable accuracy.  
- Preprocessed with resizing, normalization, and augmentation.  

---

## Applications
- Gesture-based media control  
- Virtual presentations (slide navigation)  
- Accessibility tools for touch-free interaction  
- IoT/Smart Home control systems  

---

##  Future Work
- Expand gesture classes.  
- Integrate with IoT devices for real-world control.  
- Improve accuracy with larger datasets and advanced architectures (CNN, MobileNet).  

---

