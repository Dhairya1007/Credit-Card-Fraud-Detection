# Credit-Card-Fraud-Detection

This is a machine learning project for detection of a fraud credit card payment. 
In this project, I have used 2 models for training and testing:

1. Local Outlier Factor
2. Isolation Forest

Note that it is an unsupervised learning example, so we won't be providing any reference outputs for training. We will be using this models from the sklearn package. 

Libraries required:

1. Matplotlib
2. Seaborn
3. sklearn
4. pandas
5. numpy
6. scipy

Note that the accuracy we have with this models in very less because of the form, that is unsupervised. Then also, we will use a fraction of the large credit card transactions database from kaggle containing a large amout of data. 

Isolation forest is basically a number of random forest cases in a tree format. 

Acurracies obtained :

1. Outlier Model - 21% 
2. Isolation Forest - 33%

Hope the project helps you learn the basics of the following models as there is a step be step data preprocessing and the model training with both methods in the Jupyter notebook attached.

Link for the dataset - https://www.kaggle.com/mlg-ulb/creditcardfraud
(it is approx 100mb so couldnt upload it directly to the repo.)
