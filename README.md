
# Audio Samples Classification - MachineHack Week 13 Hackathon
# Overview
This project focuses on classifying audio samples to distinguish between major and minor chords using audio data. The dataset consists of audio files from two instruments: guitar and piano. Major chords are associated with happy, bright tones, while minor chords have a melancholic, sad tone. The goal is to build a model that can accurately classify the audio files based on these characteristics.

# Problem Statement
Given a collection of audio samples in the form of .wav files, the task is to classify whether the chord in each sample is a major or minor chord. The classification should be based on the features extracted from the audio signals.

# Dataset
Train.csv: Contains the mapping between the audio files and their corresponding chord classification (major/minor).

Test.csv: Contains audio files for which predictions will be made.

Submission.csv: Format for submitting predictions with the audio file names and their predicted chord classifications.

# Tools and Libraries Used
Python

Librosa: For audio feature extraction such as MFCCs (Mel-frequency cepstral coefficients).

Scikit-learn: For building the classification models.

Matplotlib: For visualizing audio features and model performance.

TensorFlow/Keras: For deep learning models (CNNs/RNNs) for better classification accuracy.

# Train the model:

Implement models such as Logistic Regression, Random Forests, or advanced models like CNN/ RNN for deep learning.
Train and tune the models using cross-validation techniques.
Evaluate the model:

Use accuracy as the primary evaluation metric.
Fine-tune the model parameters for optimal performance.
Make Predictions:

Use the trained model to make predictions on the test dataset.
Submit the predictions in the required format (Submission.csv).
# Evaluation
The model will be evaluated based on Accuracy: The percentage of correctly classified samples (major/minor chords).
# Results
Rank: 26th (MachineHack Week 13 Hackathon)
# Conclusion
The project demonstrates the use of audio feature extraction and machine learning models for classification tasks. The model was able to distinguish between major and minor chords with reasonable accuracy and can be further improved using more advanced techniques.
