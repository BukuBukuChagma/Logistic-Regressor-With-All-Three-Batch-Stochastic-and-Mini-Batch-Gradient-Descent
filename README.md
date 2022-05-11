# Logestic-Regressor-With-All-Three-Batch-Stochastic-and-Mini-Batch-Gradient-Descent
I have implemented Logestic Regression for Binary classification from scratch with all three types of gradient descent.

===> main.ipynb is the notebook file that contains the implementation of the Logestic Regressor
===> nba_logreg.csv is the dataset on which the Regressor have been implemented, trained and then validated.

The code is quite generic, and can easily be modefied to fit on other binary Classifications datasets, tho the 'Data Cleaning' section of the notebook
would have to be modefied according to the dataset. 

#NOTE: This is for binary class problems only.

Libraries used:
==> Sci-kit Learn: For train_test_splits, confusion_matrix, classification_report and accuracy report
==> Numpy: Since numpy calculations are faster, so all calculations are done with numpy
==> Pandas: To read the csv into a dataframe type
==> Matplotlib and Seaborn: For plotting graphs and heatmaps
==> Random: To intialize weights randomly at beginning 
