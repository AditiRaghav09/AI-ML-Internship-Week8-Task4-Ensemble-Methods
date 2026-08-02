# Introduction to Ensemble Methods

## Project Overview

This project demonstrates the implementation and comparison of ensemble learning techniques using the Breast Cancer Wisconsin Dataset.

Three machine learning models were trained and evaluated:

- Decision Tree (Baseline)
- Random Forest
- Gradient Boosting

The objective was to compare the performance of a single decision tree with ensemble methods using classification metrics such as Accuracy and F1-Score.

---

## Dataset

**Dataset:** Breast Cancer Wisconsin Dataset

**Source:** Scikit-learn Built-in Dataset

**Problem Type:** Binary Classification

The dataset contains 569 samples with 30 numerical features used to classify tumors as malignant or benign.

---

## Project Structure

```
README.md
requirements.txt

notebooks/
└── ensemble_exploration.ipynb

reports/
└── performance_comparison.md

data/
└── raw_dataset_info.txt
```

---

## Requirements

Install the required libraries:

```bash
pip install -r requirements.txt
```

---

## How to Run

1. Clone or download this repository.
2. Install the required dependencies using:

```bash
pip install -r requirements.txt
```

3. Open the notebook:

```
notebooks/ensemble_exploration.ipynb
```

4. Run all cells sequentially to preprocess the dataset, train the models, and compare their performance.

---

## Models Used

- Decision Tree Classifier
- Random Forest Classifier
- Gradient Boosting Classifier

---

## Evaluation Metrics

The following metrics were used to evaluate model performance:

- Accuracy
- F1-Score
- Classification Report

---

## Summary

The Decision Tree model was used as the baseline classifier.

Random Forest and Gradient Boosting, as ensemble learning techniques, achieved better overall performance and demonstrated improved robustness and generalization compared to the single Decision Tree model.

---

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Google Colab

---

## Learning Outcomes

- Understanding ensemble learning techniques.
- Comparing Decision Tree with Random Forest and Gradient Boosting.
- Evaluating models using Accuracy and F1-Score.
- Observing how ensemble methods improve predictive performance.
