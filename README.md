# credit-risk-classification
Module 20 Challenge


# Lending Data Analysis and Logistic Regression Model

## Overview
This repository contains code for analyzing lending data and implementing logistic regression models to predict loan statuses. The code leverages Python and several libraries, including pandas, scikit-learn, and imbalanced-learn.

## Instructions

### Step 1: Data Setup
1. **Data Source**: Ensure that the `lending_data.csv` file is placed in the `Resources` folder.
2. **Libraries**: Install the necessary Python libraries listed in `requirements.txt` using `pip install -r requirements.txt`.

### Step 2: Data Analysis
1. **Data Loading**: Use Pandas to read the lending data from `lending_data.csv`.
2. **Data Exploration**: Examine the dataset, review the columns, and check for any missing values.

### Step 3: Model Training
1. **Splitting Data**: Split the data into training and testing datasets using `train_test_split`.
2. **Logistic Regression Model**: Implement a logistic regression model with the original data.

### Step 4: Resampling Data
1. **Resampling**: Utilize `RandomOverSampler` from `imbalanced-learn` to balance the labels.
2. **Logistic Regression with Resampled Data**: Train a logistic regression model using the resampled data.

### Step 5: Evaluation Metrics
1. **Balanced Accuracy**: Assess the model's performance using balanced accuracy scores.
2. **Confusion Matrix**: Generate a confusion matrix to visualize model predictions.
3. **Classification Report**: View precision, recall, and F1-score for each class.

## Usage
- Ensure Python 3.x and required libraries are installed.
- Run the code cells in the Jupyter Notebook or execute the Python script to replicate the analysis and model training.
- Modify paths or filenames as needed to match your file structure.
- Adjust model hyperparameters or try different classifiers for experimentation.

## Credits
- **Justin Bisal** - TA
- **James Newman** - TA
- **Ask BCS tutor**
