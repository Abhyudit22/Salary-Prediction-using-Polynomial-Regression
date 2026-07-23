# AI-ML Assignment 3: Salary Prediction

## Objective
The objective of this assignment is to estimate the salary of employees based on their position level by developing a Polynomial Regression model.

## Dataset Link
[Position Salaries Dataset on Kaggle](https://www.kaggle.com/datasets/akram24/position-salaries)

## Libraries Used
- pandas
- numpy
- matplotlib
- scikit-learn

## Methodology
1. **Data Preprocessing**: Handled missing values, selected features (Level) and target (Salary), and split the data into 80% training and 20% testing sets.
2. **Model Training**: Transformed input features to polynomial features of degree 3 and trained a Linear Regression model.
3. **Evaluation**: Evaluated the model using Mean Absolute Error (MAE), Mean Squared Error (MSE), and R² Score, and visualized the curve.

## Results
The polynomial regression curve successfully captures the non-linear relationship of the data, showing a good R² score and proving to be an effective model for this scenario.

## Conclusion
This assignment focused on predicting employee salaries based on their position levels using polynomial regression. **Key findings** show a strong non-linear relationship between position level and salary, which a simple linear regression would fail to capture adequately. 

The main **difference between Linear Regression and Polynomial Regression** is that linear regression assumes a straight-line relationship, while polynomial regression introduces higher-degree terms to model curves. 

**One major advantage of Polynomial Regression for this specific dataset** is its ability to accurately map the exponential-like growth of salaries at higher position levels.
