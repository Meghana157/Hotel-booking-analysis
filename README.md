# 🏨 Hotel Booking Analysis & Prediction

## 📌 Project Overview  
This project analyzes hotel booking data and applies machine learning models to predict booking cancellations. The goal is to optimize hotel operations, improve revenue management, and enhance customer satisfaction through data-driven insights.

## 🔍 Objectives  
- Explore key factors affecting hotel bookings  
- Perform data cleaning and feature engineering  
- Apply machine learning models to predict cancellations  
- Compare model performance using cross-validation accuracy  

## 📂 Dataset  
- The dataset includes booking details such as check-in dates, lead times, customer types, cancellation status, and more.  

## 📊 Exploratory Data Analysis  
- Distribution of cancellations vs. non-cancellations  
- Impact of lead time, deposit type, and customer type on cancellations  
- Seasonal trends in hotel bookings  

## 🛠️ Tools & Technologies  
- **Programming Language**: Python 🐍  
- **Libraries**: Pandas, NumPy, Scikit-Learn, Matplotlib, Seaborn  
- **Machine Learning Models**: Logistic Regression, Decision Tree, Random Forest, Gradient Boosting, SVM, XGBoost  

## 📈 Model Performance  
The following machine learning models were trained and evaluated using **cross-validation accuracy**:

| Model               | Accuracy  |
|---------------------|----------|
| Logistic Regression | 0.7282   |
| Decision Tree       | 0.7362   |
| Random Forest      | 0.7529   |
| Gradient Boosting  | 0.7547   |
| SVM                | 0.4399   |
| XGBoost            | **0.7614**   |

🔥 **XGBoost performed the best with an accuracy of 76.14%!**  

## 🚀 Key Findings  
- **Lead time** plays a significant role in predicting cancellations.  
- **Customers with non-refundable deposits** are less likely to cancel.  
- **Repeat guests** have a lower probability of canceling.  
- **Seasonality affects booking patterns**, with higher cancellations during peak periods.  
 

