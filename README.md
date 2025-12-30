# GPA Prediction Project

Predicting student GPA using machine learning models in Python.

---

##  Project Overview

This project uses a machine learning regression approach to predict students’ **Grade Point Average (GPA)**.  
The analysis and modeling are contained in a single Jupyter Notebook: `gpa‑prediction.ipynb`. :contentReference[oaicite:1]{index=1}

The goal is to explore relationships between academic/behavioural features and GPA, build models, and evaluate performance.

---

##  Content of This Repository

GPA‑Prediction‑project/
├── gpa‑prediction.ipynb # Main Jupyter Notebook
├── requirements.txt # Python dependencies
└── README.md # Project overview and instructions


---

##  Notebook Summary

The notebook includes:

1. **Exploratory Data Analysis (EDA)**  
   - Summary statistics
   - Visual relationships between features and GPA

2. **Data Preprocessing**
   - Handling missing values
   - Feature encoding/scaling (if applicable)

3. **Modeling**
   - Training regression models (e.g., Linear Regression)
   - Evaluating using appropriate metrics

4. **Results & Interpretation**
   - Model performance metrics
   - Visuals comparing predictions vs actual values

---

##  Results

| Model | R² Score | RMSE |
|-------|----------|------|
| *Random Forest-baseline* | *0.99* | *1.39* |
| *Random Forest*|*0.986* | *1.68* | 
|*XGBoost*|*0.996*|*0.93*|

---

## Conclusion

This project demonstrates how machine learning regression techniques can be applied to predict student GPA using academic and behavioural data. Through exploratory data analysis, preprocessing, and model evaluation, meaningful patterns influencing academic performance were identified.

The results highlight the importance of key factors such as study habits and prior performance in predicting GPA. While the models achieved reasonable predictive performance, there is room for improvement through additional features, hyperparameter tuning, and larger datasets.

Overall, this project strengthened my understanding of regression modeling, model evaluation, and translating analytical results into actionable insights within an educational context.


## 🚀 How to Run

1. **Clone the repository**:
   ```bash
   git clone https://github.com/susannebarasa/GPA-Prediction-project.git
   cd GPA-Prediction-project
