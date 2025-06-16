# 🧪 Glucose Level Prediction using Machine Learning

This project aims to predict the risk of diabetes in individuals based on health-related features such as glucose levels, blood pressure, BMI, insulin, and age. It uses supervised machine learning algorithms to build and evaluate classification models using a structured dataset.

---

## 📌 Objectives

- Clean and preprocess the dataset
- Perform Exploratory Data Analysis (EDA)
- Train multiple classification models
- Evaluate model performance using metrics like accuracy, confusion matrix, and classification report

---

## 🛠️ Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## 📁 Dataset Features

The dataset includes the following columns:
- `Glucose`
- `BloodPressure`
- `BMI`
- `Insulin`
- `Age`
- `Outcome` (0 = Non-diabetic, 1 = Diabetic)

You can use the [Pima Indians Diabetes Database](https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database) for this project.

---

## 🔍 Models Used

- Random Forest Classifier  
- Logistic Regression  
- Decision Tree Classifier  

Each model was trained and tested using the processed data. Evaluation metrics include:
- Accuracy Score
- Confusion Matrix
- Classification Report

---

## 📊 Exploratory Data Analysis (EDA)

EDA was performed to:
- Identify missing values
- Understand feature relationships
- Visualize distributions and correlations using histograms, box plots, and heatmaps

---

## 📈 Results

All models were evaluated and compared to determine the most accurate classifier for predicting diabetes. Random Forest generally showed better performance in terms of accuracy and precision.

---

## 📌 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/glucose-prediction.git
