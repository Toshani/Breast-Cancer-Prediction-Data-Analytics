# Breast Cancer Prediction - 5th Semester Data Analytics Project
Team name: Patterns n Parameters

This is the final Data Analytics course project repository where we have implemented Breast Cancer tumor classification into malignant and benign thereby predicting the chance of breast cancer.
We have used the kaggle data set and implemented Logistic Regression, Naive Bayes Algorithm, KNeighbors Classifier, Decision Tree Classifier, Random Forest Classifier and AdaBoost Classiifier.

# Dataset Description:
The dataset given to us was aready cleaned and ready for pre-processing, having the following features: 
1. Each record consists of 32 features including the tumor details such as radius, perimeter, texture, density, symmetry, diagnosis etc. 
2. Each tumor is one of 2 classes, benign or malignant
3. 400+ examples in train and 100+ in test

Link to the original dataset: https://www.kaggle.com/uciml/breast-cancer-wisconsin-data/tasks (Breast Cancer Wisconsin (Diagnostic) Data Set)

# Libraries Used: 
Pandas, Numpy, Matplotlib, Seaborn, Scipy

# Steps:
1. Import all the libraries mentioned above along with os, warning and datetime. Also import drive from google, and import/read the dataset. 
2. Perform data visualization to find out the state of the data - ready to use or pre-processing required. Use pie charts, bar graphs, histograms, heat maps etc. 
3. Pre-processing - Drop the null value entries or use imputation i.e replacing with mean or median. We have dropped the null/NaN value entries.
4. Store diagnosis in a separate list. Divide the dataset into train and test in the ratio 80:20. 
5. Apply each model and print each of their accuracy scores.

# Conclusions and Performance Metrics
So, concluding the accuracy of different models:
1. AdaBoost Classifier = 98.24 %
2. Random Forest Classifier = 95.61 %
3. Decision Tree Classifier = 94.78 %
4. K Neighbours Classifier = 70.18 %
5. Naiye Bayes = 63.30 %
6. Logistic Regression = 58.82%

# Acknowledgements
I'd like to thank Prof. Bharathi R for her guidance throughout the project. I'd also like to thank my teammates - Tankala Sunaina, Sanjana Murthy and Susan Mathew for their contribution in the project.

