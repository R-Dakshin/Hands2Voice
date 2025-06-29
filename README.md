
# Sign Language Translator 

This project enables real-time **Text-to-Sign** and **Sign-to-Speech** conversion using deep learning and computer vision. Built with Flask, TensorFlow, and OpenCV.

##  Features

-  Live webcam-based Sign Detection
-  Text-to-Sign rendering with alphabet images
-  Speech output for recognized signs
-  Built-in MobileNetV2 model via TensorFlow Lite

No Flask or web server is required. Just open the HTML file or run the Python detection script.


---

## How to Use

### For Accessing the Main File
1. Open `main.html` in your browser
2. Choose the respective options, you want to do

###  For Text to Sign
1. Open `AmericanTranslator.html` in your browser
2. Type English text to see matching ASL alphabet signs

### For Sign to Speech
1. Run this script to use webcam detection:
```bash
python webcam_detect.py
```
2. Open `index.html` in your browser
3. Detected hand gestures will be translated into letters

---

##  Model Details
- Model: MobileNetV2 (TensorFlow Lite)
- Trained to recognize: A–Z, `space`, and `del`

---

## 👥 Contributors
- **Dakshin**
- **Deepak**
- **Akshita**
- **Sudhuksha**

---
