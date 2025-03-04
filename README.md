## What is ROC?
The ROC curve is a graphical representation of a classifier's ability to distinguish between classes. It plots the True Positive Rate (TPR) against the False Positive Rate (FPR) at various threshold settings. A model with a perfect classification would have an AUC (Area Under the Curve) score of 1.0, whereas a completely random classifier would have an AUC of 0.5.

### Components of the ROC Curve:
- **True Positive Rate (TPR)**: Also known as sensitivity or recall, it measures the proportion of actual positives correctly identified.
- **False Positive Rate (FPR)**: Measures the proportion of actual negatives incorrectly classified as positives.
- **AUC (Area Under the Curve)**: A single scalar value that quantifies the overall performance of the classifier.

## Features
- Computes the ROC curve based on model predictions and true labels.
- Calculates the Area Under the Curve (AUC) score to assess classification performance.
- Visualizes the ROC curve using Matplotlib.

## Purpose
This notebook is designed to help users understand and utilize the ROC curve for evaluating classification models. It demonstrates how to generate the ROC curve, compute key metrics, and interpret the results effectively.

## Requirements
To run this notebook, ensure you have the following Python libraries installed:

```bash
pip install numpy pandas matplotlib scikit-learn
```
