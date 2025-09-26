**🌲 Forest Cover Type Classification**

This project applies multiple machine learning models to the UCI Forest CoverType dataset
 to predict forest cover types based on environmental and topographic features. With over 500,000 instances and 54 attributes (elevation, slope, aspect, soil type, etc.), the dataset provides a challenging multi-class classification problem involving seven forest cover categories.

**📌 Project Overview**

Goal: Evaluate and compare supervised ML models for classifying forest cover types.

Models Used:

Logistic Regression

K-Nearest Neighbors (KNN)

Decision Tree

Multilayer Perceptron (Neural Network)

Techniques:

- Hyperparameter tuning with GridSearchCV

- 5-fold stratified cross-validation for fair model evaluation

- Metrics: Accuracy, Precision, Recall, F1-score, Confusion Matrix


**📊 Results**

Model	              Accuracy	Precision	Recall	F1-Score
Logistic Regression	 72.7%	    71.3%	  72.7%	   71.7%
K-Nearest Neighbors	 89.7%	    89.7%	  89.7%	   89.7%
Decision Tree	       81.9%	    81.9%	  81.6%	   81.9%
MLP Neural Network	  72.8%	    73.7%	  72.8%	   71.3%

**🚀 Future Work**

Try ensembling methods like Random Forest or XGBoost.

Applying class-balancing techniques (SMOTE, oversampling).

Deploy best-performing model as a REST API for real-time predictions.

**🛠️ Tech Stack**

Python

NumPy, Pandas

Scikit-learn

Matplotlib, Seaborn
