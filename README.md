# Neural_Network_Charity_Analysis

## Overview of Analysis

The purpose of this analysis is to utilize machine learning and neural networks to create a binary classifier that can predict whether applicants will be successful if funded by the company Alphabet Soup. The data set contains 34,000 organizations compiled by Alphabet Soup's business team that have previously received funding by the company over the years. The first step in the analysis is to preprocess the data in order to compile, train, and evaluate the neural network model. The next step is to design a neural network/deep learning model to create a binary classification model that can predict if an organization funded by Alphabet Soup will be successful. The last step of the analysis is to optimize the model for a better accuracy performance. 

## Results

### Data Preprocessing

#### What variable(s) are considered the target(s) for your model?

The variable that is considered the target for the model is the "Is Successful" value. 

#### What variable(s) are considered to be the features for your model?

The variables that are considered to be the features for the model are application type, affiliation, classification, organization, status, income, ask amount, and special considerations.

What variable(s) are neither targets nor features, and should be removed from the input data?
The variable that are neither targets nor features that should be removed from the input data is the use cases value. 

### Compiling, Training, and Evaluating the Model

#### How many neurons, layers, and activation functions did you select for your neural network model, and why?

For the neural network model, three layers were used. The first layer contained 80 neurons, the second layer contained 30 neurons, and the last layer contained 10 neurons. The activation function that was used was the 'relu' function. I tried this model because the two layer model with 80 and 30 nuerons respectively did not produce a great accuracy score of only 56%. I also tried to increase the epochs from 100 to 200 in efforts to optimize performance. 

#### Were you able to achieve the target model performance?

I was unforuntately not able to achieve the target model performance. I was, however, able to raise the accuracy score from 56% to 64%. 

#### What steps did you take to try and increase model performance?

The steps I took to try and increase model performance were the addition of more layers, increase amount of neurons, an increase in the number of epochs, and removing features. 

## Summary

Overall, the results of the model produced an accuracy score of 64% and a loss of 1.66. Although this is not ideal, removing features did raise the accuracy score from 56% to 64%. To raise this model to an accuracy score of 75% or higher, I suggest removing more features and to use a different activation function when training the model. 

<img width="731" alt="Screen Shot 2021-04-18 at 11 57 32 AM" src="https://user-images.githubusercontent.com/74932178/115152050-8c2ada80-a03d-11eb-8128-bba8f5408a46.png">




