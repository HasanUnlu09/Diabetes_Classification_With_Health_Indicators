# Diabetes Classification With Health Indicators

## Project Description
In this project, it is aimed that find an answer to a question: **Can the diabetic tendency of a person be determined with the given health indicator?** In order to obtain data, **Kaggle Dataset** is used. If you would like to see content of the dataset, you can check out the dataset in the **diabetes_binary_health_indicators_BRFSS2015.csv** file or you can visit the [Kaggle - Diabetes Health Indicators Dataset](https://www.kaggle.com/datasets/alexteboul/diabetes-health-indicators-dataset). In order to accomplish classification operation, following Classification ML Algorithms are used, **Logistic Regression**, **Decision Tree Classifier**, **Naive Bayes Classifier**, **K-Nearest Neighbors(KNN) Classifier**, **Random Forest Classifier**, **AdaBoost**, **GradientBoosting** and **eXtremeGradientBoosting**. These ML Algorithms are evaluated by using **F1-Score**, **ROC Curve** and **AUC-Score** metrics. F1-Score is used and using **Accuracy** metric is avoided because of **imbalance dataset**. As a result of these algorithms, best performed model is the **Naive Bayes** algorithm with **0.411223 F1 score**. Also, it has the widest AUC among all applied models with 0.679697 value. It should be mentioned that, Data Science Project LifeCycle is followed on this project to effectively simulate business level project handling as it can be seen from the following image. Therefore, project is formed in to 7 steps with the proceduralized contents and the step/file names are as follow; **1. Business_Understanding, 2. Data_Mining, 3. Data_Cleaning, 4. Data_Exploration_(EDA), 5. Feature_Engineering, 6. Predictive_Modelling_&_Evaluation** and **7. Data_Visualization.**

![Data_Science_LifeCycle](https://github.com/HasanUnlu09/Diabetes_Classification_With_Health_Indicators/assets/133260754/247e9dbe-40e4-4ab9-9253-ed30d4b4b918)


## Project Difficulties
In this project, each ML Algorithm has unacceptably low values. This is a challange to overcome. As a result, if the EDA step of this procet is examined, then it can be said that there is no even one moderately correlated predictor with the target. Thus, I concluded that failure of the ML Algorithms should be caused from the no/low-correlation relationship. If there is any suggestions, please let me know via e-mail shared in the bottom of this README.md file.

## Install/Run
Each Data Science LifeCycle steps in Jupyter Notebook files can be runned one by one on your computer to see the results.

## Project Outcomes

All of the confusion matrix result for each model can be seen from the below image;
![1  Confusion_Matrices](https://github.com/HasanUnlu09/Diabetes_Classification_With_Health_Indicators/assets/133260754/ecb3e44e-72d4-4aab-8e90-13b089a4d0e2)

In the below image it can be seen that how well the model performed by considering F1-Score;
![2  F1-Scores](https://github.com/HasanUnlu09/Diabetes_Classification_With_Health_Indicators/assets/133260754/1c3a8e2a-2f1e-49a1-bde3-5a7c17613b1a),


ROC(Receiver Operator Characteristic) Curves for all models are shown in the below image;
![3  ROC-Curves](https://github.com/HasanUnlu09/Diabetes_Classification_With_Health_Indicators/assets/133260754/1f32782f-c92d-4138-9f41-27c8a1bb8d91)

AUC(Area Under Curve) Scores is represented in the below bar plot to compare models with each others;
![4  AUC-Scores](https://github.com/HasanUnlu09/Diabetes_Classification_With_Health_Indicators/assets/133260754/3ece1022-20dc-4f09-a6a9-93186240b5e5)

**!!!** If you would like to reach me out about this project you can yuse following e-mail address; **hasan.09.unlu@gmail.com**
