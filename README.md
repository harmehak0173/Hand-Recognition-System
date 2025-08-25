# Hand-Recognition-System
This project is a real-time system that can recognize simple hand gestures and sign language. It uses a webcam to detect your face, hands, and body movements, and then predicts what gesture you are doing.

## What It Does

Recognizes gestures like "hello", "thanks", and "I love you".

Tracks your body, face, and hands to understand movements.

Shows what gesture it detects on the screen in real-time.

Shows confidence levels for each gesture with colored bars.

## How It Works

Capture Video: Uses your webcam to record movements.

Detect Key Points: Finds important points on your hands, face, and body.

Save Data: Stores these points for each gesture so the computer can learn them.

Train Model: Uses the collected data to train a computer model to recognize gestures.

Real-Time Prediction: After training, the model can recognize gestures from your live webcam feed and display them.

## Getting Started

Install Python if you don’t have it.

Install required libraries like OpenCV, MediaPipe, TensorFlow, NumPy, and Matplotlib.

Run the data collection script to capture gestures.

Train the model using the collected data.

Run the real-time detection script to see the gestures on your screen.

## Dataset Structure

Each gesture has its own folder.

Each video sequence of a gesture is saved in a separate folder.

Each frame of the video is saved as a file containing the key points.

## How to Use

Look at the webcam and perform a gesture.

The program will show the gesture name on the screen.

Colored bars show the confidence level for each gesture.

## Tools Used

Python – Programming language

OpenCV – To capture video from your webcam

MediaPipe – To detect hands, face, and body points

TensorFlow/Keras – To train the gesture recognition model

NumPy – To handle data

Matplotlib – To show probabilities visually
