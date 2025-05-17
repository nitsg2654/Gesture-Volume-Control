# Gesture-Volume-Control
![Python](https://img.shields.io/badge/Python-3.9-blueviolet)

In this project, we explore how to use gesture control to adjust the volume of a computer using real-time hand tracking. By leveraging a pre-built hand tracking module, we detect hand landmarks and interpret specific gestures to control the system volume dynamically. This modular approach simplifies the process, allowing us to focus on implementing gesture-based interactions efficiently. The project showcases the practical application of computer vision and gesture recognition using Python.

![VolumeGestureControl](https://github.com/user-attachments/assets/788e2741-e6d9-4cb7-a4a0-53381151b604)


### Features: 
<ul>
  <li>Real-time hand tracking using webcam input.</li>
  <li>Detects distance between thumb and index finger to control volume.</li>
  <li>Smooth volume transition based on gesture distance.</li>
  <li>Visual feedback for gesture detection and volume level.</li>
  <li>Modular code with reusable hand tracking module.</li>
</ul>

### Requirements:

Make sure you have the following installed:
<ul>
  <li>Python 3.7+</li>
  <li>OpenCV (opencv-python)</li>  
  <li>MediaPipe (mediapipe)</li>
  <li>Pycaw (pycaw) – for Windows audio control</li>
  <li>NumPy</li>
</ul>

You can install the required libraries using pip:

    pip install opencv-python mediapipe pycaw numpy

### How to Run: 
Clone the repository:

    git clone https://github.com/nitsg2654/Gesture-Volume-Control.git
    cd Gesture-Volume-Control

Install all the libraries mentioned in the requirements.txt file with the command 

    pip install -r requirements.txt.

Run the script:

    python VolumeHandControl.py

Use Your Hand:
<ul>
  <li>Ensure your webcam is turned on.</li>
  <li>Show your hand in front of the webcam.</li>
  <li>Move your thumb and index finger closer or farther apart to decrease or increase the volume.</li>
</ul>

### Project Structure:

    gesture-volume-control/
    │
    ├── HandTrackingModule.py     # Reusable hand tracking utility
    ├── VolumeHandControl.py      # Main script to control volume using gestures
    └── README.md                 # Project documentation
