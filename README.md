# Air Quality Analysis Project

This project involves analyzing air quality data to predict carbon monoxide (CO) levels, which are critical indicators of air pollution. The analysis was conducted applying both traditional linear classification and neural network models.

## Project Overview

### Objective
The primary goal of this project is to predict CO values based on 11 variables representing the concentration of various gases in a polluted city. This is achieved through two approaches:
1. Linear Classification Model
2. Neural Network (MLPRegressor)

### Dataset
The dataset includes measurements of various gases in a polluted city, with CO levels as the target variable. The data was cleaned, missing values were imputed, and then it was split into training and testing sets.

## Methodology

### 1. Data Preparation
- **Data Cleaning:** Removed or corrected inconsistent data entries.
- **Imputation:** Filled in missing data points to ensure a complete dataset.
- **Data Splitting:** The dataset was split into training and testing sets for model evaluation.

### 2. Linear Classification Model
- **Model Training:** A linear classification model was used to train on the dataset.
- **Prediction:** The model predicted CO values based on the other 11 variables.

### 3. Neural Network (MLPRegressor)
- **Model Training:** Implemented a neural network using `MLPRegressor` from Scikit-learn.
- **Grid Search:** Conducted a grid search to identify the best hyperparameters, including hidden neuron layers and activation functions.
- **Optimizer Comparison:** Compared the performance of Stochastic Gradient Descent (SGD) and ADAM optimizers using the best parameters identified in the previous step.

### 4. Model Evaluation
- **Comparison:** Evaluated the performance of the linear classification model and the neural network model, focusing on their ability to predict CO values accurately.

## Dependencies
- Python 3.x
- Jupyter Notebook
- Scikit-learn
- NumPy
- Pandas
- Matplotlib (optional, for data visualization)

## How to Run the Project
1. Clone this repository.
```bash
git clone https://github.com/nigelmj/air-quality-analysis.git
cd air-quality-analysis
```
2. Install the required dependencies.
```bash
pip install -r requirements.txt
```
3. Open the Jupyter Notebook and run the cells sequentially to see the results of the analysis.

## Conclusion
This project demonstrates the effectiveness of using both linear models and neural networks in predicting air quality indicators. The comparison of optimizers further provides insights into the best practices for tuning neural networks.
