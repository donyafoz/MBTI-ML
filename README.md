# Project Description
For our machine learning final project, we decided to predict
[Myers Briggs personality types(MBTI)](https://en.wikipedia.org/wiki/Myers–Briggs_Type_Indicator)
using a dataset we found on Kaggle. The dataset consists of posts users made on a personality forum:
https://www.kaggle.com/datasnaek/mbti-type

## Methods
We first cleaned up the data and did feature engineering, then 
we fit different models suchas Multinomial Naive Bayes, 
Logistic Regression, Random Forest and eXtreme Gradient Boosting. 

We used metrics such as AUC, F1 score and accuracy to 
judge the performance of our models. We then fine tuned our models and finally 
we used our model to predict the MBTI personality type of 
politicians and celebrities like Obama and Lady Gaga.

## Results
The data was heavily imbalanced, with most people identifying as introverted (I) and Intuitive (N)
rather than extroverted (E) and Sensitive (S). Because of this, all the models we tried 
(Logarithmic Regression, Random Forest, Multinomial Naive Bayes, SVM, LightGBM, and XGBoost) had 
trouble classifying extroversion vs introversion and intuition vs sensitivity. However, when we 
made a Voting Classifier using Logarithmic Regression, Random Forest, LightGBM, and XGBoost, we 
were able to achieve the best AUC-ROC score and f-scores.

## Team (alphabetical order)
Ben Khuong  
Donya Fozoonmayeh  
Nan Lin  
Tomohiko Ishihara  
Zack Pan 
