# AI-ML-Internship-Task2-Modelevaluation
Using pandas libraries and scikit-learn performed model evaluation and tuning and performance analysis

# House Price Prediction: Model Evaluation and Hyperparameter Tuning

## Project Description

This project focuses on evaluating and optimizing machine learning models for house price prediction. The dataset was cleaned and preprocessed before training multiple regression models.

## Dataset

The dataset contains housing information such as:

1. Area Type
2. Availability
3. Location
4. Total Square Feet
5. Number of Bathrooms
6. Balcony Count
7. BHK Size

Target Variable:

-> Price

## Machine Learning Models

### Baseline Models

1. Linear Regression
2. Decision Tree Regressor

## Tuned Model

1. Decision Tree Regressor optimized using GridSearchCV

## Evaluation Metrics

1. Mean Absolute Error (MAE)
2. Mean Squared Error (MSE)
3. R-squared Score (R²)

## Results Summary

----------------------------------
| Model               | R² Score |
| ------------------- | -------- |
| Linear Regression   | 0.524    |
| Decision Tree       | 0.324    |
| Tuned Decision Tree | 0.551    |
----------------------------------

The Tuned Decision Tree Regressor achieved the best performance.

## Visualizations

1. Actual vs Predicted Plot
2. Residual Plot
3. Model Comparison Plot

## Project Structure

README.md
requirements.txt
notebook
reports
images

## Technologies Used

1. Python
2. Pandas
3. NumPy
4. Matplotlib
5. Seaborn
6. Scikit-learn

