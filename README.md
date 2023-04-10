Module 13 Challenge
Module 13 challenge repository containing a model to predict whether applicants will be successful if funded by Alphabet Soup, a venture capital firm, based on a variety of categorical and numerical features. Initially a sequential model with two dense hidden layers was created and assessed. Then, potential optimization was evaluated by creating two similar alternative models:

A 3rd dense layer was added
More hidden nodes were used as well
The original model had the best accuracy score of the three. 
The second alternative had very similar accuracy but higher loss.
summary of the results are below and can also be found in the jupyter notebook.

Original - Loss: 0.591, Accuracy: 0.727
Alternative #1 - Loss: 0.599, Accuracy: 0.704
Alternative #2 - Loss: Loss: 0.630, Accuracy: 0.725
Technologies
This project leverages Python 3.7 in Jupyter Lab with the following packages:

pandas - For financial data analysis tools
numpy - For numerical functions to aid in financial calculations
scikit-learn - To create models for fitting data and making predictions
tensorflow - To build, deploy and assess machine learning models
pathlib - to assist in handling files and paths
