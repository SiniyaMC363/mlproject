🎓 Student Performance Indicator

📌 Project Overview

The Student Performance Indicator is an end-to-end Machine Learning project that predicts a student's Math Score using demographic and academic performance features.

This project demonstrates:

Complete ML pipeline implementation
Model training & evaluation
Flask-based web deployment
Real-time prediction through a user interface

🎯 Problem Statement
To predict a student's math score based on:

Gender
Race/Ethnicity
Parental Level of Education
Lunch Type (Standard / Free-Reduced)
Test Preparation Course
Reading Score
Writing Score
This helps identify students who may require academic support.

📊 Dataset

Student Performance dataset (public dataset used for academic ML practice).
Target Variable: math_score

🧠 Machine Learning Pipeline
🔹 Data Processing
Handling categorical variables (Encoding)
Feature scaling
Train-Test split
Pipeline implementation

🔹 Models Trained
Linear Regression
Decision Tree Regressor
Random Forest Regressor
CatBoost Regressor

🔹 Evaluation Metrics
R² Score
Mean Absolute Error (MAE)
Mean Squared Error (MSE)

Best-performing model selected for deployment.

🏗 Project Structure
Student-Performance-Indicator/
│
├── src/
│   ├── components/
│   ├── pipeline/
│   ├── exception.py
│   └── utils.py
│
├── templates/
├── static/
├── app.py
├── requirements.txt
└── README.md
🌐 Web Application

The project is deployed locally using Flask.

Features:
User-friendly input form
Real-time math score prediction
Clean UI interface
Integrated ML prediction pipeline

🚀 How to Run Locally
1️⃣ Clone the Repository
git clone https://github.com/SiniyaMC363/mlproject.git
cd mlproject
2️⃣ Create Virtual Environment
conda create -p venv python=3.8 -y
conda activate venv
3️⃣ Install Dependencies
pip install -r requirements.txt
4️⃣ Run the Application
python app.py

Open your browser:
http://localhost:5000

🛠 Tech Stack
Python
Pandas
NumPy
Scikit-learn
CatBoost
Flask
HTML/CSS

📈 Future Improvements

Cloud Deployment (AWS / Render)
Model Explainability (SHAP)
Add Dashboard Visualizations
Improve UI/UX

👩‍💻 Author

Siniya MC
B.Tech – Artificial Intelligence & Data Science
LinkedIn: https://www.linkedin.com/in/siniya-mc
GitHub: https://github.com/SiniyaMC363
