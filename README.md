# Neural Networks Project - Gesture Recognition

## Table of Contents:
* [Introduction](#introduction)
* [Problem Statement](#problem-statement)
* [Objectives](#objectives)
* [Dataset Description](#dataset-description)
* [Conclusion](#conclusion)
* [Technologies Used](#technologies-used)
* [References](#references)
* [Contact Information](#contact-information)

## Introduction:  
<div align="justify">This repository contains the python code to build a project, which aim to develop a gesture recognition feature for smart televisions using deep learning techniques. The task involves recognizing five different gestures performed by users in front of a webcam, each corresponding to a specific command: thumbs up, thumbs down, right swipe, left swipe, stop (pause). This feature will enable users to control the TV without using a remote. </div>

## Problem Statement:  
<div align="justify">
The task involves training a model on a dataset of videos, where each video contains a sequence of 30 frames/images. The dataset is divided into training and validation sets, with each video categorized into one of the five gesture classes. The main aim is to develop a model that performs well on both the training and validation sets, with the ultimate goal of achieving good performance on an unseen test set. </div>


## Objectives:  
<div align="justify">The main objective is to build a gesture recognition feature in the smart-TV using deep learning techniques that can recognise five different gestures performed by the user which will help users control the TV without using a remote. </div>

## Dataset Description:   
- The dataset is provided in a zip file containing 'train' and 'val' folders, each with corresponding CSV files. </br>
- Videos are organized into subfolders within the 'train' and 'val' directories, with each subfolder representing a video of a particular gesture.</br>
- Each row in the CSV files contains information about a video, including the name of the subfolder (containing the 30 images), the gesture name, and the numeric label (0-4) of the video.</br>
- Videos may have different dimensions, either 360x360 or 120x160, depending on the webcam used for recording.

## Conclusion: 

<div align="justify"> After conducting extensive experiments, we can conclude that Model 8, utilizing a combination of CNN and LSTM, exhibited strong performance. So we can select it as our final selection.</br>

- Model 8 achieves a commendable Training Accuracy of 98% and Validation Accuracy of 89%, indicating its capability to generalize well to unseen data.

- Model 8 has fewer parameters compared to other models, while maintaining strong performance.

- The optimal weights for the CNN-LSTM model are stored in file "model-00017-0.09221-0.97813-0.27520-0.89000" . These weights were utilized for testing the model's performance.</div>

## Technologies Used:
- Python, version 3 
- NumPy for numerical computations
- Matplotlib and seaborn for data visualization
- Pandas for data manipulation
- Statsmodels for statistical modeling
- Sklearn for machine learning tasks
- Tensorflow, keras, augmentor for deep learning 
- Jupyter Notebook for interactive analysis

## References:
- Python documentations
- Tensorflow, keras, augmentor documentations
- Stack Overflow


## Contact Information:
Created by https://github.com/Erkhanal - feel free to contact!
