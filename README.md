Real-Time Emotion Detection

This project is a real-time emotion detection system developed using TensorFlow and Convolutional Neural Networks (CNN). It is designed to process live video feeds and accurately classify human emotions based on facial expressions.

Table of Contents

Overview
Features
Model Training
Installation
Usage
Results
Contributing
License
Overview

The Real-Time Emotion Detection project aims to detect and classify emotions such as happiness, sadness, anger, and more through a live video feed. The model was trained using a dataset of facial images and achieved an accuracy of 56%.

Features

Real-Time Emotion Detection: Processes live video feeds to detect and classify emotions.
TensorFlow & CNN: Built using TensorFlow and Convolutional Neural Networks for image classification.
Accuracy: The model was trained on an image dataset and achieved 56% accuracy.
Model Training

The emotion detection model was trained using a dataset of facial images. The model utilizes Convolutional Neural Networks (CNN) to learn and recognize patterns in facial expressions. The training process resulted in an accuracy of 56%.

Installation

To run this project locally, follow these steps:

Clone the repository:
bash
Copy code
git clone https://github.com/keshav479/Realtime_emotion_detection.git
cd emotion-detection
Install the required dependencies:
bash
Copy code
pip install -r requirements.txt
Run the application:
bash
Copy code
python main.py
Usage

After installation, the application can be run by executing the main.py script. The system will begin processing the video feed from your webcam and display real-time emotion predictions.

Results

The model was evaluated using a test dataset, achieving an accuracy of 56%. While this indicates room for improvement, the system effectively demonstrates real-time emotion detection capabilities.

Contributing

Contributions are welcome! Please open an issue or submit a pull request for any improvements or feature requests.

License

This project is licensed under the MIT License - see the LICENSE file for details.
