## 🌧 Rainfall Prediction using Machine Learning
This project predicts rainfall based on meteorological data using multiple machine learning algorithms. It demonstrates a complete end-to-end ML workflow, including data preprocessing, model training, evaluation, and comparison.

---

## 📌 Project Overview
Accurate rainfall prediction is crucial for agriculture, water management, and disaster prevention. This project leverages various regression models to forecast rainfall, comparing their performance to determine the most effective approach.

---

## 📂 Dataset
- Contains weather and climate-related features.

- Preprocessing steps include handling missing values, encoding categorical variables.

- The dataset was split into training and testing sets for evaluation.

---

## ⚙ Workflow
**1. Data Preprocessing**

- Handle missing values (NaN)

- Encode categorical variables

**2. Model Training**
Models implemented:

- Linear Regression

- Random Forest Regressor

- Gradient Boosting Regressor

- XGBoost Regressor

- Support Vector Regressor

**3. Model Evaluation**
Metrics used:

- Mean Squared Error (MSE)

- Mean Absolute Error (MAE)

- R² Score

**4. Hyperparameter Tuning**

- Grid Search

- Random Search

**5. Results Comparison**

- Models ranked based on R² score and error metrics.

---

## 📊 Results Summary
| Model                    |      MSE |    MAE |      R² |
| ------------------------ | -------: | -----: | ------: |
| Linear Regression   |     8.31 |   2.55 |  0.9995 |
| Gradient Boosting        |  3869.95 |  46.17 |  0.7708 |
| Random Forest            |  4324.12 |  48.24 |  0.7439 |
| XGBoost                  |  6084.04 |  57.37 |  0.6397 |
| Support Vector Regressor | 31060.72 | 134.40 | -0.8395 |

---

## 🛠 Technologies Used
- **Python**
- **Libraries:** Pandas, NumPy, Scikit-learn, XGBoost, Matplotlib, Seaborn

