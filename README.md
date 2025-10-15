# Traffic-Sign-Recognition

Project Overview
This project implements an Industry-Level Computer Vision solution to classify traffic signs. The goal is to build a robust model capable of recognizing and categorizing 43 distinct traffic sign classes from real-world images. This technology is foundational for Advanced Driver-Assistance Systems (ADAS) and autonomous vehicles.

🔑 Key Concepts and Techniques
Model Architecture: Built a custom Convolutional Neural Network (CNN) (LeNet-style architecture) using Keras/TensorFlow.

Multi-Class Classification: Solved the complex challenge of classifying images into 43 separate categories.

Preprocessing Pipeline: Handled image data preparation, including resizing (to 32×32 or 48×48 pixels), normalization (scaling pixel values to 0−1), and One-Hot Encoding of class labels.

Data Augmentation (Bonus): Used Keras's ImageDataGenerator during training to artificially increase the dataset size and prevent model overfitting against real-world variations (e.g., rotation, zoom).

💾 Dataset and Aim
Name: GTSRB (German Traffic Sign Recognition Benchmark).

Aim: To provide a large, lifelike database of images captured under diverse lighting and environmental conditions to challenge and develop highly reliable image classification models.

📊 Final Performance
The trained CNN model was evaluated using Overall Accuracy and the Classification Report across all 43 classes.

The final model demonstrated a high classification accuracy on unseen images, confirming its ability to generalize effectively for mission-critical visual tasks.

🛠️ Technologies
Python

TensorFlow / Keras (Deep Learning Framework)

NumPy (Numerical operations)

PIL/OpenCV (Image loading and manipulation)

Scikit-learn (Metrics)
