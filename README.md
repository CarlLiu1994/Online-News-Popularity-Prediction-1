# Online-News-Popularity-Prediction
*This is a group project done by Hanqiu Yang, Haoyun Peng, Carl liu and Chuxin Piao under guidance from Prof Zhenglin Qi (GWU Decision Science Department)

## Dataset Review
Our group chose to use the Online News Popularity Data Set from UCI Machine Learning Repository:https://archive.ics.uci.edu/ml/datasets/Online+News+Popularity

This dataset summarizes a heterogeneous set of features about articles published by Mashable in a period of two years. The goal is to predict the number of shares in social networks (popularity). 

## Problem Description
Our main goal is to predict the popularity of news or articles through the given variables using different algorithms. 

During this period, we tried to use regression algorithms to predict the number of shares. Unfortunately, every model we tried does not perform well on predicting the number of shares: the evaluation metrics, R squared is pretty close to 0, meaning that the response cannot be explained by our models at all, and the lowest test RMSE we achieved is greater than 7000. 

Besides, the higher the Regularization parameter was, the better the model performs, which indicates that the model did such a poor job that even using the mean of the number of shares to make predictions can result in a better outcome. 
Instead, we convert the regression problem into a classification problem  and will develop some learning algorithms that classify news as popular or unpopular.

## Algorithms and Performance Overview
<img width="853" alt="WX20200706-153706@2x" src="https://user-images.githubusercontent.com/55762821/86633437-a6a83180-bf9e-11ea-8d76-205028dedda4.png">


