# House_prediction
## Explainable AI - Salary Analysis

### Overview
This repository contains the code and analysis for a project focused on understanding the underlying factors influencing salary using INSEE data. The project utilizes Python for data analysis, with a primary focus on the pandas and matplotlib libraries.

### Getting Started
1. **Download Data:**
   - Visit [INSEE Data](https://www.insee.fr/fr/statistiques/7651654) and download the data and documentation files.
   - Extract the downloaded files.

2. **Load Data in Jupyter Notebook:**
   - Use a Jupyter notebook to load the data using pandas.
   - Understand the variables with the help of the documentation file.
   - Choose 5-10 variables related to salary (e.g., gender, type of contract).

### Data Cleaning
3. **Clean Data:**
   - Replace codes with their corresponding values based on the documentation file.
   - For salary, replace it with the lower part of the bracket.

### Data Analysis
4. **Compute Correlation Matrix:**
   - Compute the correlation matrix for numerical variables.
   - Identify highly correlated or anti-correlated variables and assess their logical relevance.
   - Analyze average salary grouped by categorical variables.

5. **Visualize Data:**
   - Create pairwise scatter plots between salary and other numerical variables.
   - Plot salary box-plots for each category of categorical variables.
   - Identify interesting patterns or outliers.

### Linear Regression
6. **Build Linear Model:**
   - Import the linear regressor from the sklearn library.
   - Split data into training and testing sets.
   - Train the linear model and evaluate R2 score and RMSE.
   - Examine regression parameters and interpret their significance.

### Model Improvement
7. **Log Transformation:**
   - Try improving the model by taking the logarithm of the salary.
   - Assess how the interpretation of parameters changes with the log-transformed salary.

Feel free to explore the Jupyter notebook in this repository for a step-by-step walkthrough of the analysis.
