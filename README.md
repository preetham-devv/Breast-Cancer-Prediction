# Breast-Cancer-Prediction
Breast Cancer Prediction

This repository contains the project, focusing on the application of data analytics in healthcare informatics to predict breast cancer cases. The project utilizes Linear and Kernel (both RBF and Linear) Support Vector Machine (SVM) models to classify breast cancer cases as benign or malignant.

Project Overview<br />
Breast cancer is a significant health concern, and early detection is crucial for effective treatment. This project aims to predict whether a breast cancer case is benign or malignant using machine learning techniques, specifically SVM models. The data consists of 699 recorded cases with 11 features, where the target variable indicates the class (0 for benign, 1 for malignant).

Data Description
The dataset contains the following columns:<br />

1.Case number: Identifier for each case.<br />
2.Clump Thickness: Measurement of the thickness of cell clumps.<br />
3.Uniformity of Cell Size: Consistency in cell size.<br />
4.Uniformity of Cell Shape: Consistency in cell shape.<br />
5.Marginal Adhesion: Degree of adhesion between cells.<br />
6.Single Epithelial Cell Size: Size of single epithelial cells.<br />
7.Bare Nuclei: Count of bare nuclei.<br />
8.Bland Chromatin: Texture of the cell's chromatin.<br />
9.Normal Nucleoli: Count of normal nucleoli.<br />
10.Mitoses: Count of mitotic cells.<br />
11.Class: Target variable (0 for benign, 1 for malignant).<br />


Project Details<br />
Data Splitting: The dataset is split into training and testing sets.<br />
Model Training: Linear SVM and Kernel SVM (with RBF and Linear kernels) models are trained on the data.<br />
Hyperparameter Tuning: Hyperparameters for both models are finetuned to optimize performance.<br />
Evaluation Metrics: Cross-validation training accuracy and testing accuracy are reported.<br />
