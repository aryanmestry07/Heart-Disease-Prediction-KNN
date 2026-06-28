# Heart Disease Prediction using K-Nearest Neighbors (KNN)

## Overview

This project demonstrates the implementation of the **K-Nearest Neighbors (KNN)** classification algorithm to predict the likelihood of heart disease based on patient health data.

The project follows a complete machine learning workflow, including data preprocessing, feature scaling, model training, hyperparameter tuning, pipeline creation, and performance evaluation using Scikit-learn.

---

## Dataset

* **Dataset:** Heart Disease Dataset
* **Problem Type:** Binary Classification
* **Target Variable:**

  * `0` → No Heart Disease
  * `1` → Heart Disease

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

---

## Machine Learning Workflow

1. Data Loading
2. Data Preprocessing
3. Train-Test Split
4. Feature Scaling using `StandardScaler`
5. K-Nearest Neighbors (KNN) Classification
6. Hyperparameter Tuning using `GridSearchCV`
7. Pipeline Implementation
8. Model Evaluation

---

## Concepts Covered

* K-Nearest Neighbors (KNN)
* Euclidean & Manhattan Distance
* Feature Scaling
* StandardScaler
* Hyperparameter Tuning
* GridSearchCV
* Pipeline
* Cross Validation
* Classification Report
* Confusion Matrix
* Accuracy, Precision, Recall, and F1-Score

---

## Model Evaluation

The model was evaluated using:

* Accuracy Score
* Precision Score
* Recall Score
* F1-Score
* Classification Report
* Confusion Matrix

---

## Project Structure

```
Heart-Disease-Prediction-KNN/
│
├── data/
│   └── heart.csv
│
├── notebook/
│   └── knn.ipynb
│
├── images/
│   ├── confusion_matrix.png
│   ├── accuracy_vs_k.png
│   └── classification_report.png
│
├── README.md
└── requirements.txt
```

---

## Key Learning Outcomes

* Implemented the KNN classification algorithm from scratch using Scikit-learn.
* Understood the importance of feature scaling for distance-based algorithms.
* Used GridSearchCV to identify the optimal value of K and other hyperparameters.
* Built a Pipeline to automate preprocessing and model training while preventing data leakage.
* Evaluated model performance using multiple classification metrics.

---

## Future Improvements

* Compare KNN with Logistic Regression, Decision Tree, Random Forest, and SVM.
* Perform feature selection.
* Experiment with different distance metrics and hyperparameters.
* Deploy the trained model using Flask or FastAPI.

---

## Author

**Aryan Mestry**

Aspiring AI & Machine Learning Engineer passionate about building practical machine learning projects and continuously improving problem-solving skills.

Feel free to connect with me on LinkedIn and explore my GitHub repositories.
