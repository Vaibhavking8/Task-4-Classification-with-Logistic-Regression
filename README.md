# Task-4-Classification-with-Logistic-Regression

This project performs binary classification using **Logistic Regression** on the Breast Cancer Wisconsin dataset to predict whether a tumor is malignant or benign.

## Steps Performed

1. **Dataset**: Breast Cancer Wisconsin Diagnostic Data (`data.csv`)
2. **Preprocessing**:
   - Encoded target: `M` → 1 (malignant), `B` → 0 (benign)
   - Standardized features
3. **Model**: Logistic Regression
4. **Evaluation Metrics**:
   - Confusion Matrix
   - Precision
   - Recall
   - ROC-AUC Score
   - ROC Curve and Threshold Tuning

## Threshold Tuning

The default threshold (0.5) was analyzed using ROC and precision-recall curves to understand trade-offs:
- Lower thresholds increase recall.
- Higher thresholds increase precision.
