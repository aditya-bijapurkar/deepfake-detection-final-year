# Deepfake detection using Deep Learning (ResNext and LSTM)

## 1. Introduction
This project aims to detect video deepfakes using deep learning techniques like ResNext and LSTM. We have achieved deepfake detection by using transfer learning where the pretrained ResNext CNN is used to obtain a feature vector, further, the LSTM layer is trained using the features.

## 2. Directory Structure
For ease of understanding the project is structured in the below format
```
Deepfake_detection_using_deep_learning
    |
    |--- Django Application
    |--- Model Creation
```
1. Django Application 
   - This directory consists of the Django-made application of our work. Where a user can upload the video and submit it to the model for prediction. The trained model performs the prediction and the result is displayed on the screen.
     
2. Model Creation
   - This directory consists of the step-by-step process of creating and training a deepfake detection model using our approach.
