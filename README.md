# MNIST-Digit-Classification
The MNIST dataset is a classic benchmark in machine learning for image classification. It consists of 70,000 grayscale images of handwritten digits (28x28 pixels), each labeled from 0 to 9.  This project trains an MLP model on the dataset and allows users to draw digits on a virtual canvas and get real-time predictions using a Gradio interface. 

# Dataset
Source: https://www.kaggle.com/datasets/crawford/emnist<br>
Features: 28x28 grayscale images<br>
Labels: Integers from 0 to 9<br>
Shape after flattening: 784 features per image<br>
Presentation :https://www.canva.com/design/DAGvIm9-B6Y/FL1KiMM94am6tNV3qnGhkw/edit?utm_content=DAGvIm9-B6Y&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton<br>

# Results
After training and evaluating two different models on the MNIST dataset:<br>
Best Performing Model: **Convolutional Neural Network** (CNN) and achieved **99%** accuracy.<br>
**MLPClassifier** also performed well and achieved **97%** accuracy.<br>
Both models were integrated into an interactive Gradio canvas app for testing handwritten digits.<br>


![WhatsApp Image 2025-08-07 at 06 00 00_5ec3e1ba](https://github.com/user-attachments/assets/c85abdda-7eda-43e8-a42f-73100f048e03)
