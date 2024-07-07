# Drowsiness-Detector

This project implements a drowsiness detection system using computer vision. The system aims to detect when a driver is drowsy and alert them to prevent accidents.

Table of Contents
Overview
Features
Requirements
Installation
Usage
Contributing
License
Acknowledgements
Overview
Drowsiness detection is crucial for road safety, as drowsy driving can lead to severe accidents. This project utilizes a combination of computer vision techniques and machine learning algorithms to monitor a driver's facial features and detect signs of drowsiness in real-time.

Features
Real-time monitoring of the driver's facial features
Detection of drowsiness based on eye aspect ratio and mouth aspect ratio
Alerts the driver through an alarm when drowsiness is detected
Requirements
Python 3.7+
OpenCV
dlib
imutils
scipy
Installation
Clone the repository:

sh
Copy code
git clone https://github.com/yourusername/drowsiness-detection.git
cd drowsiness-detection
Create and activate a virtual environment (optional but recommended):

sh
Copy code
python3 -m venv venv
source venv/bin/activate   # On Windows: venv\Scripts\activate
Install the required dependencies:

sh
Copy code
pip install -r requirements.txt
Usage
Ensure your webcam is connected and working.

Run the drowsiness detection script:

sh
Copy code
python drowsiness_detection.py
The system will start capturing video from the webcam and monitoring for drowsiness. If drowsiness is detected, an alarm will sound to alert the driver.

Contributing
Contributions are welcome! Please follow these steps to contribute:

Fork the repository
Create a new branch (git checkout -b feature-branch)
Make your changes and commit them (git commit -am 'Add new feature')
Push to the branch (git push origin feature-branch)
Create a new Pull Request
License
This project is licensed under the MIT License. See the LICENSE file for details.
