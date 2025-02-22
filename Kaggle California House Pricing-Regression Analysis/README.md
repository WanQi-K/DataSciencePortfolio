# 🏡 California Housing Price Prediction  

## 📌 Project Overview  
This project aims to predict the **median house value in California** based on housing characteristics, location, and demographics. By leveraging **machine learning models**, we analyze key factors driving house prices and assess how well different models perform in making predictions.  

## 📊 Dataset Information  
- **Source:** [California Housing Prices Dataset (Kaggle)](https://www.kaggle.com/datasets/camnugent/california-housing-prices)  
- **Target Variable:** `median_house_value` (House Price)  
- **Independent Variables:** Features like `longitude`, `latitude`, `total_rooms`, `population`, `ocean_proximity`, etc.  

## 🛠️ Methods & Models Used  
The following machine learning models were applied and compared:  
1. **Linear Regression**  
2. **Polynomial Regression**  
3. **Decision Tree Regression**  
4. **Random Forest Regression**  
5. **XGBoost Regression** (Best-performing model)  

🔹 **Feature Engineering & Data Preprocessing:**  
- Applied **log transformation** to normalize skewed data.  
- Created **dummy variables** for categorical features (`ocean_proximity`).  
- Used **StratifiedShuffleSplit** to maintain balanced train-test splits.  
- Scaled numerical features using **StandardScaler**.  

🔹 **Hyperparameter Tuning:**  
- Tuned models for better accuracy and generalization.  
- Compared **R-squared, RMSE (Root Mean Squared Error), and MAE (Mean Absolute Error)** across models.  

## 🔍 Key Findings  
✔️ **Income is the biggest factor influencing house prices** in California.  
✔️ **Houses further inland tend to have lower prices** (negative correlation).  
✔️ **XGBoost outperformed all other models**, achieving the best prediction accuracy.  

## 🚀 How to Run the Project  
1. Clone this repository:  
   ```bash
   git clone https://github.com/yourusername/california-housing-prediction.git

## 📝 I Wrote about this Project
-  [Medium Post](https://medium.com/@kwanqi.yt/kaggle-california-house-pricing-a-machine-learning-approach-33ae91b2ee2b)  
