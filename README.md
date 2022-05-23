# Neural_Network_Charity_Analysis

## Overview
The purpose of the analysis is to create a binary classifier that is capable of predicting whether applicants will be successful if funded by Alphabet Soup.

## Results
### Data Preprocessing
- What variable(s) are considered the target(s) for your model?
The target for the model was the answer to if the application would be successful

- What variable(s) are considered to be the features for your model?
The features for the model were information such as the following:
1. How much was asked for
2. Application Type
3. Income Amount
4. Special Considerations

- What variable(s) are neither targets nor features, and should be removed from the input data?
The variables that were neight targets nor features are the following:
1. Affiliation
2. Use Case
3. Organization
4. Classification


### Compiling, Training, and Evaluating the Model
- How many neurons, layers, and activation functions did you select for your neural network model, and why?
I selected 3 hidden layers, with a decreasing amount of neurons from 100 to 40 to 10 in the consecutive layers. I did this because it was important that the machine learning model was able to handle the diverse inputs efficiently, and then specify an expectation due to the more minor variations later on in the processing. 

- Were you able to achieve the target model performance?
I was not quite able to achieve the target model performance of 75%. After three attempts, my best accuracy was .7227, which is roughly 72%

-What steps did you take to try and increase model performance?
I attempted to increase the model performance by increasing the number of layers and also adding more neurons to the layers. 

## Summary

The overall results of the deep learning model show that with a clean data set, careful consideration of target and feature variables, and a strong setup of the model, deep learning can be quite helpful to accurately predict outcomes. While an accuracy of nearly 75% is commendable, note that even this model is not a perfect predictor of success. However, through the power of deep learning, what would otherwise take a lifetime to know can be predicted with a pretty strong degree of accuracy. Being able to accurately predict results without overfitting is difficult, and the results that were achieved are impressive given the complex nature of the data.