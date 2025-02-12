# Audio Intent Detection Lab

## Project Description

**Audio Intent Detection Lab** is a research-driven project aimed at improving **speech-based intent recognition** using **deep learning models**. The project focuses on accurately predicting the **intended action and object** from spoken audio commands, a crucial task for **voice assistants** and **speech-based applications**.

The system processes **WAV audio files**, extracting features that represent **spoken intent**, and classifies them into distinct **intent labels**. The project ensures robust performance through **Convolutional Neural Networks (CNNs)**, leveraging hierarchical feature extraction for better classification accuracy.

## Methodology

The project develops a **deep learning-based pipeline** to analyze and classify spoken commands. It includes:

- **Audio Feature Extraction**: Uses **Librosa** to extract key spectrogram-based features for training.
- **CNN-Based Classification**: Implements a **1D Convolutional Neural Network (CNN)** with **PReLU activation** and **GlorotUniform initialization** for effective feature learning.
- **Model Optimization**: Fine-tunes hyperparameters, including **batch size**, **epochs**, and **learning rate scheduling**, to improve classification accuracy.

### Pipeline Overview

1. **Preprocessing & Feature Engineering**: Converts raw **WAV files** into feature vectors.
2. **Model Training**: Trains a **CNN model** to classify **audio intent**.
3. **Prediction & Evaluation**: Predicts the **intent label** using concatenated **action-object pairs** (e.g., `"increasevolume"`).
4. **Submission Format**: Generates a **CSV file** with predictions for evaluation.
