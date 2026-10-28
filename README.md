# Decision Tree & Random Forest Regression

## Project Overview

This project explores tree-based machine learning algorithms for predicting median house values.

The objective is to understand how Decision Trees make predictions through feature-based splits and how Random Forest combines multiple trees to produce predictions.

## Dataset

**housing.csv**

The dataset includes housing characteristics such as location, housing age, room counts, population, households, and median income.

**Target Variable:** Median house value

## Tools & Libraries

Python | Pandas | Matplotlib | Scikit-learn

## Methodology

### 1. Data Preparation

- Loaded and inspected the housing dataset.
- Removed missing values.
- Selected numerical predictor variables.
- Split the dataset into training and testing sets.

### 2. Decision Tree Regression

Trained a Decision Tree Regressor with controlled tree depth and minimum sample requirements.

Explored:

- Root nodes and decision nodes
- Leaf nodes
- Feature-based splitting
- Overfitting and underfitting

### 3. Model Evaluation

Generated predictions for training and testing data.

Evaluated performance using:

- R² Score
- Mean Absolute Error (MAE)

### 4. Feature Importance

Analyzed the contribution of individual features to the model's predictions.

Visualized the decision tree to better understand its structure and decision-making process.

### 5. Random Forest Regression

Implemented Random Forest Regression to explore ensemble learning.

Random Forest combines predictions from multiple decision trees to produce a final prediction.

Compared model performance and examined Random Forest feature importance.

## Key Takeaways

- Decision Trees make predictions through a series of feature-based decisions.
- Tree depth and minimum sample settings influence model complexity.
- Random Forest combines multiple trees to reduce reliance on a single tree.
- Feature importance provides insight into which variables contribute most to predictions.
- Comparing training and testing metrics helps identify potential overfitting.

## Learning Outcomes

- Decision Tree Regression
- Random Forest Regression
- Ensemble learning
- Model evaluation
- Feature importance analysis
- Decision tree visualization

## Future Improvements

- Perform hyperparameter tuning.
- Compare both models using a consolidated performance table.
- Explore additional ensemble methods.
- Apply cross-validation for more reliable evaluation.
