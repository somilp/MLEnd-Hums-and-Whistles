# MLEnd Hums and Whistles
* "Basic" and "Advanced" solutions, based on the MLEnd Hums and Whistles dataset (https://www.kaggle.com/datasets/jesusrequena/mlend-hums-and-whistles)
* Cleaned and labelled data according to the problem being solved
* Both involved experimentation with many different features extracted from the audio domain
* Feature selection using the random forest method
* Explored extracted features visually to anticipiate model performance
* Utilised several machine learning models (described below)
* Hyperparameter tuning using grid search technique, k-fold cross validator
* Evaluated model performance using confusion matrices and training/validation accuracies

## Basic Solution
* Predict the labels of audio segments from the Harry Potter theme song and The Imperial March (Star Wars)
* Models used: logistic regression, support vector machine, k-nearest neighbour and random forest classifier

## Advanced Solution
* Predicting the gender of participant, using the hum interpretations across a variety of songs
* Models used: logistic regression, support vector machine, k-nearest neighbour and guassian mixture model (GMM)
* Utilised bayesian information criterion to evaluate hyperparameter selection for the GMM

