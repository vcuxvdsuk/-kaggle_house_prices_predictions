
# kaggle house prices predictions
Mar 2024 - Apr 2024Mar 2024 - Apr 2024
## first part
In this competition I built a model to predict house prices in Ames, Iowa.

I will try to predict house prices using linear regression. I will use the loss, features selecting, hyperparameters and various regularizations to find the model that will give the best score

## second part
I built upon the foundation of part 1. On top of those foundations, I tested four models:

LWLR - Locally Weighted Linear Regression
KNN – K Nearest Neighbors
Decision Trees
SVM – Support Vector Machines

After the "normal" models, I tested three ensemble models:

BaggingRegressor
AdaBoostRegressor
RandomForestRegressor
On top of it, I tried to combine them using voting with the help of:

VotingRegressor
Furthermore, I used PCA on some of the models to try to conclude if it would be beneficial to do so, but it seems to not improve the score, so I didn't use it for the final model.

The final model that was chosen was the Bagging Regressor, although I thought that the equal voting ensemble model, which takes into consideration the result of all the ensemble models and gives all the models the same voting power, has the most potential.
