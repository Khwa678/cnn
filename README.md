🐶🐱 Cats vs Dogs Image Classification using CNN
📘 Overview

This project focuses on binary image classification — distinguishing between cats and dogs using a Convolutional Neural Network (CNN) built with TensorFlow and Keras.
The model is trained on the Microsoft Cats vs Dogs dataset, a classic dataset widely used for computer vision learning and deep learning experiments.

📂 Dataset

Source: Microsoft Cats vs Dogs Dataset (Kaggle)

Size: 25,000 images (12,500 cats 🐱 + 12,500 dogs 🐶)
Each image is labeled and used for supervised training.

In this project, a filtered subset of 2,000 training and 1,000 validation images was used for faster training.
🧠 Model Architecture

A Convolutional Neural Network (CNN) was implemented using keras.Sequential.
It consists of multiple convolutional and pooling layers to capture image features efficiently.

Layers:

Conv2D → MaxPooling2D (feature extraction)

Flatten → Dense (classification)

Dropout (regularization)

Output layer → Sigmoid activation (binary classification)
