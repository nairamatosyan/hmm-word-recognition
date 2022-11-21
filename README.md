# HMM Isolated Word Recognition

### Requirements
- Python version 2.x
- hmmlearn package 
- python_speech_features package
- matplotlib package
- sklearn package

### Description
This project constructs an HMM model for audio files of 10 categories (digits 0-9) and predicts corresponding labels on testing set by calculating the log-likelihood score of corresponding audio.

The dataset used is Speech Commands Dataset released by Google (https://datarepository.wolframcloud.com/resources/Spoken-Digit-Commands-Dataset) represented in Audio folder.

The audio files are processed beforehand and MFCC representation of corresponding sounds is extracted for better processing.

The results are visualized by using confusion matrix based on testing set's real an predicted values.
