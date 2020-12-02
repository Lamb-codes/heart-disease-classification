# Heart disease classification project

![alt text](https://img.webmd.com/dtmcms/live/webmd/consumer_assets/site_images/article_thumbnails/slideshows/did_you_know_this_could_lead_to_heart_disease_slideshow/650x350_did_you_know_this_could_lead_to_heart_disease_slideshow.jpg)

## Problem statement
Heart disease describes a range of conditions that affect your heart. Diseases under the heart disease umbrella include blood vessel diseases, such as coronary artery disease; heart rhythm problems (arrhythmias); and heart defects you're born with (congenital heart defects), among others.

**Aim of the project**

Given medical patient's attributes, is it possible for a Machine Learning model to predict wether or not the patient has a heart disease?

## Results and considerations

Best model: LogisticRegression (hyperparameters tuned using GridSearchCV)

Classification report:

![alt text](https://github.com/Lamb-codes/heart-disease-classification/blob/main/class_report.png)

It's probably possible to improve it even more by trying to tune the model with more hyperparameters or by collecting more data.

## About the data
The original set comes from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/heart+Disease)

## EDA - Exploratory Data Analysis
After defyining and understanding data's features I performed some basic comparisons between the most interesting ones.

**Heart disease frequency per maximum heart rate achieved and cholestorol levels**

![alt text](https://github.com/Lamb-codes/heart-disease-classification/blob/main/graph.png)

And more

