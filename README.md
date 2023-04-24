# Mobile Price Classification-Project Overview
The goal of this project is to develop classification model for dataset that hold several specifications of 2000 mobile phones attempt to predict best price ranges by applying either Artificial Neural Network or by using various machine learning algorithm.
# Notebooks:
Included in this github is a jupyter notebook containing:

EDA_DataPreprocessing_Mobile_Price_Classification.ipynb :A notebook where significant EDA to explore the variables as well as data preprocessing steps are performed.

Project1_Mobile_Price_Classification.ipynb: A notebook where apart from EDA, models implementation which includes training, testing as well the performance of the models are evualuated using the metrics like accuracy,precision ,recall and F1-score are performed
Also note, models are tested on different kind of input scenarios as well which includes- feature selection, PCA input, hyperparamter tuning

# Main steps performed for EDA and data-preprocessing

1.	Check the null values in dataset
2. Checking number of categorical attributes
3. Finding Duplicates in the data
4. Visualising the data distribution of the target variable
5. Analysing the relationship between variables
6. Analysing the relationship between target variable and other features in dataset
7. Visualising all the input features
8. Detecting Outliers
9. Visualising outliers using box plots

# Data-preprocessing

1. Visualise data in 2-D using LDA
2. Finding the number of outliers and eliminating them
3. Splitting the train and test dataset
4. Standardizing the dataset

# Models Implementation. training and analysis of results
To predict the mobile phone price, we have applied different techniques on the input data like dimensionality reduction (PCA), feature selection and then used mentioned below machine learning algorithms and deep learning techniques on the training and test dataset. After that, we choose the best model for our data set based on the comparative results on the selected evaluation metrics like -accuracy,precision, Recall,F1-score.
Implementation of Machine Learning Algorithms:
1.	Logistic regression
2.	Random forest
3.	KNN
4.	SVM

Implementation of Deep Learning Technique: Artificial Neural Network


