# Human-Activity-Recognition-using-Deep-Neural-Networks

## Contents
  * [Introduction](#introduction)
  * [Dataset Installation](#dataset)
  * [Summary](#summary)
  * [Resources](#resources)

## Introduction: <a name="introduction"></a>
The dataset is collected from the 30 participants with the help of a smartphone mounted on the waist area of a person. The dataset is collected and labelled while the person were performing six different activities such as "walking", "standing", "sitting", "laying down", "walking upstairs" and "walking downstairs". The embedded accelorometer and gyroscope sensors used to track the 3 axis acceleration and 3 axis angular velocity. Some preprocessing techniques were used to collect important features in the time and frequency domains. These features are the feature columns of the dataset.

## Dataset Installation <a name="dataset"></a>
The dataset is downloaded from the official [Kaggle Website](https://www.kaggle.com/uciml/human-activity-recognition-with-smartphones) and then it is imported in the workspace directory. Steps are described in the coding part. 

## Summary <a name="summary"></a>
Firstly the dataset is imported and then exploratory data analysis(EDA) is performed. With the help of EDA, we can get some useful information from the data including descriptive statistics such as maximum or minimum value in each feature column. Alongwith this, EDA helps us in visually interpreting the distribution of different activities. One such plot is shown below indicating distribution of stationary and dynamic activities.

A sequential model has been trained on the training examples, "Adam" optimizer is used as an optimization technique with a learning rate of 0.001. The model training requires 22 epochs, and the training accuracy came out was around 93%. The testing accuracy is 91%. This could be further improved with proper selection of hyperparameteres or using hyperparameter tunning.

## Resources <a name="resources"></a>


