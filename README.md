# Quora-question-pair-similarity
Quora question pair similarity is a binary classification problem, for a given pair of questions we need to predict if they are duplicate or not.
Metric's considered: Log-loss and Binary confusion metrics
Applied Logistic Regression and Linear SVM with simple TF-IDF vectorization.
Hyperparameter tuning done on XGBoost model using Random Search to reduce the log-loss.
XGBoost model with test log-loss score is 0.435
