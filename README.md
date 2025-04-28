# Internship_Task_3
# Housing Dataset Linear Regression

This project demonstrates how to perform linear regression on a housing dataset using Python and `scikit-learn`. The goal is to build a model that predicts house prices based on features like square footage, number of rooms, and other factors.

## Steps

### 1. Import and Preprocess the Dataset
The dataset is loaded and preprocessed for analysis. This involves:
- Reading the CSV file using `pandas`.
- Handling any missing values, duplicates, or categorical features.
- Scaling or encoding data if necessary.

### 2. Split Data into Train-Test Sets
The dataset is split into training and testing sets using an 80-20 split. The training set is used to train the model, and the testing set is used to evaluate its performance.

### 3. Fit a Linear Regression Model
The model is trained using `sklearn.linear_model.LinearRegression`. It learns the relationship between the input features and the target variable (house prices).

### 4. Evaluate the Model
The performance of the model is evaluated using three key metrics:
- **Mean Absolute Error (MAE)**: Measures the average magnitude of errors in the predictions.
- **Mean Squared Error (MSE)**: Measures the average squared difference between the predicted and actual values.
- **R² Score**: Indicates how well the model fits the data (range from 0 to 1, where 1 is a perfect fit).

### 5. Plot the Regression Line
A plot of the regression line is created to visualize how well the model fits the data. The line represents the predictions made by the model.

Additionally, the coefficients of the regression model are interpreted to understand the importance of each feature in predicting house prices.

## Requirements

- Python 3.x
- `pandas`
- `numpy`
- `matplotlib`
- `scikit-learn`

## Installation

To get started with this project, clone the repository and install the required dependencies:

```bash
git clone <repository_url>
cd <repository_directory>
pip install -r requirements.txt
