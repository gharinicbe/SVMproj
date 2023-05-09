Breast Cancer Detection using Support Vector Machine (SVM) Classifier
Introduction
This project is about building a Support Vector Machine (SVM) classifier that predicts the likelihood of a patient having breast cancer based on their clinical data. The dataset used in this project is the breast cancer dataset from scikit-learn. The aim of this project is to build a model with high accuracy in detecting breast cancer.

Methodology
The following steps were taken to build the SVM classifier:

Load the dataset and preprocess the data by normalizing the features.
Split the dataset into training and testing sets.
Use gridsearchcv technique to select the optimal hyperparameters for the SVM classifier.
Train the SVM classifier using the training data.
Evaluate the performance of the SVM classifier using the testing data.
To compare the performance of the SVM classifier with another model, a KNN classifier was also built using the same dataset.

Results
The SVM classifier was able to predict with very high accuracy (97%) the likelihood of a patient having breast cancer based on their clinical data. The KNN classifier, on the other hand, had an accuracy of 94%, which is slightly lower than the SVM classifier.

Conclusion
Based on the results, the SVM classifier is better suited for this dataset than the KNN classifier. This model can be useful for early detection of breast cancer and can aid in providing early treatment for patients.

How to Use
To use this model, you can run the SVMFINALPROJ.ipynb file which contains the code for building and evaluating the SVM classifier. You can also modify the code to try out different parameters and see if it improves the performance of the model.
