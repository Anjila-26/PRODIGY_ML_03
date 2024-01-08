# Image Classification with Support Vector Classifier (SVC)

## Overview

This repository contains code for training an image classifier using a Support Vector Classifier (SVC) with Histogram of Oriented Gradients (HOG) features. The code uses the scikit-learn library for SVC and the scikit-image library for HOG feature extraction. The trained model is saved for future use, and predictions are made on a test dataset.

## Contents

- **`train_classifier.py`**: Python script for training the SVC model. It reads images from the 'train1' directory, extracts HOG features, and performs classification.

- **`extract_hog_features`**: Function to extract HOG features from a given image.

- **`SVC_model.sav`**: The saved SVC model file after training.

- **`test_classifier.py`**: Python script for testing the trained SVC model on a test dataset. It loads the saved model and makes predictions on images in the 'test1' directory.

- **`submission.csv`**: The output file containing predictions for the test dataset.
