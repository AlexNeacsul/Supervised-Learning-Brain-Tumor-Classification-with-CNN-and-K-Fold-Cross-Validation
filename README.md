# Supervised-Learning-Brain-Tumor-Classification-with-CNN-and-K-Fold-Cross-Validation
The project implements **$k$-Fold Cross-Validation** (with $k=5$ folds) and explores various **data balancing** methods, including:
* **Weighted Loss function**.
* **Oversampling**.
* **Augmented Oversampling**.

It was observed that balancing techniques led to an **approximate 3% performance increase** for every metric, and the weighted loss function seems to be the most balanced solution, as it improves performance without requiring modifications to the dataset.

### Key Results

* **Average Validation Accuracy (No Balancing)**: $0.8448$
* **Maximum Accuracy (With Balancing)**: $0.8693$ (Oversampling).
* The **Confusion Matrix** and detailed per-class metrics (Precision, Recall, F1 Score) are included.

---
