Project Overview
Emotion-Lens is a deep learning-powered system for real-time emotion detection through facial expressions. Utilizing OpenCV and a Convolutional Neural Network (CNN), the project captures facial features from webcam input and classifies emotions into categories like happy, sad, angry, surprised, and more. It's an ideal foundation for emotion-aware applications in mental health, e-learning, user experience, and human-computer interaction.


Demo
A live webcam-based demo is available upon running the application locally. Users can view real-time emotion predictions rendered directly on their video feed.

Installation
To set up Emotion-Lens on your machine, follow these steps:

Clone the repository:

git clone https://github.com/typicallylakshmi/Emotion-lens.git
cd Emotion-lens

Install dependencies:

Make sure you have Python installed. Then install the required packages:
pip install -r requirements.txt

Run the application:
python emotion_detector.py
A window will open using your webcam. Detected emotions will be displayed on your face in real-time.

Features
1.Real-time face detection using OpenCV's Haar cascades.

2.CNN-based emotion classification trained on FER2013 dataset.

3.Support for seven primary emotions: Angry, Disgust, Fear, Happy, Sad, Surprise, and Neutral.

4.Minimalistic UI with instant feedback.

5.Custom-trained Keras model for high accuracy and speed.

Dependencies
The project relies on:

1.opencv-python: For face detection and video streaming.

2.tensorflow / keras: For deep learning model loading and inference.

3.numpy: For numerical operations.

4.matplotlib: (Optional) For plotting training metrics or debugging.


Install with:
pip install opencv-python tensorflow keras numpy matplotlib
Project Structure
graphql


Emotion-lens/
├── .env
├── page.html
├── setting.json          
└── README.md               # Project documentation



Conclusion
Emotion-Lens is a powerful yet accessible tool that showcases the potential of deep learning and computer vision in understanding human emotions. With real-time facial expression recognition, it opens doors for applications in mental health analysis, user experience enhancement, e-learning engagement, and more. The project is designed to be lightweight, easy to set up, and highly extensible—making it a great starting point for developers, researchers, and students interested in affective computing. Future improvements could include multi-modal emotion detection (voice, text), emotion trend tracking, and deeper integration with user interfaces.
