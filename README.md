# AN2DL_Challenges_2021
Repository of the two challenges made during the course of Artifical Neural Networks and Deep Learning at Politecinco di Milano in 2021

**Image classification**

The first challenge concerns the classification of images, in particular it was required to classify images of leafs (like the ones in the example images below), which are divided into categories according to the species of the plant to which they belong. Being a classification problem, given an image, the goal is to predict the correct class label.

![leaves_screen](https://user-images.githubusercontent.com/49268333/147560862-9bf7ada5-3a71-4d42-a476-60e48649b8cd.PNG)

In the folder 'image_classification' the notebooks with the models used are listed.
We explored two solutions to address this problem, the first by creating a CNN architecture from scratch, the second using trasnfer learning and fine tuning of pre-trained CNN networks (such as VGG or Xception).
An in-depth description of these models and the solutions adopted in this challenge can be found in the pdf 'Report Image Classification'. 
We finished the challenge with 90% accuracy on the test set

**Timeseries Forecasting**

The second challenge concerns Timeseries forecasting, it was  required to predict future samples of a multivariate time series. The goal was to design and implement forecasting models to learn how to exploit past observations in the input sequence to correctly predict the future. 

We have faced this problem with two different approaches: direct and autoregressive. For each of the two we have experimented with different recurrent architectures (LSTM, GRU and Bidirectional, 1DConv).
An in-depth analysis of all experiments can be found in the pdf 'Report Timeseries Forecasting'.
We reached 3.6 as best RMSE on the test set.
