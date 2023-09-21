# Medical research data analysis - ECG data classification prediction

Project Overview

This project focuses on the analysis and classification of electrocardiogram (ECG) data using machine learning techniques. The goal is to classify different types of heart diseases based on ECG data, which includes multi-class classification with 5 categories (4 classifications for heart diseases and 1 for healthy cases). Various machine learning algorithms were employed and optimized for accurate classification.

Dataset Information

The ECG dataset used for this project is sourced from the MIT-BIH dataset, which is available on Kaggle. The dataset consists of two subsets: "mitbih_train.csv" for analysis, training, and validation, and "mitbih_test.csv" for testing. A statistical comparison of these two subsets is conducted.

Project Workflow

The project followed these key steps:

Data Exploration and Visualization: The raw ECG data was explored and visualized to understand the characteristics of different heartbeat types. Variations in length, timing, and amplitude of waves were identified for different heartbeat types.

Data Imbalance Handling: Recognizing the imbalance in the provided training dataset, steps were taken to balance it, as classifiers built on imbalanced data may exhibit bias.

Classification and Prediction: Three machine learning algorithms - K-Nearest Neighbors (KNN), Decision Tree, and Support Vector Machine (SVM) - were applied to the balanced data for classification and prediction.

Model Evaluation and Selection: An extensive performance evaluation scheme was employed to assess the classification models' performance. The optimal machine learning algorithm was selected based on classification prediction accuracy on testing data. The KNN classifier achieved the highest accuracy, reaching 78%.

Resources

Dataset Source: MIT-BIH ECG Dataset on Kaggle

Dataset Files: "mitbih_train.csv" for training and validation, "mitbih_test.csv" for testing.
Deliverables

The project includes a technical report with the following sections:

Introduction: An overview of the project objectives and scope.

Methods: Detailed explanations of data preprocessing, feature selection, and model building.

Experiment Results: Presentation of classification results and model performance metrics.

Discussion & Conclusion: Interpretation of findings, implications, and conclusion.

References: Citations to relevant sources and materials.
