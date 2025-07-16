# Emotion Detection Using EEG Signals

### Project Overview:

This project focuses on classifying human emotions using EEG (Electroencephalography) signals to enhance human-computer interaction systems. The model detects three emotional states: Happy, Disgust, and Neutral.

### Key Components:

1. Data Acquisition

 - Subjects: Data collected from 10 participants, average age 21

 - EEG Electrodes Used: Fp1, Fp2, F3, F4 (frontal lobe positions)

2. Preprocessing

 - Sliding Window Technique: Captured time-segmented features from continuous EEG signals

 - Notch Filter (49–51 Hz): Removed powerline interference

 - Band-Pass Filter (8–30 Hz): Preserved relevant EEG frequency bands and reduced noise

3. Classification

 - Three machine learning models were tested:

   - Random Forest
   - Support Vector Machine 
   - Decision Tree

### Technologies Used:

 - Python

 - Scikit-learn – For ML algorithms

 - SciPy / NumPy – For EEG signal preprocessing

### Features:

 - Emotion detection using EEG signals

 - Sliding window segmentation for time-series analysis

 - Artifact removal through filtering

 - Performance evaluation using accuracy, precision, recall, and F1 score
