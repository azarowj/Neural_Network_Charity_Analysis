# Neural_Network_Charity_Analysis

## Overview

- The purpose of this analysis is to use machine learning and neural networks to create a binary classifier. We are predicting whether or not loan applicants will be successful if they are given the loan. We have been given an CSV file containing more than 34,000 organizations that have received funding over the years. 

## Results

- Data Preprocessing
    - The target variable in our analysis is "IS_SUCCESSFUL"
    - The feature variables in our analysis are Application Type, Affiliation, Classification, Use Case, Organization, Status, Income Amount, Special Considerations, and Ask Amount.
    - The variables that are not considered to be feature or target variables are "EIN" and Name.


- Compiling, Training, and Evaluating the Model
  - I initalliy used two layers in the fuction. I used a relu function in the hidden layers and a sigmoid function in the output layer.
  - I was not able to achieve the target performance
  - In my first attempt at optimizing the model, I removed the columns for Status and Special Considerations. I also added a third hidden layer.
  - In my second attempt at optimzing the model, I left the changes from the first attempt. I also increased the number of buckets for the Classification feature and increased the number of neurons in each hidden layer.
  - In the third attempt, I left the changes from the previous two attempts. I decreased the number of buckest for the Application feature. I also changed the function in the hidden layers from relu to tanh.

## Summary
