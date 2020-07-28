# Rock_Paper_Scissors_CNN

[Dataset](https://www.kaggle.com/drgfreeman/rockpaperscissors)

# What is this project about
I wanted to created simple cnn that can identify 3 hand gestures(rock, paper, scissors) from pictures.

# Data
Data consist of about **2600 images** in green screen. I used **20%** of it for **validation**. 

# Model
Model has **3 convolution and pooling layers** with changing filter and kernel sizes, **30% dropout layer** to prevent overfitting, **1 hidden layer** of 64 nodes and an **output layer** with softmax activation function.

# Results
Model performed pretty well with accuracy over 90%. I also tested 2 images from different dataset and they were predicted correctly.




