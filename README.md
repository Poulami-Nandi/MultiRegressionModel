# Regression and Classification Model Comparator

This Python project is designed to compare the performance of various regression and classification models on a given dataset. It provides a streamlined workflow for data preprocessing, exploratory data analysis (EDA), model training, hyperparameter tuning, and evaluation.

## Features

Data Preprocessing: Handles missing values, removes duplicates, performs label encoding for categorical features, and scales numerical features.

## Exploratory Data Analysis (EDA):

Identifies and visualizes outliers.

Generates a correlation heatmap.

Model Training and Evaluation:

Supports a wide range of regression and classification models.

Automatically applies hyperparameter tuning where applicable.

Evaluates models using appropriate metrics based on the task type (regression or classification).

## Results:

Displays model performance in tabular format.

Identifies and outputs the best-performing model.

Supported Models

Regression Models:

* Linear Regression

* Ridge Regression

* Lasso Regression

* ElasticNet Regression

* Random Forest Regressor

* Gradient Boosting Regressor

* OLS (Ordinary Least Squares)

* Support Vector Regression (SVR)

Classification Models:

* Gaussian Naive Bayes

* Multinomial Naive Bayes

Getting Started

Prerequisites

Ensure you have Python installed along with the required libraries. You can install the necessary dependencies using the following command:

pip install pandas numpy seaborn matplotlib scikit-learn statsmodels pyearth

## Usage

Clone the repository:

git clone <repository_url>
cd <repository_folder>

Prepare your dataset:

Ensure your dataset is in CSV format.

Specify the target column name.

Run the script:

python <script_name>.py

Provide inputs when prompted:

File path: Path to your CSV dataset.

Target column: Name of the column to predict.

Task type: Either regression or classification.

## Example

Enter the file path: data.csv
Enter the target column: price
Enter the task type (regression/classification): regression

## Results

A detailed analysis is displayed, including model performance metrics (e.g., MSE, R², or Accuracy).

The best-performing model is highlighted.

File Structure

main.py: Main script for running the project.

data/: Folder to store datasets.

results/: Folder to store outputs

## Contributing

Contributions are welcome! Feel free to fork the repository and submit a pull request.

## License

This project is licensed under the MIT License. See the LICENSE file for details.

