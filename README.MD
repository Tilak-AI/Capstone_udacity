# Sparkify - Udacity data scientist nanodegree capstone project

### Table of Contents

1. [ Installation ](#installation)
2. [ Project Motivation ](#motivation)
3. [ File Descriptions ](#filedesc)
4. [ Results ](#results)
5. [ Licensing ](#licensing)

## 1. Installation <a name="installation"></a>
Jupyter Notebook for this article was developed using Python v3.4 using below libraries

1.) PySpark,
2.) Pandas,
3.) Matplotlotlib,
4.) NumPy,
5.) MLlib

Models:
1.) Logistic Regression,
2.) Gradient Boosted Trees
3.) Random Forest



## 2. Project Motivation <a name="motivation"></a>
Purpose of this notebook/article is, using Spark framework, to predict whether users of a music audio streaming platform, Sparkify, are likely to churn or not. This is a capstone project for the Udacity data scientist nanodegree program.

## 3. File Descriptions <a name="filedesc"></a>
* _Sparkify.ipynb_ contains all the code allowing data load, manipulation, and graph generation.
* _Sparkify.html_ is the same, in HTML format.
* _mini_sparkify_event_data.json_ is a copy of the dataset (JSON format).

Article is available on [Medium](https://medium.com/@tgpath18/sparkify-predicting-the-customer-churn-43e228ddb71e).

## 4. Results <a name="results"></a>

It turns out that we only needed 10 features to acquire a decent model that will predict good churn rates than guessing randomly; the logistic regression model was 81% accurate with an F1-Score of 0.78 and the random forest model well of course scored similar fashion compared to logistic regression on base parameter.


The "lifetime" is the greatest important feature along with "thumbs down" and "friends added by the churners". This makes top 3 important features to predict the churns

## 5. Licensing <a name="licensing"></a>

Dataset and image used for this notebook/article are courtesy of [Udacity](https://www.udacity.com).