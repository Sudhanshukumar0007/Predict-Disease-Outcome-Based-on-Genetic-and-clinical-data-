# Predict-Disease-Outcome-Based-on-Genetic-and-clinical-data-
🔍 Project Title:
Predict-Disease-Outcome-Based-on-Genetic-and-clinical-data-

📌 Objective:
To build a machine learning model that can predict whether a breast tumor is malignant or benign using clinical data and features derived from digitized images of breast mass.

📊 Dataset:
Source: Wisconsin Diagnostic Breast Cancer (WDBC) dataset

Features: 30 numerical attributes (mean, standard error, and "worst" of cell nucleus features like radius, texture, perimeter, area, smoothness, etc.)

Target: Diagnosis — Malignant (1) or Benign (0)

⚙️ Methodology:
Data Preprocessing:

Removed unnecessary columns like id.

Encoded categorical labels: 'M' → 1 (Malignant) and 'B' → 0 (Benign).

Scaled features using StandardScaler to normalize the input data for the model.

Train-Test Split:

Used train_test_split() to divide the data: 80% for training, 20% for testing.

Model:

Used Logistic Regression, a simple and effective linear classification algorithm.

Trained on the training data and evaluated on the test data.

Evaluation Metrics:

Accuracy

Classification Report (Precision, Recall, F1-score)

Confusion Matrix

Visualization of Confusion Matrix using a heatmap

📈 Results:
The model achieved high accuracy on the test data.

The confusion matrix and classification report show that it correctly identifies most malignant and benign cases.

Suitable for medical screening support, although not a substitute for clinical diagnosis.

🧠 Why Logistic Regression?
Interpretable and efficient.

Good baseline model for binary classification problems.

Performs well when the classes are linearly separable, as in this case.

📦 Tools & Libraries:
pandas, numpy for data handling

matplotlib, seaborn for visualization

scikit-learn for preprocessing, model training, and evaluation

