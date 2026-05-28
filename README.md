# ML Portfolio

This portfolio includes projects in machine learning and computer vision. The tabular ML part covers data preprocessing, feature engineering, model training, and comparison for customer churn prediction and Game of Thrones character survival classification. The CV part includes medical image segmentation in `PyTorch` and object detection with `YOLO` for parking space analysis. The main focus across all projects is the full pipeline: data preparation, experimentation, model evaluation, and result analysis.

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

### 4. PKLot Parking Space Detection
- Computer vision project for parking space detection and occupancy recognition based on the PKLot dataset.
- Includes conversion from COCO annotations to YOLO format, model training with Ultralytics YOLO, and evaluation with confusion matrices and validation metrics.
- Main metrics: `Precision`, `Recall`, `mAP@50`, `mAP@50-95`.

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
  pklot_detection/
    parking_space_detection_yolo.ipynb
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
- Ultralytics YOLO

## Notes

- The projects are stored in notebook format.
- Some datasets are not included in the repository and should be downloaded separately if needed.
