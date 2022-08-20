# Admission-Prediction

An admission prediction tool which helps you know your probabilities of admission into a particular college

This project uses the dataset from https://github.com/harshchaludia/admission-predictor/blob/master/admission.csv and predicts if a student will get an admission (on based on his/her TOEFL, SOP, LOR, CV, GPA, Research paper, GRE) to university or not.

This is a regression problem. I have implemented following parts.

Data Visualization and Correction.
ML Algorithm accuracy comparison with BoxPlot.
Calculated the accuracy of the overall model.
Find the overall accuracy with different Sklearn Machine learning modules like 'Logistic Regression' , 'CART', 'Linear Discriminant Analysis (LDA)' , 'K Neighbour Classifier' , 'Random Forest Classifier' , 'Naive Bayes' and 'Support Vector Machine'.
After a thorough comparison, We take logistic regression as the best fit for our dataset which has maximum accuracy.
The prediction model is finally made to achieve results between 0 and 1. Using proba function we estimate the probability of admission.
