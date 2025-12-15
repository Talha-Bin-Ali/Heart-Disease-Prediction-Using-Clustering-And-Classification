# Heart-Disease-Prediction-Using-Clustering-And-Classification
Heart Disease Prediction Using Machine Learning
📌 Project Overview

This project focuses on predicting the presence of heart disease using supervised machine learning techniques. Cardiovascular diseases are among the leading causes of death worldwide, and early prediction can significantly improve treatment outcomes. The goal of this academic project is to build, evaluate, and compare machine learning models that can assist in heart disease diagnosis using patient clinical data.

This project was developed as part of an academic machine learning research assignment.

🎯 Objective

To develop a machine learning–based classification system that predicts whether a patient has heart disease based on clinical and demographic features.

📊 Dataset Description

The project uses the Cleveland Heart Disease Dataset, a widely used dataset in healthcare analytics research. The dataset consists of multiple medical attributes, including:

Age

Sex

Chest pain type (cp)

Resting blood pressure (trestbps)

Serum cholesterol (chol)

Fasting blood sugar (fbs)

Resting ECG results (restecg)

Maximum heart rate achieved (thalach)

Exercise-induced angina (exang)

ST depression (oldpeak)

Slope of ST segment (slope)

Number of major vessels (e

Thalassemia (thal)

The target variable indicates the presence (1) or absence (0) of heart disease.

🧠 Methodology

The workflow followed in this project includes:

Data loading and exploration

Data preprocessing (handling missing values, encoding, scaling)

Feature transformation using pipelines

Model training

Model evaluation and comparison

🤖 Models Implemented

The following machine learning models were trained and evaluated:

Logistic Regression

Random Forest Classifier

These models were selected due to their effectiveness in binary classification problems and frequent use in medical prediction tasks.

📈 Evaluation Metrics

Model performance was evaluated using the following metrics:

Accuracy

Precision

Recall

F1-score

These metrics are especially important in healthcare applications, where incorrect predictions can have serious consequences.

🧪 Results Summary

Logistic Regression provided a strong and interpretable baseline model.

Random Forest Classifier achieved higher predictive performance due to its ability to capture non-linear patterns.

Overall, ensemble-based models showed improved accuracy, while linear models offered better interpretability.

🚀 Deployment (Extension)

As an extension of this project, a simple Flask-based API was implemented to demonstrate how the trained model can be deployed for real-time heart disease prediction.

🛠️ Technologies Used

Python

NumPy

Pandas

Scikit-learn

Matplotlib / Seaborn

Flask

Jupyter Notebook

▶️ How to Run the Project

Clone the repository:

git clone <repository-url>

Navigate to the project directory:

cd heart-disease-prediction

Install required dependencies:

pip install -r requirements.txt

Open the notebook:

jupyter notebook

Run project22.ipynb

⚠️ Limitations

Dataset size is limited

Model trained on a single dataset

Predictions should not replace professional medical diagnosis

🔮 Future Work

Use larger and more diverse datasets

Apply advanced models (Gradient Boosting, Neural Networks)

Perform hyperparameter tuning

Integrate explainable AI techniques (SHAP, LIME)

📚 Academic Disclaimer

This project was developed strictly for educational and academic purposes. The results should not be used for real-world medical decision-making.

👤 Author

Talha Ali
Machine Learning Student
