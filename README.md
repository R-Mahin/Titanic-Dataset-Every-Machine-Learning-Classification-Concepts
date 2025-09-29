# 🚢Titanic Survival Prediction 
![](https://storage.googleapis.com/kaggle-competitions/kaggle/3136/logos/header.png?GoogleAccessId=web-data@kaggle-161607.iam.gserviceaccount.com&Expires=1759205363&Signature=srQdGArmZpPZx6nqsX%2BeSSp7jv0p7zlAlZ8sdPWNzz1sf1BrHt9B%2FU3cep6MDgMM03I0ykhcMaTNlL0fSPW1YaC8pOAuh%2FPYODBlPfGnecGgLxMYuSyty1%2FIXE1hoO6IStZLA8aQid6n%2BwUzOOhJA8%2B42%2BlOA5JKlEVtRZFV4MBIX7MD6wgeaJeVMpQ31aW0s8EfZP9C6l1%2BzFQUW%2Bkw3vlDdalmUcQ742DPk63DcMj3ehZAVULe0mDxzdYLsDflj%2FLqmHzOmSp09BA0Y9TwEwN40B%2BDPEuQj3HHlhz%2FLwIi%2BDIRQQkKWoYdRI9lR4Zoeq7ATQbGRmfsw2t1mvbiaQ%3D%3D)

This project predicts passenger survival on the Titanic dataset using various machine learning algorithms.
It includes feature preprocessing, model training, and evaluation with XGBoost, Random Forest, Logistic Regression, KNN, SVM, and ensemble methods like Bagging, Voting, and AdaBoost.

## 📊 Dataset
The dataset is taken from [Kaggle’s Titanic Competition](https://www.kaggle.com/c/titanic/data)
Files needed:
- `train.csv` (for training the model)
- `test.csv` (for evaluation/prediction)

---

## 📝 Steps Outline

### 1. Understanding the Data
- Loaded the Titanic dataset and explored its structure.  
- Defined the **target variable**: `Survived`.  
- Identified and handled missing values (`Age`, `Embarked`, `Cabin`) and outliers.  

### 2. Exploratory Data Analysis (EDA)
- Visualized feature distributions and survival rates by passenger class, gender, and age.  
- Checked correlations between features and the target variable.  
- Observed survival patterns (e.g., women and children had higher survival chances).  

### 3. Data Preprocessing 
- Scaled using **StandardScaler** 
- Applied **One-Hot Encoding** for categorical variables (`Sex`, `Embarked`, etc.).  


### 4. Modeling and Comparison
Trained and evaluated the following models:  
- Logistic Regression  
- Random Forest  
- Support Vector Machine (SVM)  
- K-Nearest Neighbors (KNN)  
- Decision Tree  
- Gradient Boosting
- Ensemble: Voting, Bagging, Boosting 

**Metrics used:**  
- Accuracy  


### 5. Model Selection
- **Voting using Bagging** achieved the highest accuracy score on kaggle of **0.78229**.  
 

### 6. Submission
- Generated predictions on the test dataset.  
- Prepared `submission.csv` in the required Kaggle format.  

---

## 📊 Results
- **Best Model**: Voting using bagging  
- **Accuracy score on kaggle**: 0.78229  
- Kaggle submission file: `submission.csv`  

---

## ⚙️ Technologies Used
- Python  
- Pandas, NumPy  
- Scikit-learn  
- Matplotlib, Seaborn  
- XGBoost 

---


