# Breast Cancer Prediction

Machine learning classification project for predicting whether breast cancer tumors are **benign (B)** or **malignant (M)** based on numerical cell measurements.

This project was developed as a semestral assignment for **IB031 – Introduction to Machine Learning**.

---

## About

The goal of this project is to build, train, evaluate, and compare machine learning models for binary classification of breast cancer tumors.

The models use numerical measurements of cell nuclei obtained from biopsy samples. The classification task is medically sensitive, because false negative predictions — malignant tumors classified as benign — are especially risky. Therefore, the project evaluates models not only using accuracy, but also precision, recall, F1-score, confusion matrices, and ROC analysis.

---

## Dataset

**Wisconsin Breast Cancer Dataset**

| Property | Description |
|---|---|
| Source | [golianr/BreastCancerCellsDataset](https://github.com/golianr/BreastCancerCellsDataset) |
| Samples | 568 patients |
| Features | 30 numerical features |
| Target | `diagnosis` — B benign / M malignant |

For each of the 10 cell properties, three statistics are available: `_mean`, `_se`, and `_worst`.

The measured properties include:

- radius
- texture
- perimeter
- area
- smoothness
- compactness
- concavity
- concave points
- symmetry
- fractal dimension

---

## Project Structure

```text
breast-cancer-prediction
 ┣ Breast_Cancer_Prediction.ipynb   # Main Jupyter Notebook
 ┣ README.md                        # Project documentation
 ┗ documentation.pdf                # Final project documentation, if included
