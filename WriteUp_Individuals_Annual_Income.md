   # Individuals Annual Income in The USA




 ## Abstract:

 The goal of this project is to build a classification model to accurately predict whether an individual annual income in the U.S is more or less than 50k. The datasets were imported from the U.S Census website (https://census.com/). Different machine learning models, future engineering, and techniques were applied to successfully accomplish our project. 

 ## Design:

 Starting with performing EDA and data cleaning, we found that our data is imbalanced so a weight adjustment by *3 was necessary to prevent overfitting and a low F1 score. A Knn model was selected as a baseline for it is simplicity and to have a better insight about our data and following procedure.


 ## Data:

 The data contain over 280000 rows and more than 40 columns. Most of it was categorical such as work class, education, marital status, gender, race, etc...


 ## Algorithms:

### Feature Engineering

1.	Converting categorical features to binary dummy variables
2.	Converting the target columns to binary
3.	Squaring the age features helped to improve our data accuracy
4.	Trying different feature engineerings such as addition multiplication and division
5.	Using stacking

### Models

* Logistic regression
* Logistic Regression 3*1(Balanced by multiplying 1's rows by 3)
* Logistic Regression 3*1 age^2 (in addition to balancing age is squared)
* stacked (stacking(Logistic regression,Logistic Regression 3*1 age^2,kNN))
* kNN
* Scaled Logistic Regression
* Decision Tree
* Extra Trees
* Random forest 

### Model Evaluation and Selection

 The entire dataset of 280k observation was split into 92/4/4 train/validation/ Test. While examining our results from all models we found that logistic regression is the best in terms of F1, train, validation ROC, and test outcomes.

* Final random Logistic regression score: 
* Training accuracy 0.938
* Testing accuracy 0.939
* F1 score 0.544
* Recall 0.569
* Precision 0.569

 ## Tools:

 * Jupyter Notebook  
 * Statsmodels.api  
 * Seaborn 
 * Statsmodels.formula.api 
 * Matplotlib 
 * Numpy 
 * Pandas 
 * Sklearn 
 * Patsy 
 * Pickle

 ## Communication:

 We used pdf and PowerPoint slides to communicate our findings and results.


   
   
   
   
   
   
   
   
   
   
   
   
   
   


