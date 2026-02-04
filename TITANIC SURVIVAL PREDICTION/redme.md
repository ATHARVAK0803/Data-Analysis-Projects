# 🚢 Titanic Survival Prediction using Machine Learning & SMOTE

##  Project Overview
This project predicts whether a passenger survived the Titanic disaster using
machine learning techniques.  
It also addresses **class imbalance** in the dataset using **SMOTE (Synthetic Minority Oversampling Technique)** to improve model performance on the minority class.

---

##  Problem Statement
Given passenger details such as age, gender, class, and fare, build a machine learning
model to predict survival (`Survived = 1`) or non-survival (`Survived = 0`).

---

##  Dataset
- **Source:** Kaggle Titanic Dataset  
- **Files Used:**
  - `train.csv`
  - `test.csv` (optional)

### Target Variable
- `Survived`  
  - 0 → Did not survive  
  - 1 → Survived  

### Features Used
- `Pclass`
- `Sex`
- `Age`
- `SibSp`
- `Parch`
- `Fare`
- `Embarked`

---

##  Technologies Used
- Python  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Scikit-learn  
- Imbalanced-learn (SMOTE)

---

##  Data Preprocessing
- Handling missing values (Age, Embarked)
- Dropping irrelevant columns (Name, Ticket, Cabin)
- Encoding categorical variables
- Feature scaling using `StandardScaler`
- Train-test split

---

## ⚖️ Handling Class Imbalance
The dataset is imbalanced, with more non-survivors than survivors.

To solve this:
- **SMOTE** is applied on the training data only
- Generates synthetic samples for the minority class
- Improves recall and F1-score

---

##  Machine Learning Models
- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier
- Support Vector Machine (optional)

---

##  Model Evaluation
Metrics used:
- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix

Performance comparison is done **before and after applying SMOTE**.

---

##  Results
- SMOTE improved minority-class prediction
- Random Forest achieved the best overall performance
- Reduced bias towards the majority class

---

##  Conclusion
This project demonstrates the importance of handling class imbalance in real-world
datasets. SMOTE significantly improves classification results when predicting rare outcomes.

---

##  Future Improvements
- Hyperparameter tuning
- Feature engineering
- Cross-validation
- Model deployment using Flask or Streamlit

---

## Author
**Atharva Kulkarni**  
Machine Learning Project  
