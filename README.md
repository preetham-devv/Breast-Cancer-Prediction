# Breast-Cancer-Prediction
Breast Cancer Prediction

This repository contains the project for IT7103 – Assignment 4, focusing on the application of data analytics in healthcare informatics to predict breast cancer cases. The project utilizes Linear and Kernel (both RBF and Linear) Support Vector Machine (SVM) models to classify breast cancer cases as benign or malignant.

Project Overview
Breast cancer is a significant health concern, and early detection is crucial for effective treatment. This project aims to predict whether a breast cancer case is benign or malignant using machine learning techniques, specifically SVM models. The data consists of 699 recorded cases with 11 features, where the target variable indicates the class (0 for benign, 1 for malignant).

Data Description
The dataset contains the following columns:

#1.Case number: Identifier for each case./n
#2.Clump Thickness: Measurement of the thickness of cell clumps.
#3.Uniformity of Cell Size: Consistency in cell size.
Uniformity of Cell Shape: Consistency in cell shape.
Marginal Adhesion: Degree of adhesion between cells.
Single Epithelial Cell Size: Size of single epithelial cells.
Bare Nuclei: Count of bare nuclei.
Bland Chromatin: Texture of the cell's chromatin.
Normal Nucleoli: Count of normal nucleoli.
Mitoses: Count of mitotic cells.
Class: Target variable (0 for benign, 1 for malignant).


Project Details
Data Splitting: The dataset is split into training and testing sets.
Model Training: Linear SVM and Kernel SVM (with RBF and Linear kernels) models are trained on the data.
Hyperparameter Tuning: Hyperparameters for both models are finetuned to optimize performance.
Evaluation Metrics: Cross-validation training accuracy and testing accuracy are reported.
