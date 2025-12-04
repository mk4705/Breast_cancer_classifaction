Overview:
This project demonstrates how to use Support Vector Machines (SVM), a powerful supervised learning method, to classify breast cancer tumors using the widely-used Breast Cancer Wisconsin (Diagnostic) dataset. The notebook follows a complete machine learning workflow: data loading, exploratory analysis, preprocessing, model training, and evaluation, all within Python.

Dataset:
The dataset contains 569 samples with 30 numerical features describing tumor characteristics extracted from digitized images of a fine needle aspirate (FNA) of a breast mass. Each sample is labeled as malignant (M) or benign (B).

Key features include:
Mean, standard error, and worst (largest) value for each of ten characteristics (e.g., radius, texture, perimeter, area, smoothness).

Diagnosis label (M for malignant, B for benign).

Data Loading & Inspection :
Imports the dataset 
Explores columns, checks for missing values, and examines basic statistics.

Exploratory Data Analysis
Visualizes the distribution of different features.
Examines class balance between benign and malignant tumors.

Data Preprocessing
Converts diagnosis labels from strings (M, B) to binary values (1, 0).
Scales features using StandardScaler to ensure equal contribution for SVM.

Model Building

Splits data into training and test sets (80/20 split)
Initializes and trains an SVM classifier.

Model Evaluation
Predicts using the test set.
Calculates model accuracy, and displays a classification report (precision, recall, F1-score).
Plots the confusion matrix for easy interpretation.

Key Findings

SVM models—especially with RBF or linear kernels—often achieve high accuracy (around 97–99%) on this dataset.
Certain features (like mean radius, texture, perimeter) have strong impact on classification.
Visualization of results highlights model strength in distinguishing between benign and malignant cases.
