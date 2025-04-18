# Predict-Disease-Outcome-Based-on-Genetic-and-clinical-data-

# 🧠 Breast Cancer Prediction using Logistic Regression

## 📌 Problem Statement

Breast cancer is one of the most common types of cancer among women worldwide. Early detection and accurate diagnosis are critical to improving survival rates. The goal of this project is to build a machine learning model that can **classify tumors as either malignant or benign** based on various features computed from a digitized image of a fine needle aspirate (FNA) of a breast mass.

## 🧪 Dataset

The dataset used is the **Breast Cancer Wisconsin (Diagnostic) Dataset**, which contains 569 samples with 30 numeric features related to characteristics of the cell nuclei present in the image. The target variable is:
- `M` = Malignant (1)
- `B` = Benign (0)

## ⚙️ Methodology

1. **Data Preprocessing**
   - Removed irrelevant columns like `id` and `Unnamed: 32`
   - Encoded the diagnosis column into binary format (0 for benign, 1 for malignant)
   - Normalized feature data using `StandardScaler` to bring all features onto a similar scale
   - Split the dataset into training and testing sets using `train_test_split` (80/20 split)

2. **Modeling**
   - Used **Logistic Regression**, a linear model for binary classification
   - Trained the model on the training set and tested on the unseen test data

3. **Evaluation**
   - Evaluated the model using:
     - **Accuracy Score**
     - **Classification Report** (Precision, Recall, F1-Score)
     - **Confusion Matrix** (visualized with Seaborn)

## 📊 Results

- The Logistic Regression model performed well on the test data.
- **Accuracy:** 96.49%
- The confusion matrix showed that the model was able to correctly classify the majority of benign and malignant cases.
- Precision and recall values were also high, indicating good performance across both classes.

![Screenshot 2025-04-18 145025](https://github.com/user-attachments/assets/2b48ec6f-ad88-4ff7-81ce-541e395745a1)


---

## 💡 Future Work

- Implement a Neural Network (Multi-layer Perceptron) and compare performance
- Use cross-validation and hyperparameter tuning
- Experiment with other algorithms like SVM, Random Forest, and Gradient Boosting

## 🛠️ Tech Stack

- Python
- Pandas
- NumPy
- Scikit-learn
- Seaborn & Matplotlib


