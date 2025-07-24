# CloudyML-INTERNSHIP
📌 Project Title: Predicting Graduate Admissions with Linear Regression
👨‍💻 Internship: CloudyML – Internship Project 1
📖 Project Overview
This project focuses on building a Linear Regression model to predict a student's chance of admission into Ivy League universities based on academic and profile parameters. The project was part of the CloudyML internship, in collaboration with Jamboree Education, a leading test preparation company.

The objective was not only to create a predictive model but also to gain actionable insights from the data through rigorous Exploratory Data Analysis (EDA) and testing of linear regression assumptions.

📊 Dataset Description
The dataset used is jamboree_admission.csv, which contains 500 entries with the following features:

GRE Score (out of 340)

TOEFL Score (out of 120)

University Rating (out of 5)

Statement of Purpose (SOP) strength (out of 5)

Letter of Recommendation (LOR) strength (out of 5)

CGPA (out of 10)

Research Experience (0 = No, 1 = Yes)

Chance of Admit (target variable: between 0 and 1)

🧪 Steps Followed
✅ 1. Problem Statement & EDA
Defined the problem statement and importance of prediction in educational consulting.

Checked data types, null values, duplicates, and basic statistics.

Conducted univariate and bivariate analysis using plots and correlation matrix.

Derived initial insights from distributions, outliers, and relationships.

✅ 2. Data Preprocessing
Removed duplicate records.

Handled any potential outliers.

No missing values were present.

Scaled and prepared the data for regression.

✅ 3. Model Building
Built a Multiple Linear Regression model using Statsmodels.

Interpreted model coefficients and their significance.

Further experimented with Ridge and Lasso Regression for regularization.

✅ 4. Testing Assumptions of Linear Regression
✅ Multicollinearity: Checked using VIF, removed variables with VIF > 5.

✅ Residual Mean ≈ 0

✅ Linearity: Verified using residual plots

✅ Homoscedasticity: Checked constant variance of errors

✅ Normality: Verified through histogram and QQ plot

✅ 5. Model Evaluation
Evaluated model using:

R² and Adjusted R²

Mean Absolute Error (MAE)

Root Mean Squared Error (RMSE)

Compared training and test performance to check for overfitting.

✅ 6. Insights & Recommendations
Identified most significant predictors: CGPA, GRE Score, and Research Experience.

Suggested collecting additional data such as extracurriculars, internships, and essay scores for better prediction.

Discussed potential implementation in student counseling and personalized study plans.

📁 Project Deliverables
✅ Jupyter Notebook (.ipynb / .html)

✅ EDA Visualizations

✅ Linear, Ridge, and Lasso Regression Models

✅ Residual Diagnostic Plots

✅ Final Summary Report

🔧 Tools & Technologies Used
Python

Pandas, NumPy

Matplotlib, Seaborn

Statsmodels

Scikit-learn

Jupyter Notebook

✍️ Author
Manchit Sinha
B.Tech, Computer Science (AI)
Aspiring Data Analyst | CloudyML Intern

