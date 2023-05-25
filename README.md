# CDSS_Tasks

This is a repository for tasks regarding  different machine learning models such as Linear & Logistic Regression using several tools for implementation such as python and weka tools.

## [Task 1](https://github.com/mahmoud1yaser/CDSS_Tasks/tree/main/Task1)
#### Creating a multinomial regression model for hypothyroid disease using Weka tool.


* The chosen dataset is one of weka's examples "Hypothyroid", consisting of 30 attributes, 29 independent and one dependent.

* Accuracy of the model
1. 96.85% correctly classified.
2. MCC (Matthew’s Correlation coefficient) with average of 0.8.

![Results](https://user-images.githubusercontent.com/81927516/226500141-adde2bbb-1f19-4706-9d58-2b5cc8821ac3.png)


## [Task 2](https://github.com/mahmoud1yaser/CDSS_Tasks/tree/main/Task2)
### Creating a logistic regression model for hypothyroid disease using python.

* The chosen dataset is for diagnosing a patient with 3 levels of hypothyroid, or determining if they are not sick.
The dataset includes 29 features to help predict 4 output classes: negative (not sick), primary, secondary or tertiary hypothyroidism.

* Data cleaning and visualization were applied using multiple techniques

Histogram visualization

![Histogram-visualization](https://user-images.githubusercontent.com/81927516/226503258-2e194e04-0765-4a5a-9da5-c10043a101a5.png)

* For modelling the data, many approaches where carried out to reach best results and accuracy, that approach was Logistic Regression Model using all the features in case of combination of the four output classes into two main classes.

* Final Results

![Results](https://user-images.githubusercontent.com/81927516/226503788-75841cae-587c-47b8-b7ed-0dff772f0e3d.png)

## [Task 2](https://github.com/mahmoud1yaser/Clinical-Decesion-Support-System-Course/tree/main/Diabetes%20Problem)
#### Using various classification algorithms to improve diabetes diagnosis in Indian women

* The dataset is concerned with diagnosing diabetes in Indian women based on basic EHR records and some insulin readings.
* Data cleaning and pre-processing included engineering new features based on the original ones (for example: Medical risk is an engineered feature derived from Age, BMI, and blood pressure).

* Main Results

We surpassed the maximum acheived accuracy in the aforementioned paper, both by using simple feature engineering as well as hyperparameter tuning.

Paper's results:

| Classifier | Accuracy | F1 Score | Cross Validation |
|------------|----------|----------|------------------|
| GNB        | 0.79     | 0.78     | 0.74             |
| DT         | 0.76     | 0.80     | 0.74             |

Accuracies After Preprocessing and Hyperparameter Tuning

| Classifier | Accuracy | F1 Score | Cross Validation |
|------------|----------|----------|------------------|
| SVM **     | 0.83     | 0.83     | 0.77             |
| GNB        | 0.78     | 0.78     | 0.75             |
| DT         | 0.75     | 0.80     | 0.74             |
| RF         | 0.79     | 0.79     | 0.74             |
| LR         | 0.81     | 0.82     | 0.76             |
| KNN        | 0.78     | 0.79     | 0.73             |



## About Us

 The projects are made for clinical Decision Support Systems course of SBME 2024 under supervision of Dr/ Ahmed Morsy, Instructor/Eng. Eman Ayman, and TA/ Eng. Abdelrahman Hisham Mostafa.

### Team Members

Name| Section | Bench Number |
--- | --- | --- |
[Ahmed El-Sarta](https://github.com/ahmed-elsarta "Ahmed El-Sarta")| 1 | 8
[Abdelrahman Yasser](https://github.com/Abdelrhman012 "Abdelrahman Yasser") | 1 | 52
[Nourhan Sayed](https://github.com/nourhansayed102 "Nourhan Sayed") | 2 | 47
[Mahmoud Yasser](https://github.com/mahmoud1yaser "Mahmoud Yasser") | 2 | 29
[Sohaila Mahmoud](https://github.com/sohailamahmoud "Sohaila Mahmoud") | 1 | 45
