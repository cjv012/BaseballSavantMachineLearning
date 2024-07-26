# CSCI 349 Final Project

Team Name: Baseball Savants

Team Members: Connor Vucovich, Doruk Ozar, and Taylor Lamantia

This project attempts to take existing pitch data from the MLB, Major League Baseball,to model its effectiveness in a particular situation given its characteristics. A possible use of this model would be to determine what pitches should be thrown by the pitcher in what situation in order to garner the best possible results on the field.

The dataset can be found at: https://baseballsavant.mlb.com/statcast_search

# DataPrep_EDA.ipynb
This file discusses the problem being worked on, describes the data involved in the problem, and handles the preprocessing/data exploration (EDA). The goals and modeling methods to be used are discussed here.

# Modeling.ipynb
This notebook explores the development of predictive models. In this case, a neural network and decision tree (both with cross validation and grid search for parameter optimization) are trained and tested. The neural network performs better with an 86.22% accuracy.

# Final_Report.ipynb
This notebook includes the final most important results received from the data. It includes the most important results from the initial EDA, the neural network training, and the performance results of the model. The model is then used to predict the results for each pitch type that a particular pitcher uses. 