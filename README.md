# Breast Cancer Prediction

Machine learning classification of breast cancer tumors based on cell measurements.

---

## About

The goal of this project is to classify breast tumors as **benign (B)** or **malignant (M)**
based on numerical measurements of cell nuclei obtained from biopsies.

This project was developed as a semestral assignment for **IB031 – Introduction to Machine Learning**.

---

## Dataset

**Wisconsin Breast Cancer Dataset**

| | |
|---|---|
| Source | [golianr/BreastCancerCellsDataset](https://github.com/golianr/BreastCancerCellsDataset) |
| Samples | 568 patients |
| Features | 30 numerical |
| Target | `diagnosis` — B (benign) / M (malignant) |

For each of the 10 cell properties (radius, texture, perimeter, area, smoothness, compactness, concavity, concave points, symmetry, fractal_dimension), three statistics are available: `_mean`, `_se`, `_worst`.

---

## Project structure

```
breast-cancer-prediction
 ┣ Breast_Cancer_Prediction.ipynb   # Main notebook
 ┗ README.md
```

### Notebook contents

| Section | Description |
|---------|-------------|
| 1. Imports | Libraries and dependencies |
| 2. Constants | Dataset URL, feature list |
| 3. Data loading & cleaning | Dataset processing functions |
| 4. Dataset description | Column overview and meaning |
| 5. EDA | Statistics, histograms, heatmap, boxplots |
| 6. Preprocessing | Train/test split, imputation, standardization |
| 7. Model | Logistic Regression — training, interpretation, evaluation |
| 8. Conclusion | Results and findings |

---

## Model

### Logistic Regression

Logistic Regression predicts the probability of a malignant tumor using the sigmoid function.
If the output is > 0.5, the sample is classified as malignant.

**Preprocessing pipeline:**
- Missing values → filled with median (`SimpleImputer`)
- Features → standardized to mean 0, std 1 (`StandardScaler`)
- Train/test split → 80% / 20%, stratified

---

## Getting started

### Requirements

```bash
pip install numpy pandas matplotlib seaborn scikit-learn openpyxl
```

### Run the notebook

```bash
jupyter notebook Breast_Cancer_Prediction.ipynb
```

> The dataset is downloaded automatically from GitHub when the notebook is run.

---

## 👤 Author

**Richard Golian** — IB031 Semestral Project
