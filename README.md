# Optimization-of-Gradient-Boosting-Classifier-Parameters-for-Wine-Dataset-using-GridSearchCV

This repository contains code for optimizing a Gradient Boosting Classifier model using GridSearchCV. It includes hyperparameter tuning, evaluation metrics, and visualizations.

## Introduction

Gradient Boosting Classifier is a powerful machine learning algorithm that combines weak predictive models, typically decision trees, to create a stronger model. This code demonstrates how to optimize the Gradient Boosting Classifier model using GridSearchCV, a technique that exhaustively searches for the best hyperparameters for the model.

## Code Explanation

The code consists of the following main parts:

- Importing the required libraries: The necessary libraries for the code are imported, including numpy, scikit-learn, matplotlib, and seaborn.

- Defining the `optimize_model` function: This function performs hyperparameter tuning on the given model using GridSearchCV. It splits the data into training and testing sets, performs grid search using the provided parameter grid, finds the optimal parameters, evaluates the model's performance using classification report and confusion matrix, and visualizes the results.

- Loading the wine dataset: The code loads the wine dataset from the scikit-learn datasets module. This dataset is a multi-class classification problem where the goal is to predict the type of wine based on its features.

- Defining the Gradient Boosting Classifier model: The code creates an instance of the GradientBoostingClassifier class, which will be optimized using GridSearchCV.

- Defining the parameter grid: The parameter grid specifies the hyperparameters to be tuned. In this example, the learning rate, subsample, number of estimators, and maximum depth are explored.

- Calling the `optimize_model` function: The `optimize_model` function is called with the Gradient Boosting Classifier model, parameter grid, and the wine dataset features and labels as inputs.

## Installation

To run the code, you need to have Python and the required libraries installed. Follow the steps below to set up the environment:

1. Clone the repository:

   ```bash
   git clone [https://github.com/your-username/your-repo.git](https://github.com/UbaidullahAmjad/Optimizing-Gradient-Boosting-Classifier-Parameters-for-Wine-Classification/tree/main)
