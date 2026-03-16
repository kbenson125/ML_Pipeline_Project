Bone Marrow Transplant Survival Prediction
This project predicts survival status for pediatric bone marrow transplant patients using a machine learning pipeline. The pipeline includes data preprocessing, PCA for feature selection, and logistic regression with hyperparameter tuning.

Dataset

Source: UCI Machine Learning Repository
Features: Patient and donor characteristics, transplant details
Target: Survival status (alive or dead)
Workflow

Load and clean the dataset
Split features into numerical and categorical
Preprocess data (imputation, scaling, encoding)
Apply PCA for dimensionality reduction
Train and tune a logistic regression classifier
Evaluate model accuracy
Requirements

Python 3
pandas
scikit-learn
numpy
scipy
Usage

Clone the repository
Place bone-marrow.arff in the project directory
Run script.py to train and evaluate the model
Results

Initial pipeline accuracy: ~79%
Tuned model accuracy: ~82%
License

For educational use only. Dataset © UCI Machine Learning Repository.
