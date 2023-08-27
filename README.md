# Medical-research-02--ECG-data-classification

This project is to use a large but imbalanced ECG dataset for a case study and implement, validate, and optimize some machine learning solutions for the analysis and classification of heartbeat data.

The goal of the ECG data analysis was to do multi-classification of what kind of heart disease a person has based on their ECG data, There were 5 classifications (4 classifications had heart disease, 1 classification was healthy). During the experiment, different machine learning algorithms were used, and an optimal algorithm was selected for future classification prediction. 

The experimental steps were as follows：

1. The raw data was the ECG data of different people. Data exploratory analysis and visualization were carried out by comparing a sample of each heartbeat type, finding that for different heartbeat types, the length, the timing, and the amplitude of different waves were different. 
2. Notice the provided training dataset was imbalanced based on the classification, so I need to balance the training dataset because a classifier built based on an imbalanced training dataset may just classify any dataset to the majority votes in the training dataset. 
3. Balanced data were classified and predicted using three different machine learning algorithms, including KNN, Decision tree, and SVM. 
4. Finally, found the optimal machine learning algorithm based on the classification prediction accuracy rate on the testing data. The best classifier I have got for this project is KNN by using all the features, the accuracy rate was 78% for this classifier.


Resources 

Download the MIT-BIH dataset from this Kaggle website:

https://www.kaggle.com/datasets/shayanfazeli/heartbeat

It contains two subsets as CSV files. Use the file “mitbih_train.csv” for analysis, training, and validation, and “mitbih_test.csv” for testing. Carry out a statistical comparison of the two subsets.

Explore the possible use of various unsupervised and supervised learning algorithms.

This project contains: 

1. Visual, exploratory data analysis. 
2. Classification of heartbeat types. Use three classification algorithms to tackle the problem; employ a comprehensive performance evaluation scheme. Performance tuning and model interpretation.

Deliverable

The attached technical report contains four sections: Introduction, Methods, Experiment Results, and Discussion & Conclusion, plus References.

