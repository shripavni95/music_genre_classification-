My project is a music genre classification system that uses machine learning techniques to analyze audio files and predict their genre. The system is built using Python and leverages several libraries for audio processing and machine learning.
Key Components:
-> Feature Extraction:
*Use Mel-frequency cepstral coefficients (MFCC) to extract features from audio files.
*The python_speech_features library is used to compute MFCC features.

-> Dataset:
*The system uses a dataset of audio files organized into different genre folders.
*It processes .wav files from each genre folder to create a training and testing dataset.

-> Machine Learning Model:
*Implement a k-Nearest Neighbors (k-NN) algorithm for classification.
*The distance between audio samples is calculated using a custom distance function that considers mean and covariance of MFCC features.

-> Training and Testing:
*The dataset is split into training and testing sets (66% for training, 34% for testing).
*The model is trained on the training set and evaluated on the testing set.

-> Prediction:
*The system can predict the genre of new, unseen audio files.

->Performance:
*The accuracy of the model is calculated and printed (about 70.8% in the example run).

-> Genre Mapping:
*The system maps numeric labels to genre names for easy interpretation of results.

-> External Testing:
*The project includes functionality to test the model on external audio files.


Technical Details:
*Programming Language: Python
*Key Libraries: python_speech_features, scipy, numpy
*Audio Processing: MFCC feature extraction
*Machine Learning Algorithm: k-Nearest Neighbors
*Dataset Handling: Custom functions for loading and processing audio files
