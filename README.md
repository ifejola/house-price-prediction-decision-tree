# house-price-prediction-decision-tree
Predicting housing prices using Decision Tree Regressor with hyperparameter tuning, model evaluation, and feature importance analysis
# House Price Prediction Using Decision Tree Regressor

## Overview
This project builds a Decision Tree regression model to predict housing prices and analyze how different features influence predictions.

The goal is to compare model performance, understand feature importance, and visualize how decisions are made within the model.

---

## Dataset
The dataset contains 20,000+ housing records with features including:

- Longitude & Latitude
- Housing Median Age
- Total Rooms & Bedrooms
- Population & Households
- Median Income
- Median House Value (target variable)

---

## Tools & Libraries
- Python
- pandas
- numpy
- scikit-learn
- matplotlib

---

## Data Preparation

- Removed missing values
- Selected numerical features for modeling
- Split data into training (80%) and testing (20%)

---

## Model Building

- Used `DecisionTreeRegressor` from scikit-learn
- Tuned key hyperparameters:
  - `max_depth = 10`
  - `min_samples_split = 20`
  - `min_samples_leaf = 10`
- Set `random_state = 42` for reproducibility

---

## Model Evaluation

### Training Performance:
- R² Score: 0.805  
- MAE: ~34,361  

### Testing Performance:
- R² Score: 0.731  
- MAE: ~40,685  

### Interpretation:
- Model performs well on training data
- Slight drop on test data indicates minor overfitting
- Still generalizes well overall

---

## Feature Importance

Top contributing features:
- Median Income (most important)
- Longitude
- Latitude

Lower impact:
- Total rooms
- Bedrooms
- Households

---

## Visualization

- Plotted feature importance rankings
- Visualized decision tree structure (first 3 levels)
- Observed how model splits data based on key features

---

## Key Insights

- Median income is the strongest predictor of house prices  
- Location plays a significant role in determining value  
- Decision trees provide clear interpretability compared to linear models  

---

## Future Improvements

- Tune hyperparameters using GridSearchCV
- Compare with Random Forest / Gradient Boosting
- Apply feature scaling and engineering
- Prune tree to reduce overfitting

---

## Conclusion

The Decision Tree model provides strong predictive performance and valuable interpretability, making it useful for understanding key drivers of housing prices.
