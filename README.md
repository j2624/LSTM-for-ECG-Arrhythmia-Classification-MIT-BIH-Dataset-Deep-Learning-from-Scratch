# LSTM for ECG Arrhythmia Classification

## Project Overview
Built an LSTM deep learning model from scratch to classify 
ECG heartbeats into 5 arrhythmia classes using the 
MIT-BIH dataset.

## Results
- Accuracy: 95.6%
- Ventricular AUC: 1.00
- Fusion F1: improved from 0.00 to 0.56
- 7 model iterations

## Dataset
MIT-BIH Arrhythmia Database
- 87,554 training samples
- 21,892 test samples
- 5 classes: Normal, Supraventricular, Ventricular, 
  Fusion, Unknown

## Key Techniques
- Manual Class Weights (no SMOTE — medical data)
- AdamW Optimizer
- Early Stopping
- Dropout regularisation

## Full Notebook
https://www.kaggle.com/code/jyothiprabhu/lstm-on-ecg-deataset

## Tools Used
Python · TensorFlow · Keras · Sklearn · Kaggle GPU
