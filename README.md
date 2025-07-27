# 🚢 Titanic Survival Prediction using Machine Learning

Welcome to my Titanic Machine Learning project!  
This project dives into the iconic Titanic dataset to uncover real survival patterns using machine learning techniques.

---

## 📌 Overview

We often think of the Titanic tragedy in terms of luck or fate — but what happens when we let the data speak?  
In this project, I:

- Explored the data to discover trends and correlations.
- Built models using **Logistic Regression**, **Decision Tree**, and **Random Forest**.
- Performed **hyperparameter tuning** using GridSearchCV for optimal performance.
- Achieved a **94% accuracy** using tuned Logistic Regression.

---

## 🔍 Key Findings

- **Gender**: Females were much more likely to survive.
- **Pclass** and **Fare**: Wealth had a noticeable impact on survival chances.
- **Family Size**: Traveling with 2–4 family members gave a higher survival rate.

---

## 📊 Models Compared (after tuning)

| Model               | Accuracy |
|--------------------|----------|
| Logistic Regression| 94%      |
| Decision Tree      | ~89%     |
| Random Forest      | ~87%     |

*Note: All models were tuned using GridSearchCV for hyperparameter optimization.*

---

## 🛠️ Tech Stack

- Python
- Jupyter Notebook
- Pandas, NumPy
- Seaborn, Matplotlib
- Scikit-learn

---

## 🚀 How to Run

1. Clone this repository:

   ```bash
   git clone https://github.com/mohit1221iitian/Titanic_ML.git
   cd Titanic_ML
   ```
2. Open the notebook:

   ```bash
   jupyter notebook code.ipynb
   ```

3. Download the dataset from the link in `dataset_link.txt` and place it in the same directory .

---

## 📂 Files Included

```
.
├── code.ipynb           # Main Jupyter Notebook
├── dataset_link.txt     # Link to Titanic dataset (Kaggle)
├── report.pdf           # Full PDF report with analysis & results
└── README.md            # This file
```

---

## 📘 Detailed Report

For a full walk-through of the project (EDA, models, hyperparameter tuning, and visualizations), check out:  
📄 [`report.pdf`](./report.pdf)

---

## 💡 Possible Improvements

- Try ensemble methods like XGBoost or LightGBM
- Deploy as an interactive web app using Streamlit or Flask
- Add SHAP or LIME for model explainability

---

## 🙋‍♂️ Let's Connect

If you liked this project or have feedback/suggestions, feel free to raise an issue or connect!

---

## 🏷️ Tags

`#TitanicML` `#LogisticRegression` `#HyperparameterTuning` `#MachineLearning` `#StudentProject` `#DataScience`
