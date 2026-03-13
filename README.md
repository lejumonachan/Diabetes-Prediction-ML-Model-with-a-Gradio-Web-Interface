# Diabetes-Prediction-ML-Model-with-a-Gradio-Web-Interface
# Diabetes Prediction using Machine Learning

This project predicts the likelihood of diabetes using machine learning models trained on medical patient data. The system analyzes key health indicators such as glucose level, BMI, age, blood pressure, and insulin levels to estimate diabetes risk.

The project compares multiple machine learning algorithms and uses an ensemble voting classifier to improve prediction performance. A simple web interface is created using Gradio so users can enter patient details and get instant predictions.

## Features
- Data preprocessing and normalization
- Exploratory Data Analysis (EDA)
- Multiple ML models implemented
- Ensemble learning using Voting Classifier
- Interactive prediction interface using Gradio

## Machine Learning Models Used
- Logistic Regression
- Random Forest
- AdaBoost
- Gradient Boosting
- Voting Ensemble Model

## Dataset Features
The model uses the following medical attributes:

- Pregnancies
- Glucose
- Blood Pressure
- Skin Thickness
- Insulin
- BMI
- Diabetes Pedigree Function
- Age

## Model Performance
Accuracy achieved by different models:

- Logistic Regression: ~76%
- AdaBoost: ~77%
- Gradient Boosting: ~76%
- Random Forest: ~76%
- Voting Ensemble: ~76%

## Technologies Used
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- Gradio

## How to Run the Project

1. Clone the repository
2. Install dependencies
3. Run the notebook or Python script

```bash
pip install pandas numpy scikit-learn matplotlib seaborn gradio
