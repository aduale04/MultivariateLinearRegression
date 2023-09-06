# MultivariateLinearRegression
Multivariate Linear Regression and EDA on a Student performance dataset

# Student Performance Prediction Using Linear Regression

## Overview
This project aims to predict student performance based on various features such as gender, parental level of education, test preparation course, lunch, etc., using a Linear Regression model. The project includes data preprocessing, exploratory data analysis (EDA), and model training and evaluation.

## Data
The dataset used in this project contains information about student performance along with various other attributes like gender, race, parental level of education, etc. The target variable is the performance index, which we aim to predict.

## Requirements
- Python 3.x
- Jupyter Notebook
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn

## Setup
1. Clone the repository to your local machine.
2. Install the required packages using `pip install -r requirements.txt`.
3. Open the Jupyter Notebook and run all cells to see the analysis and model training.

## Steps
1. Data Loading: Load the student performance dataset.
2. Data Preprocessing: Handle missing values and encode categorical variables.
3. Exploratory Data Analysis: Analyze the dataset to identify patterns and relationships among variables.
4. Model Training: Train a Linear Regression model on the preprocessed data.
5. Model Evaluation: Evaluate the model using metrics like RMSE, R-squared, etc.
6. Prediction: Use the trained model to make predictions on new data.

## Results
The trained Linear Regression model shows an R-squared value of 0.98, indicating that 98% of the variability in the dependent variable can be explained by the independent variables in the model. In other words, the model very closely fits the actual data and can account for most of the variations in the target variable.

## Future Work
- Experiment with other machine learning algorithms like Decision Trees, Random Forest, etc.
- Perform hyperparameter tuning to improve model performance.
- Extend the analysis to include more features.

## Author
Your Name

## Acknowledgments
Data sourced from Kaggle.
