# Titanic Survival Prediction – Beginner ML Project

This project explores the Titanic dataset to build a machine learning model that predicts whether a passenger survived or not. It was developed as a beginner-level portfolio project for learning data science and machine learning fundamentals.

---

## Project Goals

- Load and explore the Titanic dataset
- Clean and preprocess the data (handle missing values, encode categorical variables, drop irrelevant columns)
- Train and evaluate classification models (Logistic Regression, Decision Tree)
- Compare model performance
- Learn best practices for data science workflows

---

## Project Structure
This project is organized as follows:

titanic-survival-prediction/
├── data/ ← Contains raw data (train.csv). This folder is ignored by GitHub using .gitignore.
├── notebook.ipynb ← Jupyter notebook containing code for data cleaning, EDA, model training, and evaluation.
├── README.md ← Project overview and documentation.
└── .gitignore ← Specifies files and folders to be ignored by Git (e.g., data/ and .ipynb_checkpoints)
---

## Models Tested

| Model               | Accuracy | F1 Score (Survived) |
|--------------------|----------|---------------------|
| Logistic Regression| 0.80     | 0.76                |
| Decision Tree      | 0.72     | 0.67                |

Logistic Regression gave the best overall performance.

---

## Tools Used

- Python
- pandas, NumPy
- matplotlib, seaborn
- scikit-learn
- Jupyter Notebook

---

## Key Skills Practiced

- Exploratory Data Analysis (EDA)
- Feature engineering & scaling
- Classification modeling
- Model evaluation (accuracy, precision, recall, F1)
- Version control with Git + GitHub

---

## Author

**Ouzren El Mehdi**  
Master’s student in Computer Engineering – Data Science & AI specialization  
Warsaw, Poland

---

## 🔗 Dataset

Kaggle Titanic dataset: [https://www.kaggle.com/competitions/titanic](https://www.kaggle.com/competitions/titanic)

