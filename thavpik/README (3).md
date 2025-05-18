# 📊 Customer Churn Prediction Using Machine Learning

This project helps you predict **customer churn** using machine learning and explain the results with **SHAP** (SHapley Additive exPlanations). A simple **Flask web app** allows users to upload a CSV file and receive visual and textual insights into why customers may leave.

---

## 🚀 Features

- 📁 Upload your own customer churn CSV file via web interface
- 🤖 Train an XGBoost model automatically
- 📈 View detailed classification performance (precision, recall, F1)
- 🔍 Visualize feature importance using SHAP
- 🌐 Lightweight and easy to run locally with Flask

---

## 🧠 Technologies Used

- Python 3.8+
- Flask
- scikit-learn
- XGBoost
- SHAP
- Pandas, Matplotlib, Seaborn

---

## 📂 Project Structure

customer-churn-app/
├── app.py # Main Flask app
├── customer_churn.csv # Sample dataset
├── templates/
│ ├── index.html # File upload UI
│ └── result.html # Prediction + SHAP output
├── static/
│ └── shap_summary.png # SHAP plot (auto-generated)
├── uploads/ # Stores uploaded files
├── requirements.txt # Python dependencies
└── README.md # Project documentation