# Face Mask Detector

A deep learning-based computer vision project that detects whether a person is wearing a face mask in images or live video streams. Built using TensorFlow 1.15, Keras, and OpenCV.

---

## Features

- Real-time face mask detection using webcam or video feed
- Trained with convolutional neural networks (CNNs)
- Utilizes OpenCV for face detection and drawing bounding boxes
- Supports image and video input
- Lightweight, runs on most laptops

---

## Tech Stack

- **TensorFlow** 1.15.2
- **Keras** 2.3.1
- **OpenCV** 4.2.0
- **NumPy**, **Matplotlib**, **SciPy**
- **Imutils** for basic image processing utilities

---

## Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/Sapan-Byndla/Face-Mask-Detector.git
   cd Face-Mask-Detector

2. Install dependencies:
   ```
   pip install -r requirements.txt

How to Use

To run on a webcam feed:
 ```bash
python detect_mask_video.py
```

To run on a static image:
```bash
python detect_mask_image.py --image path/to/image.jpg
```

To test on video file:
```bash
python detect_mask_video.py --video path/to/video.mp4
```

Make sure the trained model (e.g., mask_detector.model) is present in the project folder.

Project Structure
Face-Mask-Detector/
├── detect_mask_video.py
├── detect_mask_image.py
├── mask_detector.model
├── dataset/                
├── requirements.txt
└── README.md

Dataset
The model was trained on a dataset of masked and unmasked faces collected from various open-source sources. You can replace or expand the dataset for improved accuracy.

Acknowledgements
OpenCV

TensorFlow

Keras

Inspired by the global need for COVID-19 safety tools
