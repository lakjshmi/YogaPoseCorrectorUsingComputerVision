


# Yoga Pose Corrector Using Computer Vision

This project uses computer vision techniques to develop a **Yoga Pose Corrector**, which provides real-time feedback to practitioners for improving their yoga postures. It aims to reduce the dependency on instructors and promote safe, effective yoga practices.

---

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Technology Stack](#technology-stack)
- [How It Works](#how-it-works)
- [Setup and Installation](#setup-and-installation)
- [Usage Instructions](#usage-instructions)
- [Results and Impact](#results-and-impact)
- [Scope for Future Work](#scope-for-future-work)
- [Contributors](#contributors)
- [How to Cite](##citation)

---

## Introduction

Yoga has proven physical and mental health benefits, but incorrect postures can lead to injuries or reduce the effectiveness of asanas. Traditional yoga classes often consist of large batches of students, limiting the instructor's ability to provide individual corrections. 

The Yoga Pose Corrector project addresses this issue by:
1. Leveraging **Mediapipe Pose Landmarker** to detect body landmarks.
2. Providing **real-time feedback** to correct poses.
3. Enhancing accessibility for practitioners without direct access to yoga instructors.

---

## Features

- **Real-Time Feedback**: Immediate suggestions for correcting postures.
- **Reference Images**: Display of asana images to guide users.
- **Minimal UI**: Easy-to-navigate interface with options to select poses and exit.
- **Text-to-Speech Guidance**: Feedback delivered via voice to ensure an interactive experience.
- **Multi-threading**: Optimized performance for smooth execution without lag.

---

## Technology Stack

- **Programming Language**: Python
- **Libraries Used**:
  - [Mediapipe](https://google.github.io/mediapipe/) for pose landmark detection
  - OpenCV for video processing
  - Pyttsx3 for text-to-speech
  - Tkinter for GUI

---

## How It Works

1. **Pose Detection**: Mediapipe identifies key body landmarks in real-time.
2. **Angle Calculation**: Angles between joints are calculated and compared with predefined reference angles for each pose.
3. **Feedback System**: 
   - If the angles are incorrect, corrective feedback is displayed and spoken.
   - A message is shown when the pose matches the reference.
4. **UI Integration**: A simple menu allows users to select poses and exit the application.
5. **Reference Display**: Reference images for poses are displayed alongside the camera feed.

---

## Setup and Installation

### Prerequisites
- Python 3.8+
- Webcam for live pose detection

### Installation Steps
1. Clone the repository:
   ```bash
   git clone https://github.com/your-repo/yoga-pose-corrector.git
   cd yoga-pose-corrector
   ```
2. Install required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the application:
   ```bash
   python yoga_pose_corrector.py
   ```

---

## Usage Instructions

1. Open the application.
2. Select a yoga pose from the dropdown menu.
3. Follow the on-screen and voice instructions to adjust your posture.
4. Press `q` to exit the camera feed or use the Quit button to close the application.

---

## Results and Impact

- Improved posture alignment for yoga practitioners.
- Enhanced instructor efficiency in large classes.
- Promoted safe and independent yoga practice.

### Sample Screenshots
- **Main Menu**: Select poses and start.
- **Feedback**: Real-time text and voice messages for corrections.
- **Success**: Notification when pose is accurate.

---

## Scope for Future Work

- **Dynamic Feedback**: Replace hardcoded angles with AI-driven suggestions.
- **Enhanced Testing**: Evaluate the app in real yoga class settings.
- **Offline Mode**: Optimize for usage in areas with poor internet connectivity.
- **Improved UI**: Develop a more accessible and visually appealing interface.
- **Data Security**: Implement protocols to ensure user privacy and data safety.

---

## Contributors

- **Lakshmi H Siddaveer** (1BM21MD019)
- **Seggu Harshavardhan** (1BM21MD032)
- **Varuni Gorkalkar** (1BM21MD042)

**Guides**:
- Internal: Dr. Beena Ullala Mata B N, B.M.S. College of Engineering
- External: Sharadha Shetty, Sampoorna Yoga

## Citation
Siddaveer, L., Gorkalkar, V., & Seggu, H. (2025). Yoga Pose Corrector with Computer Vision. Zenodo. https://doi.org/10.5281/zenodo.14752450


[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.14752450.svg)](https://doi.org/10.5281/zenodo.14752450)


---

### Acknowledgments
Special thanks to B.M.S. College of Engineering and Sampoorna Yoga for their support and guidance in making this project a success.


