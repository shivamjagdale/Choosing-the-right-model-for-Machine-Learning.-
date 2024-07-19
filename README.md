# Choosing-the-right-model-for-Machine-Learning.-
Choosing the right model for Machine Learning. 

Here we are building a Machine Learning models and testing out all the different models to see which one performs the best.

Here we will 1st do it with cross_val_score and with out giving specific hyper parameters to each of the model.
Then we will do the same process but by giving hyperparameters and here we will use GridSearchCV instead of cross_val_score

Now the best model we got here is RandomForestClassifier(random_state=0) and it's parameters as {'n_estimators': 100}.
