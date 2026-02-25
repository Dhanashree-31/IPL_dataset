# 🏏 IPL Data Analysis & Match Outcome Prediction (ML Project)

A complete data science project that analyzes IPL historical match data and builds machine learning models to predict match-related outcomes using structured datasets. The project focuses on exploratory data analysis (EDA), feature engineering, model training, and performance benchmarking using ensemble learning techniques.

---

## 🚀 Project Objective

- Analyze IPL match data and uncover performance patterns  
- Build regression-based ML models for prediction  
- Evaluate models on training and test data  
- Select the best-performing model based on accuracy  

---

## 🧠 Models Used

| Model         | Description                     |
|---------------|----------------------------------|
| Random Forest | Ensemble tree-based regressor    |
| XGBoost       | Gradient boosting regressor      |

---

## 📊 Model Accuracy (R² Score Only)

### 🔹 Random Forest Regressor

| Dataset | Accuracy (R²) |
|--------|----------------|
| Train  | **99.33%**     |
| Test   | **95.00%**     |

### 🔹 XGBoost Regressor

| Dataset | Accuracy (R²) |
|--------|----------------|
| Train  | **90.07%**     |
| Test   | **87.53%**     |

---

## 🏆 Final Model Selection

**Best Model: Random Forest Regressor**

**Reason:**
- Higher training accuracy  
- Higher testing accuracy  
- Better generalization  
- Lower error on unseen data  

Random Forest is selected as the final production model for this dataset.

---

## 🔎 Key Insights

- Random Forest generalizes better than XGBoost for this dataset  
- The train-test accuracy gap is within acceptable limits  
- Feature engineering significantly improved model performance  
- Ensemble methods outperform simpler baseline models  

---

## ⚙️ How to Run

### Step 1: Install Dependencies
```bash
pip install pandas numpy scikit-learn xgboost matplotlib seaborn
```

---

### Step 2: Run Notebook

jupyter notebook ipl_data_analysis.ipynb

## 🧩 Tech Stack

- Python  
- Pandas, NumPy  
- Scikit-learn  
- XGBoost  
- Matplotlib, Seaborn  
- Jupyter Notebook  

---

## 📌 Future Enhancements

- Hyperparameter tuning with Optuna  
- Add SHAP-based model explainability  
- Build Streamlit web app for live predictions  
- Deploy model using REST API  
- Add season-wise trend analysis  

---

## 👩‍💻 Author

**Dhanashree Pawar**  
Machine Learning & Data Science  

---

## 📜 License

This project is for educational and research purposes.  
You are free to fork and extend this work.
