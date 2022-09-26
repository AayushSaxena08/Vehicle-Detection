# Predicting the price of Vehicle

### Problem Statement: 

Using a dataset of (301,9) we have to predict the selling price of the second-hand vehicles sold

### Solution: 

Creating a Pandas Dataframe to read the data. And apply Feature Engineering techniques like One-Hot Encoding to check the correlation between dependent and independent variables.

`Random Forest` is a popular supervised machine learning algorithm which is used for both Classification and Regression problems. It is based on the concept of ensemble learning, which is a process of combining multiple classifiers to solve a complex problem and to improve the performance of the model.

The Working process can be explained in the below steps:

1. Select random K data points from the training set.
2. Build the decision trees associated with the selected data points (Subsets).
3. Choose the number N for decision trees that you want to build.
4. Repeat Step 1 & 2.
5. For new data points, find the predictions of each decision tree, and assign the new data points to the category that wins the majority votes.
