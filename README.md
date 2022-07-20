# Classification Models to Predict if Customer Subscribes a Given Product


Data: 
The “train.csv” contains a marketing campaign dataset of 22,606 observations that is used to train classification models. The 16 predictors are included in the dataset.

The response variable “y” indicates whether the customer subscribes the product (1 = “yes”, 0 = “no”). You are not allowed to recode the response variable.

The “test.csv” contains a dataset of 22,605 observations used to evaluate the performance of classification models. The test dataset has the same data structure as the training dataset.
Task:
Apply various predictive modeling techniques to build a classification model that performs very well for predicting if a customer subscribes the product. Below is a list of possible techniques that could help you tune your models: 

1) Deal with imbalanced dataset 

For more details, refer to https://imbalanced-learn.readthedocs.io/en/stable/index.html 

2) Assign class weight
 
3) Tune hyperparameters 

4) Use advanced models such as ensemble learning 

For more details, refer to https://scikit-learn.org/stable/supervised_learning.html 

5) Select important features 
6) Use deep learning methods 
7) Other methods…… 

You can only use the training dataset to train the classification models without touching the test dataset. You can normalize/transform the variables in the test dataset, but any resampling applied to the test dataset is not allowed. 
Model Evaluation:
The test dataset is only used to evaluate the performance of your model. Your models need to be evaluated by AUC score [area under the ROC curve, using the method sklearn.metrics.roc_auc_score() to calculate].
