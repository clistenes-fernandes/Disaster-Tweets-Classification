# Disaster-Tweets-Classification
## Classification of disaster tweets using Convolutional and Recurrent Neural Network

This project was inspired by a Kaggle competition that asked the participants try to predict either a tweeter was real about a disaster or not. The platform provided the data for training and also the test data. 
So, after sending the predictions to Kaggle I decided to post some result on Github using the training dataset, splitting into train and test.

To complete this task was used the model proposed by [Wang et al. 2019](https://ieeexplore.ieee.org/document/8852406), that used a Convolutional Neural Network and a LSTM Recurrent Neural Network to perform a classification task, the model architecture can be seen on figures below, taken from the mentioned paper:

![Model Architecture](/images/model_architecture.JPG)
![Model Architecture](/images/convolutional_architecture.JPG)

On this project was used the same CNN proposed on the paper but instead of using a LSTM recurrent layer was decided to use Gated Recurrent Unit - GRU.

This model returned a low rate of wrong classifications, with only 16 wrong predictions - 3 false-negative and 13 false-positive.


