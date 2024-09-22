# Face Recognition Using SVM and Wavelet Transform

This project uses image processing and machine learning techniques to classify celebrity faces. The primary aim is to detect faces from images, apply wavelet transformation, and train a Support Vector Machine (SVM) classifier for recognition.

## Features
- **Face Detection**: Detects faces using OpenCV’s Haar cascades.
- **Wavelet Transformation**: Extracts features from images using wavelet transform.
- **SVM Classifier**: Trains a Support Vector Machine (SVM) to classify faces.
- **GridSearchCV**: Tunes hyperparameters for better model performance.
- **Model Evaluation**: Uses a confusion matrix to visualize predictions.
- **Model Saving**: Saves the trained model and the class dictionary for future use.

## Requirements

Install the necessary dependencies by running:
```bash
pip install -r requirements.txt
