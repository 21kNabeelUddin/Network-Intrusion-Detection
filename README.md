# Binary Classification with Neural Networks

This repository contains a TensorFlow-based implementation of a binary classification model for machine learning tasks. The model leverages a fully connected neural network to predict binary outcomes based on input numerical features.

# Features

## Data Preprocessing:

Handles missing values and infinite values.

Removes low-variance features to improve model efficiency.

Selects top features using SelectKBest with mutual_info_classif.

## Model Architecture:

Input normalization using Batch Normalization.

Three fully connected layers with ReLU activations.

Dropout for regularization.

Output layer with sigmoid activation for binary classification.

## Training:

Early stopping to avoid overfitting.

Learning rate reduction on plateau.

## Evaluation:

Confusion matrix and classification report.

Accuracy and loss visualization.

## Installation

Clone the repository:
```bash
git clone https://github.com/21kNabeelUddin/Network-Intrusion-Detection.git
```
```bash
cd Network-Intrusion-Detection
```

Install required dependencies:
```bash
pip install -r requirements.txt
```



# Results

Achieved significant accuracy on binary classification tasks.

Confusion matrix and classification report demonstrate model performance.

## License

This project is licensed under the MIT License - see the LICENSE file for details.


Feel free to contribute or raise issues!
