Emotion Recognition using Machine Learning

Overview
This project focuses on multi-class emotion recognition using feature-based machine learning. The goal is to classify emotional states into four classes derived from the valence–arousal representation.

Methods

Data preprocessing on high-dimensional feature vectors (1793 features)

Machine learning classification pipeline

5-fold Cross-Validation

Group K-Fold Cross-Validation to ensure subject-independent generalization

Performance evaluated using macro F1-score

Dataset
Feature-extracted dataset provided for emotion recognition tasks, where each sample belongs to one of four emotion classes.

Results
The final model was selected based on cross-validation performance and generalization to unseen subjects, achieving strong macro F1-scores in a Kaggle-style evaluation setting.

Technologies Used

Python

NumPy

Pandas

scikit-learn

How to Run
Open the Jupyter notebook and run all cells to reproduce preprocessing, training, validation, and prediction steps.
