# Breast Cancer Detection Using Deep Learning

## Overview

Deep Learning project for breast cancer detection using medical image
classification with EfficientNet.

## Objective

The objective of this project is to develop a deep learning model capable
of classifying medical images for breast cancer detection.

## Technologies

- Python
- PyTorch
- EfficientNet
- Computer Vision
- Deep Learning
- NumPy
- Pandas
- Scikit-learn
- Matplotlib

## Model

The project uses EfficientNet as the backbone for medical image
classification.

## Training

The training pipeline includes:

- Data preprocessing
- Image augmentation
- Train/validation/test split
- Weighted loss
- Mixed-precision training
- Gradient clipping
- Early stopping

## Evaluation

The model was evaluated using:

- ROC-AUC
- PR-AUC
- Precision
- Recall
- F1-Score

## Model Performance

The model was evaluated on the test set using multiple classification metrics.

- ROC-AUC: 0.781
- PR-AUC: 0.158
- Precision: 0.0537
- Recall: 0.6777
- F1-Score: 0.0995
- ## Key Results

The model achieved a ROC-AUC of 0.781 and a PR-AUC of 0.158 on the test set.

The selected classification threshold was 0.95, with a recall of 0.6777.
## Project Structure
## Installation

Install the required dependencies:

```bash
pip install -r requirements.txt
```text
Breast-Cancer-Detection/
│
├── README.md
├── requirements.txt
├── notebooks/
├── src/
├── models/
└── data/How to Run
Clone the repository.
Install the required dependencies.
Prepare the dataset.
Run the training or inference notebook/script.
