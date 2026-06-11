# Titanic Survival Prediction - Machine Learning Project

## 📌 Objective

The objective of this project is to build and evaluate machine learning models that predict whether a passenger survived the Titanic disaster based on features like age, gender, class, and fare.

---

## 📊 Dataset

* Dataset: Titanic Survival Prediction (Kaggle)
* Type: Classification Problem
* Target Variable: `Survived` (0 = No, 1 = Yes)

---

## 🛠 Tools & Libraries Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

---

## ⚙️ Project Workflow

### 1. Data Preprocessing

* Handled missing values (Age, Embarked)
* Dropped irrelevant columns (Name, Ticket, Cabin, PassengerId)
* Encoded categorical features (Sex, Embarked)
* Split dataset into training (80%) and testing (20%)

### 2. Feature Engineering

* Selected relevant features impacting survival
* Removed unnecessary columns to improve model performance

### 3. Model Training

Three models were trained:

* Logistic Regression
* Random Forest Classifier
* K-Nearest Neighbors (KNN)

### 4. Model Evaluation

Models were evaluated using:

* Accuracy
* Precision
* Recall
* F1 Score

---

## 📈 Model Comparison

| Model               | Accuracy | Precision | Recall | F1 Score |
| ------------------- | -------- | --------- | ------ | -------- |
| Logistic Regression | 0.810056 | 0.785714  | 0.7432 | 0.763889 |
| Random Forest       | 0.810056 | 0.777778  | 0.7567 | 0.767123 |
| KNN                 | 0.703911 | 0.684211  | 0.527  | 0.595420 |


## 🏆 Best Model

Random Forest performed the best among all models due to its ability to capture complex patterns and reduce overfitting.

---

## 📉 Confusion Matrix

A confusion matrix was plotted for the best model to evaluate prediction performance.

---

## 🧠 Key Insights

* Gender and passenger class significantly impact survival chances
* Younger passengers had higher survival probability
* Random Forest handled feature interactions better than other models

---

## 📌 Conclusion

Three machine learning models were implemented and compared in this project. Random Forest achieved the best performance in terms of accuracy and F1 score. Proper preprocessing and feature selection played a crucial role in improving model performance. This project highlights the importance of comparing multiple models to select the best one.

---

## 🔗 Project Links

* Google Colab Notebook: https://colab.research.google.com/drive/1RWeXgCHhnHo-XKeAVYdbiDjIZkuffJbz?usp=sharing
* GitHub Repository: https://github.com/DEVANG-60/Titanic-ML-Project.git

---

## 👨‍💻 Author

* Devang Shinde
