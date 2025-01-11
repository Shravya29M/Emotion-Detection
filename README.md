# Emotion Detection from Facial Images

This project is focused on detecting human emotions from facial images using Novel CNN Model. The model is trained on the CK+ dataset from Kaggle, achieving an accuracy of 99%. The implementation involves preprocessing, data augmentation, and building a custom convolutional neural network with advanced layers and blocks, such as Depthwise Convolutions and Squeeze-and-Excitation blocks, for feature extraction.

---

## Features

1. **Dataset**: CK+ Dataset from Kaggle.
   - Classes: Surprise, Fear, Sadness, Disgust, Contempt, Happy, Anger.
   - Each emotion class contains multiple facial expressions.

2. **Accuracy**: Achieved a remarkable accuracy of **99%** on the test set.

3. **Model Architecture**:
   - Custom CNN with Depthwise Convolutions.
   - Squeeze-and-Excitation blocks for feature recalibration.
   - Residual connections for improved gradient flow.
   - Global Average Pooling to reduce parameters.
   - Fully connected layers with Dropout for regularization.

4. **Callbacks and Visualization**:
   - Grad-CAM for interpreting model predictions.
   - Custom callback to monitor training progress.

---

## Requirements

### Libraries
- Python 3.8+
- TensorFlow 2.x
- OpenCV
- NumPy
- Matplotlib

Install the required libraries using:
```bash
pip install tensorflow opencv-python numpy matplotlib
```

### Dataset
Download the CK+ dataset from Kaggle and organize it into subdirectories for each emotion.

---

## Results

The model achieved an accuracy of **99%** on the test set, demonstrating its effectiveness in emotion detection.




