Here we build a movie recommendation system that recommends movies to users based on their preferences. we decided to use three different models to make predictions: a decision tree classifier, a random forest classifier, and a gradient boosting classifier.

By using ensemble model that combines the predictions of these three models to make the final recommendation.

We could train each of these models on the same training dataset of movies and user ratings, and then, combine the output from each model using the majority voting rule to make the final recommendation.

We can then validate the performance of the model on a separate validation set or by doing cross-validation.
