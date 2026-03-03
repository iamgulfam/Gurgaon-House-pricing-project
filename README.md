# 🏠 House Price Prediction - Machine Learning

An end-to-end Machine Learning project that predicts house prices using structured housing data.  
This project demonstrates complete ML workflow including preprocessing, model training, evaluation, and automated prediction pipeline.

---

## 🚀 Project Overview

The objective of this project is to build a robust regression model capable of accurately predicting house prices based on multiple housing features.

This project includes:

- Comprehensive Exploratory Data Analysis (EDA)
- Data Cleaning & Missing Value Handling
- Feature Engineering & Feature Scaling
- Model Training & Comparison
- Cross-Validation & Performance Evaluation
- Feature Importance Analysis
- Automated ML Pipeline Implementation

---

## 📂 Project Structure

```
├── .vscode/
├── .gitattributes
├── .gitignore
├── housing.csv
├── input.csv
├── output.csv
├── feature_importances.csv
├── main.py
├── main_old.py
```

---

## 🔍 Exploratory Data Analysis (EDA)

- Analyzed feature distributions and correlations  
- Identified key housing patterns  
- Studied relationships between independent variables and target variable  
- Detected outliers and skewed features  

---

## 🧹 Data Preprocessing

- Handled missing values using **Median Imputation**
- Applied **Stratified Sampling** for balanced train-test split
- Scaled numerical features
- Encoded categorical features
- Built separate pipelines for:
  - Numerical features
  - Categorical features
- Combined into a complete preprocessing pipeline

---

## 🤖 Models Implemented

The following regression algorithms were trained and evaluated:

- Linear Regression  
- Decision Tree Regressor  
- Random Forest Regressor  

The best-performing model was selected based on evaluation metrics.

---

## 📊 Model Evaluation

Models were evaluated using:

- RMSE (Root Mean Squared Error)  
- MAE (Mean Absolute Error)  
- 10-Fold Cross Validation  

Final predictions were generated using the optimized model.

---

## 📈 Feature Importance

- Extracted and analyzed feature importance  
- Identified key factors influencing house prices  
- Saved results in `feature_importances.csv`

---

## ⚙️ ML Pipeline Implementation

- Implemented complete preprocessing + training workflow  
- Automated prediction generation  
- Saved optimized model using Joblib  
- Maintained clean, modular, and production-style code  

---

## ▶️ How to Run

1. Clone the repository:

```bash
git clone https://github.com/your-username/your-repo-name.git
```

2. Install dependencies:

```bash
pip install -r requirements.txt
```

3. Run the project:

```bash
python main.py
```

4. Predictions will be saved in:

```
output.csv
```

---

## 🛠 Technologies Used

- Python  
- Pandas  
- NumPy  
- Scikit-learn  
- Matplotlib  
- Seaborn  
- Joblib  

---

## 🎯 Key Highlights

✔ End-to-end Machine Learning workflow  
✔ Structured preprocessing pipeline  
✔ Cross-validation based model comparison  
✔ Feature importance analysis  
✔ Clean and maintainable code  

---

## 📌 Future Improvements

- Hyperparameter tuning using GridSearchCV  
- Model deployment using Flask or FastAPI  
- CI/CD integration  
- Model performance monitoring  

---

## 👨‍💻 Author

Gulfam Raza

If you found this project useful, consider giving it a ⭐
