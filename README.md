## Customer Churn Prediction Using ANN

This repository contains code and resources for predicting customer churn using Artificial Neural Networks (ANN). Customer churn prediction is crucial for businesses to understand and anticipate customer behavior, allowing them to take proactive measures to retain customers.


<h5>Introduction</h5>
Customer churn refers to the phenomenon where customers leave a service or product provider and switch to a competitor. Predicting customer churn is essential for businesses to implement strategies that can prevent customers from leaving. This repository provides a solution to predict customer churn using Artificial Neural Networks (ANN).

<h5>Dataset</h5>
The dataset used for this project can be found in the data directory. It includes features related to customer interactions, demographics, and previous usage patterns. The target variable is whether the customer churned or not.

<h5>Requirements</h5>
To run the code and reproduce the results, you need the following dependencies:

Python 3.x
NumPy
Pandas
Scikit-Learn
Keras (with TensorFlow backend)


<h4>Result</h4>

Model performance is evaluated using metrics such as accuracy, precision, recall, F1-score, and AUC-ROC. Special attention is given to measuring the model's ability to correctly identify churned customers despite the imbalanced nature of the dataset

<b>Before Handling imbalanced dataset</b>
<img

<h5>Handling imbalanced dataset</h5>
To run the code <b>pip install imbalanced-learn</b>

<li>Undersampling</li>
Check classification report above. f1-score for minority class 1 improved from 0.57 to 0.76. Score for class 0 reduced to 0.75 from 0.85 but that's ok. We have more generalized classifier which classifies both classes with similar prediction score

<li>Oversampling</li>
Check classification report above. f1-score for minority class 1 improved from 0.57 to 0.76. Score for class 0 reduced to 0.75 from 0.85 but that's ok. We have more generalized classifier which classifies both classes with similar prediction score

<li>SMOTE</li>
SMOTE Oversampling increases f1 score of minority class 1 from 0.57 to 0.81 (huge improvement) Also over all accuracy improves from 0.78 to 0.80




