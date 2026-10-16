# electricity-consumption-prediction-
# Electricity Consumption Prediction

## Project Overview

This project uses Machine Learning to predict electricity consumption based on environmental and calendar-related features.

It was developed as a beginner-friendly project to practice the main steps of a Machine Learning workflow.

## Objectives

- Explore and visualize a dataset.
- Prepare data for Machine Learning.
- Train and evaluate regression models.
- Compare Linear Regression and Random Forest.
- Predict electricity consumption for new observations.

## Dataset

The project uses a synthetic dataset containing 5,000 rows and variables such as:

- Hour
- Temperature
- Humidity
- WindSpeed
- Sunshine
- Weekend
- Holiday
- Consumption (target variable)

**Note:** The dataset is synthetic and does not represent real electricity measurements.

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Google Colab

## Models and Evaluation

The project compares Linear Regression with Random Forest Regressor.

The optimized Random Forest achieved approximately:

- **R² on test data:** 0.901
- **MAE on test data:** 0.292
- **Mean cross-validation R²:** 0.907

These results apply to the synthetic dataset used in this educational project.

## Project Workflow

1. Data exploration and visualization
2. Data preparation
3. Train/test split
4. Model training
5. Model evaluation
6. Cross-validation
7. Predictions on new observations

## Future Improvements

- Test the models on real electricity consumption data.
- Improve data preprocessing.
- Compare additional Machine Learning algorithms.
- Explore time-series forecasting for 24–72-hour predictions.

## Author

Engineering student interested in Machine Learning, telecommunications, and data science.
