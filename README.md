# ML Portfolio

This repository contains three machine learning projects built as standalone notebook-based case studies.

## Projects

### 1. Customer Churn Prediction
- Binary classification project for telecom customer churn prediction.
- Includes exploratory data analysis, feature preprocessing, logistic regression, and CatBoost.
- Main metric: `ROC-AUC`.

### 2. Game of Thrones Survival Prediction
- Classification project for predicting whether a character survives.
- Includes data cleaning, feature engineering, and comparison of several `scikit-learn` models.
- Main metric: `Accuracy`.

### 3. Skin Lesion Segmentation
- Computer vision project for medical image segmentation on the PH2 dataset.
- Includes `SegNet`, `UNet`, and experiments with `BCE`, `Dice`, and `Focal Loss`.
- Main metric: `IoU`.

## Repository Structure

```text
ml-portfolio/
  churn-prediction/
    customer_churn_prediction.ipynb
    README.md
  got-survival-prediction/
    got_survival_prediction.ipynb
    README.md
  skin-lesion-segmentation/
    skin_lesion_segmentation.ipynb
    README.md
```

## Tech Stack

- Python
- Jupyter Notebook
- pandas
- NumPy
- scikit-learn
- CatBoost
- PyTorch

## Notes

- The projects are stored in notebook format.
- Some datasets are not included in the repository and should be downloaded separately if needed.
