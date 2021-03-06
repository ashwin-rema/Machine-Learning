# Machine-Learning
My machine learning projects

1. Diabetes Prediction model for women
2. Digital digit recognition model

## 1.Diabetes Prediction model for women

# Problem Statement:
              The objective of the dataset is to diagnostically predict whether or not a patient has diabetes, based on certain diagnostic measurement from the given dataset. This dataset is originally from the National Institute of Diabetes and Digestive and Kidney Diseases
Note: Several constraints were placed on the selection of these dataset from a larger database. In particular, all patients included here are females who are at least 21 years old of prima Indian heritage.

# Package And IDE’s:
# Google Colaboratory:  
                      It is a jupyter notebook environment that runs in the browser using google cloud servers. It is a widely popular cloud service for machine learning that features free access to faster GPU and TPU computing resources. Colab notebooks allows you to combine executable code and rich text in a single document, along with images, HTML, laTeX and more. It is simply a cloud-based service that replicates jupyter notebook in the cloud. Colaboratory can be used to perform many tasks such as to write and run code, create its associated documentation and display graphics. It allows for faster GPU access and easy sharing. It is highly integrated with google drive making them easy to set-up and access.

# Sklearn:
                  Scikit-learn popularly known as Sklearn is a free software machine learning library for the python programming. It is a simple and efficient tool for predictive data analysis. It features various classification, regression and clustering algorithms such as random forests, gradient boosting, support vector machines, k-means and DBSCAN and it is designed to interoperate with the python numerical and scientific library numpy and scipy. It is open-source and is commercially usable to everyone.

# Pandas:
                  Pandas is a software library written for the python programming language for data manipulation and analysis. In particular it offers data structures and operations for manipulating numerical tables and time series. Pandas allows for various data manipulation operations such as merging, reshaping, selecting as well as data cleaning and data wrangling features. It is a free software that is mainly used for data analysis.

# Problem Solution:
                   The given problem is a type of binary classification problem which comes under supervised learning. The given problem is solved by adopting a logistic regression approach. Logistic regression is a useful regression method for solving binary classification problem. Logistic regression is a statistical method for predicting binary classes. Logistic regression predict the probability of occurrence of a binary event utilizing a logit function. It is a special case of linear regression where it computes the probability of an event occurrence. The prediction is built by using a logistic regression classifier.
                   The pandas(a python data analysis library) library is used to load the given dataset from the given csv file using the read_csv method.
                   The Scikit-Learn(a machine-learning library) library is used for building the prediction model. The given columns is divided into two types of variable – dependent and independent variable. Then the given dataset is divided into a training set and a test set in the ratio of 4:1 using the test_train method from model_selection class. The logistic regression classifier object is created using the LogisticRegression class. Build your model on the training set using the fit method and then perform prediction on the test set using the predict method.
                   The accuracy score of the prediction model is found by using accuracy_score method on a scale of 0 to 1. This method notifies how accurate our prediction model is 83%.
                   The confusion matrix of the prediction model is found by using the confusion_matrix method. A confusion_matrix is a table that is used to evaluate and visualize the performance of a classification model. The fundamental of a confusion matrix is that the number of correct and incorrect predictions are summed up class-wise.
                   Both accuracy_score and confusion_matrix are methods in the metrics class in scikit-learn library.


# Conclusion:
                    The diabetes prediction model has an accuracy of nearly 83%. And the model can be used efficiently to predict whether a patient has diabetes or not using the given diagnostic data to a considerable extent. From the output of the prediction model, the number of correct prediction is 127 and the number of incorrect prediction is 127(type I error is 11 and type II error is 16). The above mentioned prediction model is successfully implemented in python in google colaboratory as a notebook file.


## 2. Digital digit recognition model

# Problem Statement:
              The objective of the dataset is to diagnostically predict whether or not a patient has diabetes, based on certain diagnostic measurement from the given dataset. This dataset is originally from the National Institute of Diabetes and Digestive and Kidney Diseases
Note: Several constraints were placed on the selection of these dataset from a larger database. In particular, all patients included here are females who are at least 21 years old of prima Indian heritage.

# Package And IDE’s:
# Google Colaboratory:  
                      It is a jupyter notebook environment that runs in the browser using google cloud servers. It is a widely popular cloud service for machine learning that features free access to faster GPU and TPU computing resources. Colab notebooks allows you to combine executable code and rich text in a single document, along with images, HTML, laTeX and more. It is simply a cloud-based service that replicates jupyter notebook in the cloud. Colaboratory can be used to perform many tasks such as to write and run code, create its associated documentation and display graphics. It allows for faster GPU access and easy sharing. It is highly integrated with google drive making them easy to set-up and access.

# Sklearn:
                  Scikit-learn popularly known as Sklearn is a free software machine learning library for the python programming. It is a simple and efficient tool for predictive data analysis. It features various classification, regression and clustering algorithms such as random forests, gradient boosting, support vector machines, k-means and DBSCAN and it is designed to interoperate with the python numerical and scientific library numpy and scipy. It is open-source and is commercially usable to everyone.

# Pandas:
                  Pandas is a software library written for the python programming language for data manipulation and analysis. In particular it offers data structures and operations for manipulating numerical tables and time series. Pandas allows for various data manipulation operations such as merging, reshaping, selecting as well as data cleaning and data wrangling features. It is a free software that is mainly used for data analysis.

# Problem Solution:
                 The given problem is a type of binary classification problem which comes under supervised learning. The given problem is solved by adopting a logistic regression approach. Logistic regression is a useful regression method for solving binary classification problem. Logistic regression is a statistical method for predicting binary classes. Logistic regression predict the probability of occurrence of a binary event utilizing a logit function. It is a special case of linear regression where it computes the probability of an event occurrence. The prediction is built by using a logistic regression classifier.
                 The pandas(a python data analysis library) library is used to load the given dataset from the given csv file using the read_csv method.
                 The Scikit-Learn(a machine-learning library) library is used for building the prediction model. The given columns is divided into two types of variable – dependent and independent variable. Then the given dataset is divided into a training set and a test set in the ratio of 4:1 using the test_train method from model_selection class. The logistic regression classifier object is created using the LogisticRegression class. Build your model on the training set using the fit method and then perform prediction on the test set using the predict method.
                 The accuracy score of the prediction model is found by using accuracy_score method on a scale of 0 to 1. This method notifies how accurate our prediction model is.
                 The confusion matrix of the prediction model is found by using the confusion_matrix method. A confusion_matrix is a table that is used to evaluate and visualize the performance of a classification model. The fundamental of a confusion matrix is that the number of correct and incorrect predictions are summed up class-wise.
            Both accuracy_score and confusion_matrix are methods in the metrics class in scikit-learn library.



# Conclusion:
                    The diabetes prediction model has an accuracy of nearly 83%. And the model can be used efficiently to predict whether a patient has diabetes or not using the given diagnostic data to a considerable extent. From the output of the prediction model, the number of correct prediction is 127 and the number of incorrect prediction is 127(type I error is 11 and type II error is 16). The above mentioned prediction model is successfully implemented in python in google colaboratory as a notebook file.
