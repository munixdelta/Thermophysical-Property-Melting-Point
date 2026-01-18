# Thermophysical-Property-Melting-Point

This project is based on a Kaggle competition where the objective is to predict the melting point (Tm) of organic compounds using molecular descriptors.

The problem is treated as a regression task. Machine learning models are trained on the provided dataset to learn the relationship between molecular features and melting point values.

Dataset:
- train.csv : Contains features along with target column (Tm)
- test.csv : Contains only features (no target)
- sample_submission.csv : Submission format for Kaggle

Workflow:
- Data loading and preprocessing
- Handling missing values
- Feature scaling
- Training regression models
- Model evaluation
- Generating predictions for test data

Technologies Used:
- Python
- Pandas
- NumPy
- Scikit-learn
- Jupyter Notebook

Evaluation Metrics:
- RMSE
- MAE
- R2 Score

This project is created for learning and practicing machine learning regression techniques on real-world chemical data.
