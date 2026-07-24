#  AI-Based Hiring Prediction System

## Overview

The AI-Based Hiring Prediction System is a Machine Learning project that predicts whether a candidate should be **Hired** or **Rejected** based on resume-related information. The project demonstrates the complete ML workflow, including data preprocessing, exploratory data analysis (EDA), model training, evaluation, hyperparameter tuning, and prediction.

---

##  Objective

To build a classification model that assists recruiters by predicting hiring decisions using candidate information.

---

##  Dataset Features

- Skills
- Experience (Years)
- Education
- Certifications
- Job Role
- Salary Expectation
- Projects Count
- AI Score
- Recruiter Decision (Target)

---

##  Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Joblib

---

## 📊 Workflow

1. Import Libraries
2. Load Dataset
3. Perform Exploratory Data Analysis (EDA)
4. Handle Missing Values
5. Remove Unnecessary Columns
6. Encode Categorical Features
7. Split Data into Training and Testing Sets
8. Apply StandardScaler
9. Train Machine Learning Models
10. Compare Model Performance
11. Hyperparameter Tuning using GridSearchCV
12. Save the Best Model
13. Predict Hiring Decisions

---

##  Machine Learning Models

- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier

---

##  Evaluation Metrics

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix

---

## 📷 Results

The Random Forest Classifier achieved the best performance among the tested models and was selected as the final prediction model.

---

## 📁 Project Structure

```text
dataset/
notebook/
models/
README.md
requirements.txt
```

---

## ▶️ How to Run

```bash
git clone https://github.com/nischay25/AI-Based-Hiring-Prediction-System.git
cd AI_Hiring_Prediction_System

pip install -r requirements.txt

jupyter notebook
```

Open the notebook and run all cells.

---

##  Future Improvements

- Build a Streamlit web application
- Deploy using Render or Hugging Face Spaces
- Add Resume PDF Parsing
- Improve prediction using advanced ensemble models

---

##  Author

**Nischay V**
