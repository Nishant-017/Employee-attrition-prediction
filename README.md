# 🧑‍💼 Employee Attrition Prediction (HR Analytics)

This project aims to predict whether an employee is likely to leave the company (attrition) using historical HR data. It uses machine learning classification models, including Logistic Regression and Random Forest, to uncover patterns related to job satisfaction, overtime, income, and more.

---

## 📊 Dataset Overview

- Source: Kaggle – [Employee Attrition dataset](https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset)
- Records: ~1,470 employees  
- Features: Demographic + workplace attributes (e.g., Department, JobRole, OverTime, MonthlyIncome)

---

## 🧪 Project Workflow

1. **Exploratory Data Analysis (EDA)**  
   - Visualized attrition distribution, salary effect, job satisfaction, etc.
   - Correlation heatmaps to identify strong predictors.
  
2. **Preprocessing**  
   - Converted categorical variables using one-hot encoding and label mapping.
   - Removed irrelevant columns.
   - Handled class imbalance via stratified train-test split.

3. **Modeling**  
   - **Logistic Regression** (with class weights balanced)  
   - **Random Forest Classifier**
   - Used metrics like precision, recall, F1-score to evaluate models due to class imbalance.

---

## ✅ Results

| Model              | Accuracy | Precision (Class 1) | Recall (Class 1) | F1-Score (Class 1) |
|-------------------|----------|---------------------|------------------|--------------------|
| Logistic Regression | 75%      | 0.35                | 0.62             | 0.44               |
| Random Forest       | 83%      | 0.40                | 0.09             | 0.14               |

- While Random Forest had higher overall accuracy, Logistic Regression performed better at detecting attrition (class 1).
- Trade-off highlights the importance of model selection based on business goals.

---

## 🚀 How to Run

1. Clone the repo  
   ```bash
   git clone https://github.com/yourusername/employee-attrition-prediction.git
   cd employee-attrition-prediction
   ```

2. Open the Jupyter/Colab notebook:  
   `project1.ipynb`

3. Run all cells and follow the analysis step-by-step.

---

## 📌 Key Learnings

- Importance of EDA before modeling
- Working with imbalanced classification
- Evaluating ML models beyond just accuracy
- Feature engineering and categorical encoding

---

## 🛠️ Tools Used

- Python (Pandas, NumPy, Seaborn, Matplotlib)
- Scikit-learn
- Jupyter Notebook / Google Colab

---

> 👨‍💻 Created with curiosity and a drive to understand employee behavior and HR analytics through data!
