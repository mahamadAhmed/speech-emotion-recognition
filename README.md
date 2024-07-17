### Speech Emotion Recognition (SER)
## Overview
Speech Emotion Recognition (SER) is a pivotal area within the intersection of signal processing, machine learning, and psychology. This project focuses on developing a system capable of understanding and interpreting human emotions through speech. By leveraging data from four distinct datasets—SAVEE, RAVDESS, CREMA, and TESS—we aim to classify emotions into four categories: sad, angry, neutral, and happy. The model employs a 1D Convolutional Neural Network (CNN) for emotion classification and utilizes openSMILE for feature extraction.

## Datasets
The project uses the following datasets:

RAVDESS: Ryerson Audio-Visual Database of Emotional Speech and Song.
CREMA: Crowd-sourced Emotional Multimodal Actors Dataset.
TESS: Toronto Emotional Speech Set.
SAVEE: Surrey Audio-Visual Expressed Emotion.

## Emotion Classes
The model focuses on classifying the following emotion classes:
Sad
Angry
Neutral
Happy

## Features
Relevant acoustic features are extracted using openSMILE and other signal processing techniques.
Data Augmentation
To enhance the training data, various data augmentation techniques are employed:

## Noise Injection
Stretching
Shifting
Pitching

## Model
The model is a 1D Convolutional Neural Network (CNN) designed to classify emotions from speech data. The architecture includes several convolutional layers followed by pooling and dropout layers to prevent overfitting. Batch normalization is used for faster convergence.

## Training and Evaluation
The model is trained using the extracted features from the combined datasets. Early stopping and learning rate reduction callbacks are used to optimize training. The model's performance is evaluated using metrics such as accuracy, and confusion matrices are plotted to visualize the classification results.

## Conclusion
This project combines data from multiple datasets and employs advanced feature extraction and model training techniques to improve the state-of-the-art in Speech Emotion Recognition. The developed model is capable of accurately classifying emotions and holds promise for real-world applications.
