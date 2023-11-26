# DeepFake Detection Model

## 1. Introduction
This projects aims in detection of video deepfakes using deep learning techniques like ResNext and LSTM. We have achived deepfake detection by using transfer learning where the pretrained ResNext CNN is used to obtain a feature vector, further the LSTM layer is trained using the features. 

## 2. Dataset 
The dataset was a combined dataset from various sources like FaceForensics++ Forensics Dataset, Celebrity Dataset. To avoid overfitting, we ensured to make our own combined dataset of 6000 videos for a better accuracy. 

##3. Model 
The model was finally trained on the above mentioned architecture on the combined dataset, which gave an accuracy of  over 90 % for 60 frames. 
