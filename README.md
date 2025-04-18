# 🩺 Disease Diagnosis Prediction using Machine Learning

This project aims to build a machine learning model to predict the likelihood of diseases such as **heart disease** or **diabetes** based on patient medical records. The ultimate goal is to provide actionable insights that support early diagnosis and prevention.

## 📁 Dataset

- **Dataset Used:** [Heart Disease Dataset](https://www.kaggle.com/datasets/johnsmith88/heart-disease-dataset)
- **Format:** CSV
- **Target Variable:** `target` (1 = disease present, 0 = no disease)

## 🔍 Project Workflow

### 1. Exploratory Data Analysis (EDA)
- Analyzed data distribution, missing values, and correlations.
- Visualized features using seaborn and matplotlib (e.g., heatmaps, histograms).

### 2. Feature Engineering
- Removed irrelevant features.
- Scaled data using `StandardScaler`.
- Performed feature selection based on correlation and model-based importance.

### 3. Model Training
Trained and compared the following models:
- `Logistic Regression`
- `Random Forest Classifier`
- `Support Vector Machine (SVM)`
- (Optionally: Neural Networks)

### 4. Model Evaluation
- **F1 Score:** Measures model accuracy considering precision & recall.
- **AUC-ROC Curve:** Evaluates classifier performance.
- **Confusion Matrix:** Visual check of True Positives and False Negatives.

### 5. Feature Importance
- Identified key contributing factors using Random Forest importance scores.
- Visualized using bar plots.

## 📈 Results

- **Best Performing Model:** Random Forest
- **F1 Score:** 0.89
- **AUC-ROC:** 0.94

## 🩺 Insights for Healthcare Professionals

- **Top Risk Factors Identified:**
  - Age
  - Chest Pain Type
  - Cholesterol Level
  - Resting Blood Pressure
- **Recommendations:**
  - Patients with abnormal values in these features should receive timely screening.
  - This tool assists in early disease detection and can improve clinical decision-making.

## 📦 Libraries Used

- `pandas`, `numpy`, `matplotlib`, `seaborn`
- `scikit-learn`
- `matplotlib`, `seaborn` (for visualization)

