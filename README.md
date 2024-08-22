# 🌀 Doctor Strange Magic Shield Project

Create your own real-time magic shield effect inspired by Doctor Strange using Python, OpenCV, and MediaPipe. Watch the shield appear and rotate based on your hand gestures!

## 📋 Table of Contents

- [✨ Features](#-features)
- [🔧 Prerequisites](#-prerequisites)
- [⚙️ Installation](#️-installation)
- [🚀 Usage](#-usage)
- [🎨 Customization](#-customization)
- [🤝 Contributing](#-contributing)

## ✨ Features

- 🖐️ Real-time hand detection using MediaPipe.
- 📏 Calculation of hand landmarks to detect specific gestures.
- 🛡️ Display of a rotating magic shield when the gesture is recognized.
- ⚙️ Adjustable shield size and rotation speed for personalized effects.

## 🔧 Prerequisites

Make sure you have the following installed:

- 🐍 Python 3.x
- 📷 OpenCV
- 🖐️ MediaPipe

Install the required packages using pip:

```bash
pip install opencv-python mediapipe
```

## ⚙️ Installation

1. Clone this repository to your local machine:

    ```bash
    git clone https://github.com/your-username/doctor-strange-magic-shield.git
    cd doctor-strange-magic-shield
    ```

2. Place the shield images (`1.png` and `2.png`) in the project directory.

3. Run the main script:

    ```bash
    python main.py
    ```

## 🚀 Usage

- 🖥️ Run the script, and it will activate your webcam.
- ✋ Perform a hand gesture with your palm facing the camera.
- 🔍 The script detects the hand and calculates the ratio of distances between key landmarks.
- 🛡️ When the ratio meets specific criteria, a magic shield will appear and rotate around your hand.

### Exiting

- ❌ To stop the script, press `q` on your keyboard.

## 🎨 Customization

You can adjust various parameters in the code:

- **🛡️ Shield Size:** Modify the `shield_size` variable to change the size of the shield.
- **💫 Rotation Speed:** Change the `ang_vel` variable to increase or decrease the rotation speed.
- **🎯 Gesture Sensitivity:** Adjust the ratio thresholds in the if-statements to fine-tune when the shield appears.

## 🤝 Contributing

Want to make this project even more magical? Fork the repository and submit a pull request!
