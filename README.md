# Identifying-safe-loans-with-decision-trees

The project is based on the [Classification](https://www.coursera.org/learn/ml-classification/home/welcome) course provided by UW on Coursera.

---
```built-in decision-trees```

In this notebook, data from the LendingClub were used to predict whether a loan will be paid off in full or the loan will be charged off and possibly go into default:
* Use SFrames to do some feature engineering.
* Train a decision-tree on the LendingClub dataset.
* Visualize the tree.
* Predict whether a loan will default along with prediction probabilities (on a validation set).
* Train a complex tree model and compare it to simple tree model.

---
```self-coded decision-trees```

The goal of this notebook is to implement self-coded binary decision tree classifier:
* Use SFrames to do some feature engineering.
* Transform categorical variables into binary variables.
* Write a function to compute the number of misclassified examples in an intermediate node.
* Write a function to find the best feature to split on.
* Build a binary decision tree from scratch.
* Make predictions using the decision tree.
* Evaluate the accuracy of the decision tree.
* Visualize the decision at the root node.
