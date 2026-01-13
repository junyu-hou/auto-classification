# Auto Dataset: Classification Analysis

This project analyzes the Auto dataset to study how vehicle characteristics
relate to fuel efficiency. I construct a binary outcome variable (`mpg01`)
based on whether a car’s miles-per-gallon (mpg) is above the sample median,
and compare the performance of several classification methods.

The analysis is organized in a single Jupyter notebook and includes:
- Exploratory data analysis (scatter plots and boxplots)
- Train/test split
- Classification using LDA, QDA, logistic regression, and Naive Bayes
- Comparison of test error rates across models

## Repository Structure
- `auto_classification.ipynb`: Main analysis notebook
- `requirements.txt`: Python packages needed
- `.gitignore`: Files and folders excluded from version control
- `data/`: Contains the Auto dataset

## Data
The Auto dataset is commonly used in applied statistics and machine learning
courses. 
