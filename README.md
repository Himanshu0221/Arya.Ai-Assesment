# Arya.ai Assignment 

##### Objective - To carry out binary classification on provided data


## Files

 - [Jupter notebook](https://github.com/Himanshu0221/Arya.Ai-Assesment/blob/main/Arya.ai.ipynb)
 - [Predictions of Test Data](https://github.com/Himanshu0221/Arya.Ai-Assesment/blob/main/test_data_pred.csv)
 - [Dependencies](https://github.com/Himanshu0221/Arya.Ai-Assesment/blob/main/dependencies.txt)

## Dataset
Train Dataset Shape  (3910,57), 

Test Dataset Shape (691,57)

  
## Approach & Key Steps

### Data Analysis
Load the training and testing dataset from csv file and figure out what kind of information is present in it.

Check if the data set is balanced or not

Checking for missing values 

Find out the correlation between multiple features present in dataset

### Feature Selection
Splitting the data into training and validation dataset

Feature selection using suitable technique

Scaling the data

### Model Building and selection

Select several classification models to test their performance on the given training data set.

find their classification performance to check which model's performance is better.

Select the model with best performance for the final training.

Calculate the training accuracy and validation accuracy of the model. Also calculate the confusion matrix to get a better understanding of the performance of the model.

After the training process, make the prediction on the test data set using the trained model.



###  Performance of model 
All the pre_processing, feature selection has been done in a single notebook, therefore to check the performance of model run the code, there we can see the desired results

Validation metrics

Accuracy : 0.948, Recall : 0.928, Precission : 0.938, AUC : 0.987, F-Beta Score : 0.933


 Arya.Ai-Assesment
