# Medical-Cost-Analysis

This repository contains the Jupyter Notebook and related files for the analysis of medical cost data. 

This project explores the medical charges on various factors like smoking status, age, and BMI using statistical analysis and machine learning techniques. The analysis aims to provide insights into how these factors impact healthcare costs, with detailed regression and hypothesis testing included.

# Table of Contents

Project Overview
Dataset
Installation
Usage
Analysis Details
1. Smoking Status and Medical Charges
2. Obesity and Medical Charges
2.1 Hypothesis Testing
2.2 Regression Analysis
Conclusion
Contributing

# Project Overview

This project involves analyzing a dataset of medical charges billed by health insurance. The primary objectives are:

To determine how smoking status, age, and BMI affect medical charges.
To investigate the influence of obesity on medical costs.
Dataset

# Dataset

The dataset used in this project contains medical charges along with various attributes like age, BMI, smoking status, etc.

# Installation

To run the notebook and perform the analysis, you need to have the following dependencies installed:

Python 3.x
Jupyter Notebook
Pandas
NumPy
Matplotlib
Seaborn
Scikit-learn
Statsmodels

You can install the required packages using pip:

bash
Copy code
pip install pandas numpy matplotlib seaborn scikit-learn statsmodels

# Usage

Clone the repository:

bash
Copy code
git clone https://github.com/your_username/medical-cost-analysis.git

Navigate to the project directory:

bash
Copy code
cd medical-cost-analysis

Open the Jupyter Notebook:

bash
Copy code
jupyter notebook MedicalCost_Analysis_SubmissionNotebook.ipynb

# Analysis Details

1. Smoking Status and Medical Charges
   
Description:

We analyze the impact of smoking status on medical charges, taking into account the interaction between age and smoking status.

Approach:

Exploratory Data Analysis (EDA)
Linear Regression

2. Obesity and Medical Charges
   
2.1 Hypothesis Testing

Objective: To test whether the medical charges for obese individuals are higher than those for non-obese individuals.

Hypotheses:

Null Hypothesis (H0): The charges for obese individuals are either equal to or lower than those for non-obese individuals.
Alternative Hypothesis (H1): The charges for obese individuals are higher than those for non-obese individuals.
Significance Level: 0.05

Method: One-tailed T-test

2.2 Regression Analysis

Objective: To quantify the relationship between obesity (BMI) and medical charges.

Approach:

Exploratory Data Analysis (EDA)
Linear Regression

# Conclusion

The regression analysis provides robust evidence that smoking status, age, and BMI are significant predictors of medical charges. Smokers incur substantially higher medical charges compared to non-smokers. Additionally, the interaction term reveals that the relationship between age and medical charges differs for smokers and non-smokers, indicating that public health interventions targeting smoking cessation and age-related healthcare needs may be crucial in reducing overall medical costs.

# Contributing

Contributions are welcome! Please create an issue or submit a pull request for any improvements or bug fixes.

