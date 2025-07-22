# Cyber Threat Detection using Deep Learning

This project implements a deep learning model for network intrusion detection using a hybrid CNN + BiLSTM architecture with focal loss and sequence windowing.

## Features
- Sequence modeling with temporal windows
- Focal loss for class imbalance
- CNN + BiLSTM architecture
- ROC curve and threshold tuning
- Class weighting
- Early stopping

## Dataset
CICIDS dataset preprocessed from:
`/kaggle/input/network-intrusion-detection/Train_data.csv`

## Requirements
- Python 3.x
- TensorFlow 2.x
- scikit-learn
- pandas
- matplotlib
- seaborn

## Usage
```bash
# Train the model and evaluate
Run the notebook: cyber_threat_detection_final.ipynb
```

## Output
- Confusion Matrix
- ROC AUC Curve
- Optimized threshold for 99% accuracy+
