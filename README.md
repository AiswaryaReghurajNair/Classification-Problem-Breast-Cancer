# Classification-Problem-Breast-Cancer
## 1. Loading and Preprocessing
Steps:
Load Dataset: Use the load_breast_cancer function from sklearn.datasets.
Handle Missing Values: The dataset does not have missing values, but we would add a placeholder step to handle missing values if they were present.
Feature Scaling: Scale features using StandardScaler from sklearn.preprocessing to standardize the data. Feature scaling ensures all features have equal importance in distance-based algorithms like SVM and k-NN.
## 2.Algorithms:
# Logistic Regression:
Logistic regression models the probability of the default class using a sigmoid function.
Suitable for binary classification tasks like breast cancer prediction due to its simplicity and efficiency.

# Decision Tree Classifier:
Builds a tree where each node splits the data based on feature values to classify the data into subsets.
Suitable for its interpretability and ability to handle non-linear relationships.

# Random Forest Classifier:
An ensemble of decision trees that improves performance by averaging multiple trees.
Suitable for its robustness against overfitting compared to single decision trees.

# Support Vector Machine (SVM):
Finds the hyperplane that best separates the classes in feature space.
Suitable for datasets with clear class separation and smaller feature sizes.

# k-Nearest Neighbors (k-NN):
Classifies data points based on the majority class of their nearest neighbors.
Suitable for simple datasets but may struggle with high-dimensional data.

## 3.Model Comparison
# Steps:
# Split Dataset: Divide the data into training and testing sets using "train_test_split" from "sklearn.model_selection".
# Model Evaluation:
Evaluate models using metrics like accuracy, precision, recall, or F1-score.
Use classification_report for a detailed comparison.
# Result Comparison:
Rank algorithms based on performance metrics.
Identify which algorithm performs best and which performs worst.
Best Performing Model: SVM with Accuracy = 0.98
Worst Performing Model: Decision Tree with Accuracy = 0.95
