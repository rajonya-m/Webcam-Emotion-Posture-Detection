# Webcam-Emotion-Posture-Detection
This project utilizes a webcam to detect the user's emotion and posture in real-time. The project leverages the FER (Facial Expression Recognition) library for emotion detection and MediaPipe for posture detection based on facial landmarks.

Features
Real-time emotion detection using FER library.
Basic posture detection based on head and shoulder landmarks.
Webcam interface to display the video feed along with detected emotion and posture scores.
Default posture and emotion scores are displayed in the frame.
Requirements
Python 3.x
OpenCV
MediaPipe
FER (Facial Expression Recognition)
You can install the required libraries by running:

pip install opencv-python mediapipe fer


Setup Instructions
Clone the repository:

git clone https://github.com/your-username/emotion-posture-detection.git
cd emotion-posture-detection

Install the necessary dependencies:

pip install -r requirements.txt
Run the Python script:

python emotion_posture_detection.py

The webcam feed will open, and the real-time emotion and posture scores will be displayed on the frame.

Press q to quit the webcam feed.

Code Explanation

Emotion Detection
The project uses the FER library to detect emotions based on facial expressions. It processes the webcam feed to analyze emotions, which include:

Happy
Sad
Angry
Surprise
Fear
Disgust
Neutral
Posture Detection

MediaPipe is used to analyze the position of the face and its landmarks, including the head and shoulder areas, to calculate a basic posture score.

Real-Time Display
The detected emotion and posture scores are displayed in real-time overlaid on the video feed. The emotion is represented by a numerical value, and the posture score is set based on head tilt or other simple markers.

Project Structure
plaintext
Copy code
emotion-posture-detection/
├── emotion_posture_detection.py  
├── requirements.txt           
└── README.md                    

License
This project is licensed under the MIT License.
