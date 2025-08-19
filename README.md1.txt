# Project 1: Employee Salary Prediction

## 📌 Overview
A simple linear regression model built with **AWS SageMaker Linear Learner** to predict employee salary based on years of experience.

## 🗂️ Dataset
- `salary.csv` → Contains YearsExperience & Salary.
- Source: Kaggle dataset.

## ⚙️ Steps
1. Upload dataset to **Amazon S3**.
2. Train Linear Learner model in **SageMaker**.
3. Split data into training/testing sets.
4. Deploy endpoint for predictions.
5. Evaluate with **RMSE**.

## 📊 Results
- Example: `5 years experience → Predicted salary ≈ $55,000`
- Model fits regression line reasonably well.

## 📎 Files
- `employee_salary_prediction_notebook.ipynb` → Notebook
- `salary.csv` → Dataset
- `slides/employee_salary_prediction_slides.pptx` → Slides
