# Speech_Emotion_Recognition_for_Human_Computer_Interaction

## Introduction

This project focuses on developing a Speech Emotion Recognition (SER) system capable of accurately identifying emotions expressed in spoken language. The system distinguishes between various emotions, including but not limited to happiness, sadness, anger, fear, disgust, and neutrality. The project's main objective is to enhance human-computer interaction by enabling machines to understand and respond appropriately to human emotions conveyed through speech.

## Features

- **Dataset:** Obtain a diverse dataset of audio recordings containing speech samples across different emotions. The dataset is collected from Kaggle (https://www.kaggle.com/datasets/dmitrybabko/speech-emotion-recognition-en/data).
- **Preprocessing:** Preprocess the audio data to extract relevant features, handle varying lengths, and ensure consistency.
- **Model Development:** Design and implement a deep learning model for speech emotion recognition, experimenting with different architectures.
- **Training and Validation:** Train the model on a substantial portion of the dataset, reserving a subset for validation to prevent overfitting.
- **Evaluation:** Utilize appropriate evaluation metrics to assess the model's performance on both training and validation sets.

## Usage

1. **Data Collection and Preprocessing:**
   - Gather a diverse dataset of audio recordings with labeled emotions.
   - Preprocess the audio data to extract features and ensure consistency.

2. **Model Development:**
   - Design and implement a deep learning model.

3. **Training and Validation:**
   - Train the model on a substantial portion of the dataset.
   - Use a validation set to monitor model performance.

4. **Testing:**
   - Evaluate the final model on an independent test set.
     
## Important Requirements

- import os                                   
- import librosa                              
- import librosa.display
- from IPython.display import Audio           
- import IPython.display as ipd
- from scipy.io import wavfile as wav         
- from scipy.signal import resample

## Result

The model has demonstrated excellent performance on the training data, achieving an accuracy of 99%. This suggests that the model has successfully learned the patterns and features in the training dataset.
The model maintains a high accuracy of 95% on the validation dataset. This is a positive sign as it indicates that the model generalizes well to unseen data. It performs reliably across different emotions, which is crucial for speech emotion recognition.

## Contact

If you have any questions, feel free to reach out to me at harshalwadke26@gmail.com

