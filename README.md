1. This is the description file for the code of the data mining project.
2. In this project code, I completed the training of the model based on the given training sets and output the predicted results based on the test set.
3. The final accuracy of my training set is 0.978 and the f1-score is 0.972.
4. This code can be run directly and the results will output the accuracy and f1-score for each model and will generate a csv file containing the predictions.

Dara pre-processing:

1. I read the files "train.csv" and "add_train.csv" and used them together as a training set.
2. I performed outlier detection and replacement operations and used category-based median interpolation for numeric data. For nominal type data, I used the "mode".
3. Standardization of data
4. Training model. hyperparameters n_neighbors=7 for KNN model.
5. Predictions are made on the test set using integrated models, selected dt, rf, knn, bayes models, and hard voting methods.
