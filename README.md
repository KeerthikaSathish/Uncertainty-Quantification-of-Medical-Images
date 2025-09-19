# Project: Uncertainty Quantification of Medical Images
## Objective
The goal of this project was to develop a deep learning framework that not only classifies brain MRI scans into tumor and no tumor categories, but also quantifies the uncertainty in its predictions. This is essential in medical AI, where wrong predictions can have critical consequences. By incorporating uncertainty estimation, the model provides both a decision and a confidence score, enabling clinicians to flag and review ambiguous cases.

## Dataset
Used the Brain Tumor Detection MRI dataset (Kaggle).
Dataset contained two classes:
    Yes (tumor present)
    No (no tumor)
Total images: ~2916, split into training (80%) and validation (20%)

## Key features:
Brain tumor classification from MRI images (tumor vs. no tumor)
Uncertainty quantification using Monte Carlo Dropout for confidence-aware predictions
CNN-based deep learning model trained with balanced sampling
Evaluation with clinical metrics 
