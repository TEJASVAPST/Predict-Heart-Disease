# Predict-Heart-Disease
# ❤️ Heart Disease Prediction using Logistic Regression

This project aims to predict whether a person is likely to have heart disease based on various medical features using **Logistic Regression**, a supervised machine learning algorithm.

---

## 📁 Dataset

The dataset contains anonymized patient records with features such as:

- Age
- Gender
- Chest pain type
- Resting blood pressure
- Cholesterol level
- Fasting blood sugar
- Resting ECG results
- Maximum heart rate achieved
- Exercise-induced angina
- ST depression
- Slope of ST segment
- Number of major vessels
- Thalassemia
- **Target**: 0 = No Heart Disease, 1 = Has Heart Disease

> 📄 Format: CSV  
> 📊 Rows: Patients, Columns: Medical attributes

---

## ⚙️ Methodology

1. **Data Loading & Preprocessing**
   - Load CSV using `pandas`
   - Handle missing values (if any)
   - Separate features (`X`) and target (`y`)
   - Scale features using `StandardScaler`

2. **Splitting Dataset**
   - Split data into training (80%) and testing (20%) sets using `train_test_split`

3. **Model Training**
   - Train Logistic Regression using `sklearn.linear_model.LogisticRegression`

4. **Model Evaluation**
   - Predict using `model.predict()`
   - Evaluate using:
     - Accuracy
     - Precision
     - Recall
     - Confusion Matrix (with Seaborn heatmap)

---

## 🧪 Evaluation Metrics

- **Accuracy**: Overall correct predictions
- **Precision**: Correct positive predictions / Total predicted positives
- **Recall**: Correct positive predictions / Actual positives
- **Confusion Matrix**: Shows TP, FP, FN, TN

---

## 📊 Visualization

A **confusion matrix heatmap** is plotted using `seaborn.heatmap()` to visualize prediction results clearly.

---

## 🛠️ Technologies Used

- Python
- NumPy
- Pandas
- scikit-learn
- Matplotlib
- Seaborn

---
 ## Output

![image](https://github.com/user-attachments/assets/241d8400-a7a8-436f-af07-8afd99a089e9)


