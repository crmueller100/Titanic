# Titanic
The goal of this competition is to identify which passengers of the RMS Titanic survived the crash. The likelihood of survival depended on multiple factors including gender, age, location of cabin on the ship, which class ticket they bought, etc. Approximately 2/3 of the passenger data provided has whether or not that passenger survived. This data is used to create a binary classification model that can be applied to the other 1/3 of the passengers to determine if they survived. The submission file is simply each passengerID and whether or not they have been estimated to survive. Kaggle evaluates each submission as a percentage of how many passengers had their fate correctly predicted. More information can be found on Kaggle's website: https://www.kaggle.com/c/titanic

## Setup
I programmed this solution by running Python in a Jupyter Notebook. For data manipulation, I made use of Python's pandas library. For visualization, the pandas and seaborn libraries were implemented. For the logistic regression model used to classify the passengers in the test data set, the sklearn library was implemented

## Motivation
The motivation behind doing this project is my desire to increase my data science skills. I have a familiarity with machine learning concepts, but doing an actual competition and applying these concepts is the best way to learn data science skills. Through this project, I hope to increase my knowledge of algorithms and programming skills. It is also an exercise to help me learn to use with my github account. 

## Implementation
My first attempt utilized the Logistic Regression linear model from the sklearn class.

### Improvements to be made
Eventually, I would like to test several different machine learning classification models and compare their accuracy. I am open to any and all criticism.

