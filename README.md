# 🏡 House Price Prediction using Machine Learning

## 📌 Project Overview

This project focuses on predicting house prices based on various features such as area, number of rooms, and other relevant factors. It demonstrates a complete machine learning workflow including data preprocessing, model training, evaluation, and optimization.

---

## 🎯 Objective

The main goal of this project is to build an accurate regression model that can estimate house prices using historical data.

---

## 📂 Dataset

* The dataset contains multiple features related to house properties.
* Target variable: **price**
* Features may include:

  * Area (square feet)
  * Number of bedrooms
  * Number of bathrooms
  * Location (if available)

---

## ⚙️ Technologies Used

* Python 🐍
* Pandas
* NumPy
* Scikit-learn
* Matplotlib / Seaborn

---

## 🔄 Project Workflow

### 1. Data Preprocessing

* Handling missing values
* Data cleaning

### 2. Train-Test Split

* Splitting dataset into training and testing sets (80/20)

### 3. Model Building

Models used:

* Linear Regression
* Decision Tree Regressor
* Random Forest Regressor

### 4. Model Evaluation

Evaluation metrics used:

* Mean Absolute Error (MAE)
* Root Mean Squared Error (RMSE)
* R² Score

### 5. Cross Validation

* 5-Fold Cross Validation used to ensure model stability

### 6. Hyperparameter Tuning

* GridSearchCV used to find best parameters for Random Forest

---

## 🏆 Best Model

* **Random Forest Regressor** performed best after tuning
* Selected using cross-validation score

---

## 📊 Results

Example:

* R² Score: ~0.86+ (depends on dataset)
* Model shows good generalization and performance

---

## 💾 Model Saving

Final model is saved using:

```python
joblib.dump(best_model, 'model.pkl')
```

---

## 🚀 How to Run

1. Clone the repository:

```bash
git clone https://github.com/JethlojaUtam/House-Price-Prediction.git
cd House-Price-Prediction
```

2. Install dependencies:

```bash
pip install -r requirements.txt
```

3. Run the notebook:

```bash
jupyter notebook
```

---

## 🔮 Future Improvements

* Add more features (feature engineering)
* Deploy using Streamlit
* Improve accuracy with advanced models

---

## 📌 Conclusion

This project demonstrates a complete end-to-end machine learning pipeline for house price prediction. It highlights the importance of model selection, evaluation, and tuning in building an effective predictive system.

---

## 🙌 Author

**Jethloja Utam**

---
