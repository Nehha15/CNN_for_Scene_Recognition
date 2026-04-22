# Scene Recognition using ResNet-34 (Transfer Learning)

## Overview
This project focuses on classifying images into 40 scene categories using transfer learning on a pre-trained ResNet-34 model and the Places2 dataset (~40,000 images).

## Key Features
- **Data preprocessing:** resizing (128×128 → 224×224), grayscale conversion, normalization  
- **Data augmentation:** rotation, translation, scaling, horizontal flip  
- **Model architecture:** modified fully connected layers (256 → 40) with ReLU and dropout (0.4)  
- **Training setup:** AdamW optimizer, learning rate 0.0001, batch size 12, CosineAnnealingLR  

## Results
- **Test Accuracy:** 66.9%  
- **Top-5 Accuracy:** 93.7%  

## Evaluation
- Confusion matrix and classification report  
- Analysis of training/validation loss to identify overfitting  

## Dataset
- Places2 (simplified): https://drive.google.com/file/d/1jp4mVtTeP4lFyHEWYUGF7Sd4JctOH7Uk/view  
- Test dataset: https://drive.google.com/file/d/1mFltwESpAY5H52vpnterCP1quqFy0cym/view  
