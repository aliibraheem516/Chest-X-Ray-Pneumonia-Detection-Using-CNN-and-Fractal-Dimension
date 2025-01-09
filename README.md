# Chest-X-Ray-Pneumonia-Detection-Using-CNN-and-Fractal-Dimension
A deep learning project that detects pneumonia in chest X-ray images using a convolutional neural network (CNN) and enhances feature extraction with fractal dimension analysis

# Dataset
The dataset used in this project is publicly available on Kaggle :

- Chest X-Ray Images (Pneumonia)

# Changes Made to the Dataset :

1-Renamed Dataset Folder: The dataset folder was renamed to xray for simplicity.

2-Combined Training and Testing Data:
-Images from the original train and test folders were combined into two subdirectories:

   -Normal and PNEUMONIA

3-Validation Data: The val/ folder was left unchanged and used as-is for evaluation purposes.

# Features :
# 1-Image Preprocessing:

Resized images to 128x128.

Normalized pixel values to the range [0, 1].

Converted images to grayscale for simplicity.

# 2-Fractal Dimension Analysis: ( will be explained properly in the next repository )

Extracted complexity features from images using the box-counting method.

# 3-CNN Architecture:

Built a convolutional neural network for binary classification (Normal vs. Pneumonia).

# 4-Prediction on New Data:

Allows predictions on unseen chest X-ray images.
