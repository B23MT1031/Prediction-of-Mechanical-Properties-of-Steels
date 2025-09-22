# Prediction-of-Mechanical-Properties-of-Steels
Machine learning project for predicting fatigue levels from dataset features. Includes data preprocessing, regression models (Linear Regression, Decision Trees, etc.), cross-validation, and evaluation using Mean Squared Error. Implemented in Python with scikit-learn.

## Project Structure
- `code.ipynb` : Main Jupyter notebook with data preprocessing, model training, and evaluation.
- `Fatigue Dataset for Steel.csv` : Dataset containing features and target variable (`Fatigue`). (Credit to NIMS Japan)

## Features
- Data preprocessing and cleaning
- Train-test split and cross-validation
- Multiple regression models tested:
  - Linear Regression
  - (Add others you implemented, e.g., Decision Tree, Random Forest, XGBoost)
- Model evaluation using Mean Squared Error (MSE)
- Visualizations for data and predictions

## Tech Stack
- Python 3.x
- pandas, numpy
- matplotlib
- scikit-learn

## Example Workflow
1. Load dataset with `pandas`
2. Split into features and target (`Fatigue`)
3. Train models using cross-validation
4. Evaluate performance (MSE)
5. Compare models and select the best one

## Future Work
- Hyperparameter tuning for improved accuracy
- Use advanced models (XGBoost, Neural Networks)
- Deploy model as an API or web app
