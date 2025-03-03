# Shared_Bike_Demand_Prediction
</br>

## 🚲 Project Description
This project analyzes the demand for shared bikes in the American market to help BoomBikes, a US-based bike-sharing service, optimize its business strategy post-pandemic. Using historical rental data with features like season, weather, and user type, the study develops a predictive model to identify key factors influencing bike demand. It covers data preprocessing, exploratory analysis, feature engineering, model building, and evaluation, providing actionable insights for demand forecasting and revenue optimization.

## 🔧 Tech Stack  

- **Programming Language:** Python  
- **Libraries:** Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn, Statsmodels  
- **Dataset:** `day.csv` (daily bike rental data, attached)  
- **Model Used:** Multiple Linear Regression (Built using Statsmodels & Scikit-learn)  
- **Tools:** Jupyter Notebook (for analysis & modeling)  

## 🔍 Exploratory Data Analysis (EDA)

- **Data Cleaning & Preprocessing:** Handled missing values, outliers, and applied feature scaling for better model performance.  
- **Feature Engineering:** Derived new features such as moving averages, seasonal indicators, and interaction terms.  
- **Visualization:** Used Matplotlib and Seaborn to analyze trends, correlations, and seasonal patterns in bike-sharing demand.  

## 🚀 Model Training & Evaluation

- **Train-Test Split:** 70% training, 30% testing.  
- **Model Used:** Multiple Linear Regression.  
- **Feature Selection:** Variables were selected based on **p-values** (statistical significance) and **Variance Inflation Factor (VIF)** to handle multicollinearity.  
- **Evaluation Metric:** Adjusted R² was used to assess model performance and explanatory power.  

## ⚡ Key Findings & Insights  



### 🔹 Key Influencing Factors:  
- **Temperature (temp) [+0.4782]** → Strongest positive impact on bike demand. As temperature increases, the number of rentals rises significantly.  
- **Light Snow/Rain (Light_snowrain) [-0.2860]** → Strongest negative impact. Poor weather conditions reduce bike demand considerably.  

### 📈 Positive Contributors to Demand:  
- **Year (year), Summer (summer), Winter (winter), September (Sept)** → Higher values in these features correlate with increased bike rentals.  

### 📉 Negative Contributors to Demand:  
- **Holiday (holiday), Windspeed (windspeed), Spring (spring), Misty (misty)** → These factors negatively impact the number of rentals. Higher wind speed and misty conditions reduce ridership.  

These insights help BoomBikes understand demand patterns and refine their business strategy for revenue growth.  
