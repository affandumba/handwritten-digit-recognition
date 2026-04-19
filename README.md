# Handwritten Digit Recognition

## Problem Statement
Recognize handwritten digits (0-9) from images using a Convolutional Neural Network.

## Dataset
- MNIST Dataset (built into TensorFlow/Keras — no download needed)
- 70,000 images — 60,000 training, 10,000 testing
- Each image is 28x28 pixels, grayscale

## Model Architecture (LeNet-5 inspired)
- Conv2D (6 filters, 5x5) → AveragePooling
- Conv2D (16 filters, 5x5) → AveragePooling
- Flatten → Dense (84) → Dense (10, Softmax)

## Highlights
- EDA with sample digit visualization and class distribution
- Data normalized using mean and std
- Train / Validation / Test three-way split
- Training accuracy and loss curves plotted
- Confusion Matrix + Classification Report per digit
- Sample predictions with correct/wrong color coding

## Result
| Metric | Score |
|---|---|
| Test Accuracy | ~98% |
| Epochs | 15 |
| Batch Size | 32 |

## Tools & Libraries
Python, NumPy, TensorFlow, Keras, Scikit-learn, Matplotlib, Seaborn
