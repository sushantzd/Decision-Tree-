# Dataset Classification with Decision Tree



This project explores the popular Iris dataset to classify iris species using a Decision Tree Classifier. In this project, post-pruning techniques were applied to enhance the model's performance, and the tree was visualized to understand the decision-making process. Additionally, Grid Search Cross-Validation (CV) was used to optimize hyperparameters and achieve the best model accuracy.

Project Overview

* Dataset: Iris dataset (from sklearn.datasets)
  
* Objective: Classify iris species based on sepal and petal measurements.
  
* Model: Decision Tree Classifier

  
Key Techniques:
* Post-pruning to reduce overfitting.

* Tree visualization using sklearn.tree.
  
* Hyperparameter tuning with Grid Search CV.
  
* Model evaluation using a Confusion Matrix and accuracy score.


* Project Workflow

Data Loading: Loaded the Iris dataset and divided it into features and labels.
Model Training:
Built an initial Decision Tree Classifier.
Applied post-pruning techniques to optimize the model by reducing unnecessary splits.
Tree Visualization:
Visualized the decision tree to interpret how the classifier splits data across different features.
Hyperparameter Tuning:
Used Grid Search CV to find the best parameters for maximum accuracy.
Evaluation:
Calculated the accuracy score of the model.
Created a Confusion Matrix to visualize model performance across different classes.
Key Results

Accuracy Score: Achieved an accuracy score of XX% after tuning.
Best Parameters: The optimal parameters found with Grid Search CV are:
python
Copy code
{
    "criterion": "gini",         # or "entropy"
    "max_depth": optimal_depth,  # Best depth from Grid Search
    "min_samples_split": optimal_split_value
}
Confusion Matrix: Demonstrated the model's effectiveness in classifying each species accurately.
Prerequisites

To run the project, install the following libraries:

bash
Copy code
pip install numpy pandas matplotlib scikit-learn
How to Run

