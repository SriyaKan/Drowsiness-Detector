# Drowsiness-Detector

This project implements a drowsiness detection system using computer vision. The system aims to detect when a driver is drowsy and alert them to prevent accidents in real-time. Drowsiness detection is crucial for road safety, as drowsy driving can lead to severe accidents.

Installation
Clone the repository:

git clone https://github.com/yourusername/drowsiness-detection.git
cd drowsiness-detection

python3 -m venv venv
source venv/bin/activate   # On Windows: venv\Scripts\activate
Install the required dependencies:

pip install -r requirements.txt

Usage
Ensure your webcam is connected and working.

Run the drowsiness detection script:

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
