Customer Churn Prediction

📌 Project Overview

This project aims to predict customer churn using machine learning techniques. It involves data preprocessing, exploratory data analysis (EDA), model training, and deploying a predictive API.

🏗️ Project Structure

Customer_Churn_Prediction/
│── data/               # Contains raw and processed datasets
│── models/             # Stores trained machine learning models
│── notebooks/          # Jupyter notebooks for EDA and model development
│── static/             # Static files (if applicable for web app)
│── templates/          # HTML templates (if applicable for Flask app)
│── venv/               # Virtual environment
│── requirements.txt    # List of dependencies
│── README.md           # Project documentation
│── app.py              # Flask API for predictions

🛠️ Setup Instructions

1️⃣ Clone the Repository

git clone https://github.com/Shrungal-DSAI/Customer_Churn_Prediction.git
cd Customer_Churn_Prediction

2️⃣ Create & Activate Virtual Environment

python -m venv venv
venv\Scripts\activate  # Windows
source venv/bin/activate  # Mac/Linux

3️⃣ Install Dependencies

pip install -r requirements.txt

4️⃣ Run Jupyter Notebook (for EDA & Model Training)

jupyter notebook

➡ Open notebooks/Customerchurnprediction.ipynb and execute the cells.

5️⃣ Run the Flask API

python app.py

API will be accessible at: http://127.0.0.1:5000/predict

📊 Model Training Steps

Data Preprocessing: Handle missing values, encode categorical variables, and normalize data.

Exploratory Data Analysis (EDA): Understand distributions, correlations, and patterns.

Model Selection: Train different ML models (e.g., Logistic Regression, Random Forest, XGBoost).

Evaluation: Measure performance using accuracy, precision, recall, and F1-score.

Deployment: Save the best model using joblib and serve predictions via Flask API.

🚀 Future Improvements

Optimize hyperparameters using GridSearchCV

Deploy on cloud platforms like AWS/GCP

Build an interactive dashboard using Streamlit or Flask

🤝 Contributing

Pull requests are welcome! For major changes, please open an issue first to discuss.

📜 License

This project is licensed under the MIT License.


