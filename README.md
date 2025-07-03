# TrafficSimAI

🚦 CS50 AI Project 5: Traffic
🎯 Purpose
The goal of this project is to build an AI model capable of recognizing and classifying traffic signs from images—a critical task in the development of self-driving cars. This project introduces you to computer vision and convolutional neural networks (CNNs) using TensorFlow. You'll work with the German Traffic Sign Recognition Benchmark (GTSRB) dataset, which contains thousands of labeled images across 43 traffic sign categories.

🧠 What the Code Does
The traffic.py script performs the following key tasks:

Data Loading (load_data):

Reads images from the dataset using OpenCV.

Resizes them to a uniform shape (e.g., 30x30 pixels).

Labels each image based on its directory (0–42).

Returns the image data and corresponding labels.

Model Building (get_model):

Constructs a CNN using TensorFlow/Keras.

Includes convolutional, pooling, and dense layers.

Compiles the model with appropriate loss and optimizer functions.

Training and Evaluation:

Splits the dataset into training and testing sets.

Trains the model on the training data.

Evaluates its accuracy on the test set.

Optionally saves the trained model to a file.
