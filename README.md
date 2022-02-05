# BREST_CANCER_DETECTTION
# DATASET:
Samples arrive periodically as Dr. Wolberg reports his clinical cases. The database therefore reflects this chronological grouping of the data. 

Attribute Information:

1. Sample code number: id number
2. Clump Thickness: 1 - 10
3. Uniformity of Cell Size: 1 - 10
4. Uniformity of Cell Shape: 1 - 10
5. Marginal Adhesion: 1 - 10
6. Single Epithelial Cell Size: 1 - 10
7. Bare Nuclei: 1 - 10
8. Bland Chromatin: 1 - 10
9. Normal Nucleoli: 1 - 10
10. Mitoses: 1 - 10
11. Class: (2 for benign, 4 for malignant)

# Test-Train split:
It is important to split your data set to training set and test set, so that you can evaluate the performance of your model using the test set before deploying it in a production environment. One important thing to note when doing the train test split is to make sure the distribution of the data between the training set and testing set are similar. What it means in this context is that the percentage of malignent in the training set and test set should be similar.

# Data preprocessing:
1.there were no missing values in the dataset considered

2.Feature Scaling was performed on the dataset
    the independent variables were scaled using the StandardScalar class provided by the scikit-learn library
    since there are only two classes label encoding was used
# Logistic Regression
Logistic regression is a process of modeling the probability of a discrete outcome given an input variable. The most common logistic regression models a binary outcome; something that can take two values such as true/false, yes/no, and so on. 
# Confion Matrix
![]confusion_matrix.png
  
