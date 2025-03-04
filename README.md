# 📊 Customer Churn Prediction

## 🚀 Project Overview
This project aims to predict customer churn using machine learning techniques. The dataset consists of various customer attributes, such as contract type, tenure, and monthly charges, to determine the likelihood of a customer leaving.

## 📂 Dataset Information
- **Source**: Telco Customer Churn Dataset
- **Size**: 7,043 records
- **Features**: Customer demographics, account information, and usage details

## 🛠️ Preprocessing Steps
- **Data Cleaning**: Handled missing values, converted data types
- **Feature Engineering**: Created meaningful features
- **Encoding**: Transformed categorical variables

## 📊 **Results and Insights**  

### **Model Performance Metrics**  
✅ **AUC Score**: **0.8186** – Indicates strong discriminative ability between churn and non-churn customers.  
✅ **Accuracy**: **78%** – The model correctly classifies 78% of the customers.  

| Metric          | Class 0 (Non-Churn) | Class 1 (Churn) |
|----------------|--------------------|----------------|
| **Precision**  | **0.84**            | **0.59**       |
| **Recall**     | **0.87**            | **0.54**       |
| **F1-Score**   | **0.85**            | **0.56**       |

### **Key Observations**  
📌 **Good performance for non-churn customers**: High precision (84%) and recall (87%) indicate strong classification of customers who are likely to stay.  
📌 **Churn detection needs improvement**: Lower precision (59%) and recall (54%) suggest some misclassifications of actual churners.  
📌 **Top 3 Important Features**:  
   - **TotalCharges** (Most influential)  
   - **Tenure**  
   - **MonthlyCharges**  

### **Next Steps for Improvement** 🚀  
🔹 **Handle Class Imbalance**: Apply SMOTE, oversampling, or class weighting to improve churn prediction.  
🔹 **Feature Engineering**: Explore additional derived features and interactions.  
🔹 **Hyperparameter Tuning**: Use GridSearchCV or RandomizedSearchCV to optimize the model.  
🔹 **Try Different Models**: Experiment with Random Forest, XGBoost, or Neural Networks for enhanced performance.  

## 📌 Conclusion
This project provides insights into customer churn patterns and helps businesses take proactive measures to retain customers. Further improvements in feature engineering and model optimization can enhance predictive accuracy.

---

📧 **Contact:** [shrungalkulkarni30@gmail.com](mailto:shrungalkulkarni30@gmail.com)
🚀 Happy Coding! 🔥
