# Speech Emotion Recognition 

## Overview
This repository contains code for Speech Emotion Recognition using deep learning techniques. The goal is to recognize emotions from audio files using various models like Convolutional Neural Networks (CNN) and Long Short-Term Memory networks (LSTM).

## Libraries
- numpy
- pandas
- librosa
- matplotlib
- scikit-learn
- keras
- tensorflow

## Data Preparation
The dataset used in this project includes audio files from various sources such as RAVDESS, CREMA-D, TESS, and SAVEE. The data is prepared by extracting features like Zero Crossing Rate, Root Mean Square Energy, and Mel-frequency cepstral coefficients (MFCC) from the audio files.

## Feature Extraction
Features are extracted from audio files using various signal processing techniques provided by the librosa library. These features are then used as inputs for the deep learning models.

## Models Implemented
### 1. Convolutional Neural Network (CNN)
A CNN model is implemented for speech emotion recognition. The model architecture consists of multiple convolutional layers followed by batch normalization, max-pooling, and dropout layers to prevent overfitting.

### 2. Long Short-Term Memory (LSTM)
An LSTM model is implemented for speech emotion recognition. The model architecture consists of LSTM layers followed by fully connected layers to classify emotions.

## Evaluation
The models are evaluated using test data, and performance metrics such as accuracy are computed. The best performing model is saved for future use.

## Skills: 
- Data preprocessing
- Feature engineering
- Building CNN models.

## Lesson Learned
The project mentions data augmentation. This technique increases the amount of training data and helps the model generalize better.

## Accuracy

![Screenshot 2024-03-28 160130](https://github.com/Owais-Shaikh-0786/Speech-Emotion-Recognition-with-librosa/assets/139638554/e52e96db-b281-4f63-aa50-cde40bee259d)

## Output

![Screenshot 2024-03-28 160152](https://github.com/Owais-Shaikh-0786/Speech-Emotion-Recognition-with-librosa/assets/139638554/a3ac6ca3-635c-4e31-8747-0c2d61982260)

