# bank-campaign-analytics 
# Portuguese Bank Marketing Analysis

## Problem Statement

The Portuguese bank is facing a revenue decline, primarily due to a decrease in client deposits. Term deposits, which lock in funds for a specific period, are essential for the bank's revenue. To address this issue, the bank wants to identify prospective clients who are more likely to subscribe to term deposits. This project involves data analysis, feature engineering, and machine learning to achieve this goal.

## About the Dataset

The dataset used for this analysis is sourced from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/bank+marketing). It contains information about marketing campaigns conducted by the bank, with a focus on term deposit subscriptions.

## Project Objectives

The objectives of this project are as follows:

1. **Data Preprocessing:** Prepare the dataset for analysis, including handling missing values, encoding categorical variables, and scaling features.

2. **Exploratory Data Analysis (EDA):** Visualize and explore the dataset to gain insights into client behavior and campaign results.

3. **Machine Learning Modeling:** Build a classification algorithm to predict whether a client will subscribe to a term deposit.

4. **Model Evaluation:** Evaluate the model's performance using appropriate metrics.

## Code Overview

Here's an overview of the key steps in the project code:

```python
# Import necessary libraries
import pandas as pd
import numpy as np
# ... (Other library imports)

# Load the dataset
bank = pd.read_csv("bank-additional-full.csv", sep=';')

# Data preprocessing, EDA, and modeling steps
# ...

# Split the data into training and testing sets
# ...

# Train a logistic regression model
# ...

# Evaluate the model
# ...

# Display model accuracy
# ...

