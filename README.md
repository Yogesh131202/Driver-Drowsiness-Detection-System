Driver Drowsiness Detection System

This repository contains the implementation of a Driver Drowsiness Detection System. The system is designed to detect drowsiness in drivers based on eye closure and yawning detection using real-time video streams. It can alert the driver if drowsiness is detected, potentially preventing accidents caused by fatigue.

Features:
•	Real-time Eye Closure Detection: Monitors the driver’s eyes and detects prolonged eye     closure.
•	Yawning Detection: Detects yawning as a sign of drowsiness.
•	Audio Alert: Triggers an alert sound when drowsiness is detected.
•	Real-time Video Processing:  Uses a webcam to monitor the driver continuously.

Technologies Used :
•	Python
•	OpenCV
•	dlib
•	imutils
•	SciPy
•	NumPy

Prerequisites :
Before you begin, ensure you have met the following requirements:
•	Python 3.x installed on your machine.
•	The required Python libraries: `opencv-python`, `dlib`, `imutils`, `scipy`, and `numpy`.

You can install the necessary libraries using:
•	pip install -r requirements.txt

Installation :
•	Clone the repository:  git clone https://github.com/Yogesh131202/Driver-Drowsiness-Detection-System.git
•	Navigate to the project directory: cd Driver-Drowsiness-Detection-System
•	Install the dependencies: pip install -r requirements.txt

Usage :
Run the application: python drowsiness_detection.py
Using a Webcam: The system will automatically start capturing video from your webcam. It will analyze your eye movements to detect signs of drowsiness.
Audio Alert: If drowsiness is detected, an alert sound will be triggered to wake up the driver.

Project Structure :

Driver-Drowsiness-Detection-System/
│
├── drowsiness_detection.py   # Main script for running the detection system
├── shape_predictor_68_face_landmarks.dat   # Pre-trained facial landmark detector model
├── requirements.txt          # List of required Python packages
├── README.md                 # Project documentation

How It Works :
The system uses facial landmarks to monitor the driver’s eyes. It calculates the Eye Aspect Ratio (EAR) to determine whether the eyes are closed or if the driver is yawning. If the EAR remains below a certain threshold for a specific time, or if yawning is detected, the system triggers an alarm.

Contributions :
Contributions, issues, and feature requests are welcome! Feel free to check the issues page if you want to contribute.

Acknowledgments :
The project is inspired by the need to improve road safety by preventing accidents due to driver fatigue. Special thanks to the creators of the Python libraries used in this project.

Contact :
Yogesh Bhagat - GitHub - For any inquiries or support, please contact me via GitHub.
