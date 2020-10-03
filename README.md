# Data-Science-Portfolio

## Stock-Predictor

The dataset used consists of 50 major companies daily stock prices downloaded from Yahoo Finance from a period of 2/8/2013 to 2/7/2018.
The closing stock prices of these companies for days in which the stock market was open were used for the analysis.
The main objective is to predict the future stock price for Activision Blizzard Inc. (ATVI) at day t+1 given the 
past evolution of 50 stocks observed up to time "t".

It is essential that the number of  **hidden layer neurons "h"**  needs to be selected very carefully. This is because selecting a 
value of h that is large could result in the model performing well on the training set but poorly on the test set. This situation is known as overfitting. 
Selecting a value of h that is small could also lead to a weak architecture and consequently underfit without capacity to generalize. As a result, it is essential 
to have a value that is stable for both the training and test set. The PCA analysis was performed on the input data to estimate the value of h that will be
used to design the architecture of the MLP.  

## Font-Predictor
The task is to calssify different fonts. The data was cleaned and then KNN was applied for classification  for different values of the hyperparameter. 
In order to improve the accuracy tweighted KNN was used with the best value of hyperparameter obtained from previous best model. The new solution improved accuracy from ~78% to ~90%



