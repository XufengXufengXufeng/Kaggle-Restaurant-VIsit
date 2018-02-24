# Kaggle-Restaurant-VIsit
My solution to the Kaggle recruit restaurant visit forcast competition. It has a few boosting models and a nn model with entity embedding implemented with pytorch.

## Notebooks description:
the boost models notebook has catboost, xgboost and lightgbm models with customized grid-search method.

the good features notebook has wonderful feature engineering methods that I learned throughout the competition.

the nn model with cat and nn model with dayofquarter notebooks are my attempts to create an easy nn with embedding layers.

the nn model with kernel data has the refined networks. I also tried to compare dropout and batch normalization, as well as 1d convolution layers. I added custmized learning rate modual with which I can change learning rate on the go. I wrote my own batches, as the model requires multiples inputs (categorical and numerical). I don't have a GPU computer, so for performance reason, I wrote my own loss recorders that randomly select parts of validation data on every round of training.

## Files missing
There are several files that exceed 100 mega bytes which couldn't be pushed to the github. Meanwhile, this repository is a convenient code notes loaction for my own use, as the nn class is quite complex to format.
