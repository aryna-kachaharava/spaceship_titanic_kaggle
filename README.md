# Spaceship Titanic Classification 

Machine learning project for the Kaggle **Spaceship Titanic** competition.

The goal of this project is to predict whether a passenger was transported to another dimension during the Spaceship Titanic incident using demographic information and onboard service usage.

---

##  Project Overview

This project covers the complete machine learning workflow:

* Exploratory Data Analysis (EDA)
* Data cleaning and preprocessing
* Missing value handling
* Feature engineering
* Categorical encoding
* Model training and evaluation
* Comparison of several classification algorithms
* Kaggle competition submission

---

##  Dataset

The dataset is provided by the Kaggle competition:

**Target variable:**

* `Transported`

  * `True` – passenger was transported
  * `False` – passenger was not transported

**Features include:**

* Passenger age
* Home planet
* Destination
* Cabin information
* VIP status
* CryoSleep status
* Spending on onboard services:

  * RoomService
  * FoodCourt
  * ShoppingMall
  * Spa
  * VRDeck

---

##  Exploratory Data Analysis

The following analyses were performed:

* Class distribution analysis
* Missing values analysis
* Numerical feature distributions
* Correlation analysis
* Passenger demographics exploration
* Visualization of categorical and numerical variables

---

## ⚙️ Feature Engineering

Several new features were created to improve model performance:

* Total spending on onboard services
* Cabin deck extraction
* Cabin side extraction
* Group size and family-related features
* Binary indicators for passenger activity

Categorical variables were encoded and numerical features were scaled using preprocessing pipelines.

---

##  Models

The following machine learning models were trained and compared:

1. Logistic Regression
2. Random Forest Classifier
3. XGBoost Classifier

Evaluation metrics:

* Accuracy
* ROC-AUC
* Cross Validation

---

## 📈 Results

| Model               | Validation Accuracy |
| ------------------- | ------------------- |
| Logistic Regression | ~0.79               |
| Random Forest       | ~0.80               |
| XGBoost             | **~0.81**           |

**Best Kaggle Public Score:** **0.75847**

XGBoost achieved the best overall performance among the evaluated models.

---

##  Technologies

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* XGBoost
* Jupyter Notebook

---

## Repository Structure

```text
spaceship-titanic-classification/

├── spaceship_titanic.ipynb
├── README.md
├── requirements.txt
└── .gitignore
```

---

##  Future Improvements

* Hyperparameter optimization using GridSearchCV / Optuna
* More advanced feature engineering
* SHAP analysis for model interpretability
* Ensemble methods and stacking

---

##  Author

**Aryna Kachaharava**

Aspiring Machine Learning Engineer passionate about data science, machine learning, and building end-to-end ML projects.
