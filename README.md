# Gesture Volume Control Project
## 📌 Project Overview
This project demonstrates a hand gesture-based volume control system using computer vision and mediapipe. The system detects hand landmarks and uses the distance between the thumb and index finger to adjust the volume of your computer in real-time.

## ✨ Features
- Real-time hand tracking via webcam

- Accurate gesture recognition using MediaPipe Hands

- System volume control based on finger distance

- Visual feedback with OpenCV drawing utilities

- Clean, modular Python code

## 📋 Requirements
Python 3.7+

OpenCV

MediaPipe

Pycaw (for controlling system audio on Windows)

NumPy

## 🛠 Installation
1. Clone this repository:
```bash
git clone https://github.com/EK-RON/HandTracking.git
cd HandTracking
```

2. Install the required packages:
```bash
pip install -r requirements.txt
```

3. Run the main script:
```bash
python VolumeHandControl.py
```

How to Use:
- Show your hand to the camera

- Make a pinch gesture with your thumb and index finger

- Move your fingers apart to increase volume

- Move your fingers closer to decrease volume

<img width="631" height="464" alt="hand2" src="https://github.com/user-attachments/assets/e07ea9f9-2e62-4dc9-8552-15171c662525" />

<img width="631" height="464" alt="hand1" src="https://github.com/user-attachments/assets/23a2b275-de06-4810-b49e-dfbcd160a966" />

## 📂 Project Structure
<pre>
HandTracking/

├── VolumeHandControl.py      # Main application script 

├── HandTrackingModule.py     # Helper functions

├── requirements.txt          # Dependency list

└── README.md                 # This file
</pre>
## 🤝 Contributing
Contributions are welcome! Please open an issue or submit a pull request for any improvements.

## 📜 License
This project is licensed under the MIT License - see the LICENSE file for details.
