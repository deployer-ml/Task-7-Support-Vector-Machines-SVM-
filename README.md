# Binary Classification with SVM

This project demonstrates binary classification using Support Vector Machines (SVM) with both **linear** and **RBF** kernels on a 2D dataset.

## Key Steps

* **Data Preparation**: Load and normalize binary classification data.
* **Model Training**: Train SVM with linear and RBF kernels using `scikit-learn`.
* **Visualization**: Plot decision boundaries for both kernels.
* **Hyperparameter Tuning**: Use GridSearchCV to optimize `C` and `gamma`.
* **Evaluation**: Apply k-fold cross-validation for model assessment.

## Requirements

```bash
pip install scikit-learn numpy matplotlib
```

## Output

* Accuracy scores with cross-validation
* Decision boundary plots
* Optimal hyperparameters
