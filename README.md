# CloudyML Internship – Project 1  
## Predicting Graduate Admissions Using Linear Regression

## Project Overview

This project focuses on developing a Linear Regression model to predict a student’s probability of admission to Ivy League universities based on academic and profile-related parameters.

The project was completed as part of the CloudyML Internship in collaboration with Jamboree Education, a leading test preparation and educational consulting organization.

The objective of this project was to:

- Build a reliable predictive model  
- Perform comprehensive Exploratory Data Analysis (EDA)  
- Validate linear regression assumptions  
- Generate actionable insights for educational consulting  

---

## Dataset Description

The dataset used is `jamboree_admission.csv`, containing 500 records with the following features:

- GRE Score (out of 340)  
- TOEFL Score (out of 120)  
- University Rating (out of 5)  
- Statement of Purpose (SOP) strength (out of 5)  
- Letter of Recommendation (LOR) strength (out of 5)  
- CGPA (out of 10)  
- Research Experience (0 = No, 1 = Yes)  
- Chance of Admit (Target variable: continuous value between 0 and 1)

---

## Methodology

### 1. Problem Definition and Exploratory Data Analysis

- Defined the business problem and its relevance in educational consulting  
- Performed data inspection for data types, missing values, duplicates, and descriptive statistics  
- Conducted univariate and bivariate analysis  
- Generated correlation matrix and visualizations  
- Identified distributions, outliers, and feature relationships  

---

### 2. Data Preprocessing

- Removed duplicate records  
- Checked and treated outliers where necessary  
- Confirmed absence of missing values  
- Scaled numerical features for regression modeling  

---

### 3. Model Development

- Built a Multiple Linear Regression model using Statsmodels  
- Interpreted regression coefficients and statistical significance  
- Implemented Ridge and Lasso Regression for regularization  
- Compared performance across models  

---

### 4. Testing Linear Regression Assumptions

- **Multicollinearity**: Evaluated using Variance Inflation Factor (VIF); removed variables with VIF > 5  
- **Zero Mean of Residuals**: Verified residual mean close to zero  
- **Linearity**: Examined through residual vs fitted plots  
- **Homoscedasticity**: Confirmed constant variance of residuals  
- **Normality of Errors**: Assessed using histogram and Q-Q plot  

---

### 5. Model Evaluation

The model was evaluated using:

- R²  
- Adjusted R²  
- Mean Absolute Error (MAE)  
- Root Mean Squared Error (RMSE)  

Training and test performance were compared to detect potential overfitting.

---

## Key Insights

- CGPA, GRE Score, and Research Experience were identified as the most significant predictors of admission probability.  
- Strong academic metrics substantially increase admission chances.  
- Inclusion of additional features such as extracurricular activities, internships, and essay evaluations could further improve model performance.  

---

## Project Deliverables

- Jupyter Notebook (`.ipynb` / `.html`)  
- Exploratory Data Analysis visualizations  
- Linear, Ridge, and Lasso regression models  
- Residual diagnostic plots  
- Final summary report  

---

## Tools and Technologies

- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Statsmodels  
- Scikit-learn  
- Jupyter Notebook  

---

## Author

Manchit Sinha  
B.Tech, Computer Science (AI)  
Aspiring Data Analyst  
CloudyML Intern  
