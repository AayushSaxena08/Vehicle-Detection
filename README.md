# Vehicle-Detection
Using Random Forest Regressor and tuning the hyperparameters

Creating a Pandas Dataframe to read the data. And apply One-Hot Encoding to check the correlation between dependent and independent values and find the correlation between them. Random Forest is a popular machine learning algorithm that belongs to the supervised learning technique. It can be used for both Classification and Regression problems in ML. It is based on the concept of ensemble learning, which is a process of combining multiple classifiers to solve a complex problem and to improve the performance of the model.

The Working process can be explained in the below steps:

Step-1: Select random K data points from the training set.
Step-2: Build the decision trees associated with the selected data points (Subsets).
Step-3: Choose the number N for decision trees that you want to build.
Step-4: Repeat Step 1 & 2.
Step-5: For new data points, find the predictions of each decision tree, and assign the new data points to the category that wins the majority votes.
