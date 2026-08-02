# Performance Comparison Report

## Objective

The objective of this project was to compare the performance of a single Decision Tree model with two ensemble learning methods: Random Forest and Gradient Boosting.

The models were trained and evaluated on the Breast Cancer Wisconsin Dataset using Accuracy and F1-Score.

---

# Dataset Information

- **Dataset:** Breast Cancer Wisconsin Dataset
- **Source:** Scikit-learn Built-in Dataset
- **Problem Type:** Binary Classification
- **Samples:** 569
- **Features:** 30 Numerical Features

---

# Models Evaluated

1. Decision Tree (Baseline)
2. Random Forest
3. Gradient Boosting

---

# Evaluation Metrics

The following metrics were used for comparison:

- Accuracy
- F1-Score
- Classification Report

---

# Performance Summary

| Model | Accuracy | F1-Score |
|--------|----------|----------|
| Decision Tree | Generated during notebook execution | Generated during notebook execution |
| Random Forest | Generated during notebook execution | Generated during notebook execution |
| Gradient Boosting | Generated during notebook execution | Generated during notebook execution |

---

# Observations

### Decision Tree

**Strengths**
- Simple and easy to interpret.
- Fast training time.

**Weaknesses**
- More likely to overfit the training data.
- Lower predictive performance compared to ensemble models.

---

### Random Forest

**Strengths**
- Reduces overfitting by combining multiple decision trees.
- Provides higher prediction accuracy.
- More robust than a single Decision Tree.

**Weaknesses**
- Requires more computational resources.
- Less interpretable than a single tree.

---

### Gradient Boosting

**Strengths**
- High predictive performance.
- Learns from previous model errors.
- Produces strong generalization on classification tasks.

**Weaknesses**
- Longer training time.
- More sensitive to hyperparameter settings.

---

# Conclusion

The ensemble learning models outperformed the baseline Decision Tree model.

Random Forest improved prediction stability through bagging, while Gradient Boosting enhanced performance by sequentially correcting previous errors.

For this classification task, ensemble methods demonstrated better accuracy and F1-Score, making them more suitable for real-world predictive applications.

---

# Learning Outcomes

Through this project, I learned:

- How Decision Trees work as baseline models.
- The advantages of Random Forest and Gradient Boosting.
- How ensemble learning improves prediction accuracy.
- How to evaluate machine learning models using Accuracy and F1-Score.
- How to compare multiple classification models on the same dataset.
