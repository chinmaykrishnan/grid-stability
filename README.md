# grid-stability
A simple binary classification problem.

The dataset was taken from the UCI Machine learning repository and can be found [here](https://archive.ics.uci.edu/ml/datasets/Electrical+Grid+Stability+Simulated+Data+). The description of the data has also been provided by the provider of the dataset.
There are two notebooks, ANN.ipynb and ML.ipynb. The ANN notebook details the classification problem solved using a simple Sequential model, implemented using keras. The accuracy obtained was ~99% on the training set and ~96% on the test set. The other notebook shows the problem solved using 5 conventional machine learning approaches namely, SVM, decision tree, logistic regression, naive Bayes, random forest and KNN classifier. All of the models(except KNN), gave us accuracies over 90%, among which the decision tree classifer and random forest classifier performed the best, with an accuracy of 99.95%.

Notes:
- The code for plotting the confusion matrices have been borrowed from a Kaggle notebook provided by George Fisher, which can be found [here](https://www.kaggle.com/grfiv4/plot-a-confusion-matrix)

