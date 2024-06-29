# Classification with a Decision Tree

## Overview

The goal of this exercise is to practice using Decision Trees for classification using sklearn in Python. You will visualize decision boundaries, compute accuracy scores, and analyze feature importance using Decision Trees of varying depths.

## Instructions

1. **Data Preparation:**
   - Read the train and test data files as Pandas data frames.
   - Use `minority` and `bachelor` as predictor variables (`X`) and `won` as the response (`y`).

2. **Initial Decision Trees:**
   - Fit a decision tree classifier of depth 2 and another of depth 10 on the training data.
   - Visualize the decision boundary of these classifiers using the `plot_boundary` function.

3. **Increasing Predictor Variables:**
   - Increase the number of predictor variables as specified in the scaffold (additional details needed).

4. **More Decision Trees:**
   - Initialize decision tree classifiers of depths 2, 10, and 15.
   - Fit each model on the training data.
   - Compute and compare the train and test accuracy scores for each classifier.

5. **Feature Importance:**
   - Utilize helper code to examine the feature importance of predictors from the decision tree of depth 15.

## Implementation Details

- **Decision Tree Classifier:** Use `sklearn.tree.DecisionTreeClassifier()` to generate decision tree classifiers.
- **Accuracy Scores:** Use `classifier.score(X, y)` to compute accuracy classification scores.
- **Feature Importance:** After fitting the decision tree, use `classifier.feature_importances_` to inspect feature importance.

