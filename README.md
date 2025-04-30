# Titanic Survival Prediction 🛳️

This project was developed as part of a Machine Learning course in 2025.  
The goal was to predict which passengers survived the Titanic disaster using logistic regression, with a strong focus on data exploration and feature engineering.

## 📌 Objective
Perform binary classification using the Kaggle Titanic dataset and a logistic regression model.

## 🔍 Key Steps

### 1. 🧪 Exploratory Data Analysis (EDA)
- Investigated missing data, outliers, and correlations
- Analyzed how features like age, fare, gender, and family size impact survival
- Visualized distributions and relationships using plots

### 2. 🛠️ Feature Engineering
- Created new features such as:
  - `FamilySize` (SibSp + Parch + 1)
  - `IsAlone` (derived from FamilySize)
  - `Title` extracted from passenger names (Mr, Miss, etc.)
- Handled missing data and encoded categorical variables
- Scaled numerical features

### 3. 🧠 Model Building
- Used logistic regression with `scikit-learn`
- Split data into temporary train and validation sets
- Tuned hyperparameters and evaluated using validation accuracy

### 4. 📊 Evaluation
- Confusion Matrix, Accuracy, Precision, Recall, F1-score
- Visualizations of training vs validation performance

### 5. 🏁 Submission
- Submitted results to Kaggle for evaluation
- Tracked performance on the leaderboard

## 🛠️ Technologies Used
- Python  
- scikit-learn  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Jupyter Notebook / Kaggle Notebook

## 📁 Files
- `Titanic.ipynb` – Full notebook with analysis and model
- `submission.csv` – Kaggle submission file
- `report.html` – Optional HTML version of the notebook

## 🧠 What I Learned
- The importance of feature engineering for improving model performance
- How to structure a machine learning pipeline from raw data to evaluation
- Practical usage of logistic regression for binary classification

## 🔁 Follow-up Work
This project served as the foundation for a more advanced version that includes multiple classification models and feature selection techniques:  
➡️ [Titanic Classification Ensemble](https://github.com/Itamar-Hadad/titanic-classification-ensemble)

---

## 👤 Author
**Itamar Hadad**  
B.Sc. Computer Science Student – Afeka College  
📧 hzitamar4@gmail.com  
[LinkedIn](https://www.linkedin.com/in/itamar-hadad)

