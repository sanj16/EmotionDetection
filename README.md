# Emotion Detection with OpenCV and Keras

# Overview
This project utilizes OpenCV and Keras to perform real-time emotion detection on faces in a video stream or file. The system uses a pre-trained deep learning model for emotion classification. Detected emotions include Angry, Disgusted, Fearful, Happy, Neutral, Sad, and Surprised.

# Dependencies
cv2: OpenCV library for computer vision tasks.
numpy: NumPy library for numerical operations.
Keras: Deep learning library for building and training models.

# Setup
Clone the repository:
git clone [https://github.com/sanj16/emotion-detection.git](https://github.com/sanj16/EmotionDetection)

Install dependencies:
pip install opencv-python numpy keras

Download the pre-trained model files:
emotion_model.json
emotion_model.h5

Run the script:
python emotion_detection.py

# Usage
The script can be configured to use either the default camera or a specified video file.
Press 'q' to exit the application.

# License
This project is licensed under the MIT License.
