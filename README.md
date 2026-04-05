# 🤟 ASL Recognition

A **Machine Learning** project that recognizes **American Sign Language (ASL)** hand gestures in real-time using Python and Computer Vision.

---

## About

ASL (American Sign Language) is a complete, natural language used by the deaf and hard-of-hearing community. This project uses a trained ML model and computer vision to detect and recognize ASL hand gestures from a live webcam feed or image input.

---

## ✨ Features

- Real-time hand gesture detection via webcam
- Recognizes ASL alphabet gestures (A–Z)
- Machine Learning model for accurate predictions
- Works with both live camera and static images
- Displays prediction confidence score
- Fast and lightweight inference

---

## 🛠️ Tech Stack

| Technology | Usage |
|------------|-------|
| Python | Core programming language |
| OpenCV | Image processing and webcam capture |
| MediaPipe / TensorFlow | Hand landmark detection / ML model |
| NumPy | Numerical operations |
| Matplotlib | Visualization |

---

## 📁 Project Structure

```
ASL_recognition/
│
├── model/               # Trained ML model files
├── dataset/             # Training images/data
├── test/                # Test images
│   └── space_test.jpg
├── train.py             # Model training script
├── predict.py           # Run predictions
├── main.py              # Main application
└── requirements.txt     # Dependencies
```

---

## 🚀 How to Run

1. Clone the repository
```bash
git clone https://github.com/Chetna3110/ASL_recognition.git
cd ASL_recognition
```

2. Install dependencies
```bash
pip install -r requirements.txt
```

3. Run the application
```bash
python main.py
```

4. Show your hand to the webcam and it will recognize your ASL gesture!

---

## How It Works

```
Webcam Input
     ↓
Hand Detection (OpenCV / MediaPipe)
     ↓
Extract Hand Landmarks / Region of Interest
     ↓
Feed into ML Model
     ↓
Predict ASL Gesture (A-Z)
     ↓
Display Result on Screen
```

---

## Requirements

```
opencv-python
numpy
mediapipe
tensorflow
matplotlib
```

Install all with:
```bash
pip install -r requirements.txt
```

---

## Author

**Chetna Bharti** — [@Chetna3110](https://github.com/Chetna3110)

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).
