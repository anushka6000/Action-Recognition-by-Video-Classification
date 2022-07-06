# Action-Recognition-by-Video-Classification
The repository contains the google colab notebook of Action Recognition task using a CNN-RNN architecture

# Dataset
In order to keep the runtime relatively short, a subsampled version of the original UCF101 dataset is used. The link to the dataset is here: https://www.crcv.ucf.edu/data/UCF101.php

# Task and Result
The task was to classify the videos present in the dataset into 5 action classes which were: 'CricketShot', 'PlayingCello', 'Punch', 'ShavingBeard', 'TennisSwing'. 
An organised series of frames makes up a video. The order of the frames carries the temporal information, and each frame contains spatial information. A  hybrid architecture that combines recurrent layers and convolutions (for spatial processing) to capture both of these elements (for temporal processing) is employed here to create a video classifier. Implemented the popular CNN_RNN architecture consisting of a GRU-layered recurrent neural network (RNN) and an InceptionV3 convolutional neural network (CNN) specifically.

The model obtained overall test accuracy of 44.2%. A sample video was passed through the model and it correctly recognized the action represented in the video. A picture of the result is attached below:

<img width="510" alt="image" src="https://user-images.githubusercontent.com/108798675/177535952-77b69ca2-1ab2-4df6-8eb7-77b58495e416.png">

