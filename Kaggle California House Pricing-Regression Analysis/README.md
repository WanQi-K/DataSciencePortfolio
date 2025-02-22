This project explores predicting median house values in California using machine learning. We analyze key housing factors such as location, median income, and housing characteristics to identify what drives property prices. The goal is to build an accurate model that can help homebuyers, investors, and policymakers make data-driven decisions.

Dataset
Source: California Housing Prices (Kaggle)
Target Variable: median_house_value (House Price)
Features Used: Median income, house age, total rooms, population, latitude, longitude, and more
Machine Learning Models Tested
Linear Regression
Polynomial Regression
Decision Tree Regression
Random Forest Regression
XGBoost Regression (Best performing model)
Key Findings
✔ Income is the strongest predictor – Higher median incomes lead to higher house prices
✔ Location matters – Inland properties tend to have lower prices compared to coastal areas
✔ XGBoost is the best model – Achieved the highest accuracy with R² = 0.88 and lowest RMSE = 0.46

Key Techniques & Preprocessing
Feature Engineering: One-hot encoding, correlation analysis, feature scaling
Data Cleaning: Log transformation to normalize skewed data
Hyperparameter Tuning: Optimized models for better accuracy
Feature Importance Analysis: Identified which factors impact prices the most
Next Steps & Future Improvements
🚀 Incorporate additional features (crime rates, school ratings)
🚀 Explore deep learning models for better predictions
🚀 Optimize hyperparameters further

How to Run This Project
Download the dataset from Kaggle
Clone this repository
Run the Jupyter Notebook / Python script
📌 Full Code Available: GitHub Repository

This project is part of my ML learning journey, where I focus on applying machine learning to real-world problems. Follow along as I explore, experiment, and refine my skills! 🚀
