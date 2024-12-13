
# Yoga Pose Detection

## Overview
This project implements a yoga pose detection system using deep learning techniques. The model classifies yoga poses as correct or incorrect based on images captured from a webcam.

## Data Preprocessing
- The dataset is organized into `train`, `valid`, and `test` folders.
- Images are transformed using resizing, augmentation, and normalization.

## Model Architecture
- Pre-trained ResNet-18 model is used and modified for binary classification.

## Training
- The model is trained for 10 epochs with a batch size of 8 and a learning rate of 0.0001.

## Results
- Validation and test accuracies are reported.

## Real-time Inference
- The model can provide real-time feedback on yoga poses using webcam input.

