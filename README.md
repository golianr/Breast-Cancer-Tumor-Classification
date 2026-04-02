# 🧠 Breast Cancer Tumor Classification

This project focuses on classifying breast cancer tumors as:
- **Benign (B)** – non-cancerous  
- **Malignant (M)** – cancerous  

The goal is to use a machine learning model to predict the diagnosis based on cell features.

---

## 📊 Dataset

The project uses the **Wisconsin Breast Cancer Dataset**.

- 👥 Number of samples: ~568 patients  
- 🔢 Features: 30 numerical attributes  
- 🎯 Target: `diagnosis` (B / M)

Each feature is represented in three forms:
- `_mean` – average value  
- `_se` – standard error  
- `_worst` – worst (largest) value  

---

## 🔍 Project Workflow

### 1. Data Loading & Cleaning
- removed unnecessary columns  
- formatted the diagnosis column  
- checked for missing values  

### 2. Exploratory Data Analysis (EDA)
- class distribution visualization  
- feature histograms  
- correlation heatmap  
- boxplots  

### 3. Data Preprocessing
- train/test split (80/20)  
- handling missing values (`SimpleImputer`)  
- feature scaling (`StandardScaler`)  

### 4. Model
Used model:
- **Logistic Regression**

Why this model:
- simple and fast  
- interpretable  
- suitable for binary classification  

---

## 🤖 Results

The model achieved solid performance in classifying tumors.

Evaluation metrics:
- Accuracy  
- Confusion Matrix  
- Classification Report  

---

## 📈 Technologies Used

- Python  
- pandas, numpy  
- matplotlib, seaborn  
- scikit-learn  

---

## 🧠 What I Learned

- working with real-world datasets  
- data cleaning and preprocessing  
- data visualization  
- training machine learning models  
- evaluating model performance  

---

## 🚀 Future Improvements

- try more advanced models (Random Forest, SVM)  
- hyperparameter tuning  
- cross-validation  
- deploy as a web application  

---

## 📂 How to Run

```bash
git clone https://github.com/golianr/Breast-Cancer-Tumor-Classification.git
cd Breast-Cancer-Tumor-Classification
