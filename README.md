# Seed Classification Using Random Forest

This project implements a **Machine Learning model using Random Forest Classifier** to predict the **type of agricultural seed** based on its physical characteristics.  
The project covers the **complete ML pipeline** including **data preprocessing, visualization, model training, evaluation, and model saving**, making it ideal for **placements, interviews, and academic submissions**.

---

## Project Overview

- **Algorithm Used:** Random Forest Classifier  
- **Domain:** Machine Learning / Data Science / Agriculture Analytics  
- **Programming Language:** Python  
- **Platform:** Google Colab  
- **Version Control:** Git & GitHub  

---

## Dataset Information

- **Dataset Name:** Seeds Dataset  
- **Total Samples:** 210  
- **Number of Features:** 7  
- **Target Classes:** 3 seed types  

### Features
- Area  
- Perimeter  
- Compactness  
- Kernel Length  
- Kernel Width  
- Asymmetry Coefficient  
- Groove Length  

---

## Data Visualization & Exploratory Data Analysis

Data visualization is performed to understand feature distributions, relationships, and model behavior.

### 🔹 Visualizations Included
- Feature importance plot  
- Confusion matrix heatmap  
- Feature distribution analysis  
- Correlation analysis  

Libraries used:
- **Matplotlib**
- **Seaborn**

---

### Feature Importance (Random Forest)

<img width="708" height="541" alt="image" src="https://github.com/user-attachments/assets/6dedc3d4-ef3a-4322-8f26-0d5f0a3e7f2e" />

**Insights:**
- **Area** and **Perimeter** contribute the most to seed classification.
- **Groove Length** and **Kernel Width** have moderate influence.
- **Compactness** has the least impact.
  
Random Forest inherently provides feature importance, improving model interpretability.

---

### Confusion Matrix

<img width="501" height="393" alt="image" src="https://github.com/user-attachments/assets/4f77ea1d-7589-4f71-afb8-49ae581c76e2" />

**Insights:**
- Majority of predictions lie on the diagonal, indicating **high accuracy**.
- Very few misclassifications are observed.
- The model performs consistently across all three seed classes.

---

## Machine Learning Workflow

1. Load and inspect the dataset  
2. Perform data visualization and exploratory analysis  
3. Preprocess data  
   - Label encoding of target variable  
   - Feature scaling using StandardScaler  
4. Split dataset into training and testing sets  
5. Train Random Forest classifier  
6. Evaluate model performance  
   - Accuracy score  
   - Classification report  
   - Confusion matrix  
7. Analyze feature importance  
8. Save trained model using Pickle  

---

## Model Details

- **Model:** RandomForestClassifier  
- **Number of Trees:** 100  
- **Evaluation Metric:** Accuracy  

### Why Random Forest?
- Handles non-linear data efficiently  
- Reduces overfitting through ensemble learning  
- Provides built-in feature importance  
- Performs well on structured tabular datasets  

---

## Results & Performance

- Achieved **high classification accuracy**
- Strong performance across all seed categories
- Minimal misclassification as shown in the confusion matrix

