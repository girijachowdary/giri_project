# giri_project
Developed an ECG classification system using the PTB-XL dataset. ECG signals were filtered, normalized, and combined with clinical metadata. A ResNet-SE fusion model with autoencoder augmentation was trained for 3-class and binary classification, achieving 83.4% and 98.8% accuracy respectively.

# PTB-XL ECG Classification

## Project Overview

This project focuses on ECG signal classification using the PTB-XL ECG dataset. The ECG signals are preprocessed and classified using a deep learning approach.

## Dataset

The project uses the PTB-XL ECG dataset, which contains 12-lead clinical ECG recordings.

The classification task includes:

- Normal
- Myocardial Infarction (MI)
- Left Ventricular Hypertrophy (LVH)
- MI + LVH

## Methodology

The project includes:

1. ECG signal preprocessing
2. Noise filtering and signal normalization
3. Dataset preparation
4. Deep learning model development
5. Model training and validation
6. Performance evaluation

## Technologies Used

- Python
- NumPy
- Pandas
- SciPy
- Scikit-learn
- TensorFlow / Keras
- ECG Signal Processing
- 1D Convolutional Neural Network (CNN)
- Kaggle

## Project Notebook

The complete implementation is available in the Jupyter Notebook:

`PTB-XL ECG Classification.ipynb`

## Results

The notebook contains the training results, classification metrics, and evaluation of the trained model.

## Dataset Source

PTB-XL ECG dataset by PhysioNet.

> Note: The dataset itself is not included in this repository because of its size and licensing/distribution considerations.
