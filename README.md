Face Mask Detection System

Project Overview

This project presents a machine learning-based Face Mask Detection System, designed to accurately identify and differentiate between masked and unmasked human faces. Utilizing a dataset of labeled face images, the system achieves high performance with 99% accuracy on test data.

Technologies Used

- MobileNetV2: Pre-trained convolutional neural network (CNN) architecture for efficient feature extraction
- Tensorflow: Open-source machine learning framework for model development and training
- Keras: High-level neural networks API for building and experimenting with deep learning models
- NumPy: Library for efficient numerical computation and data manipulation
- OpenCV: Computer vision library for image processing and face detection

Project Details

- Dataset: Dataset consists of 3833 images i.e., 1918 with mask and 1915 without mask
- Model Training: The MobileNetV2 architecture was trained on the labeled dataset, with [batch size = 32, epochs = 20, optimizer = adam]
- Model Evaluation: The trained model achieved 99% accuracy on test data, demonstrating high performance in face mask detection

Usage

1. Install dependencies: pip install -r requirements.txt
2. Train the model to generate model file: python train_mask_detector.py
3. Execution: python detect_mask_video.py
