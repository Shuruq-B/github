# Abstract 
HR analytics is the process of analysing Human Resource (HR) data to enable better and data-driven decision-making. Managing promotion`s process allows leaders to evaluate each employee and their potential to be promoted. The aim of this project was to use classification models to predict whether an employee is recommended to be promoted or not. The dataset obtained from Kaggle and contained some features related to the employee. EDA was performed on the data to understand the natural of the features. The Random Forest Algorithm was selected to be our predictive model as it returned 95% in a recall and accuracy. All the findings and conclusions were presented in a presentation to provide an overall view about the analysis.


# Design

A large multinational company that has 9 broad verticals across the organisation intends to investigate the potential employees who will earn a promotion. As different companies have different timeline to issue a promotion, some predictive analysis needs to be performed in advance to determine employees who are recommended to be promoted. This will help the company to set the appropriate promotional budgets for these employees.


# Data

The data of this project obtained from Kaggle in format of .csv and contained of 54808 employees. There were 12 relevant features recorded for each employee. The numerical features were Employee ID, Number of trainings, Age, Previous Year Rating, Length of service, Awards won and Avg training score. The categorical features were Department, Region, Education, Recruitment channel and Gender. The targe variable was Is promoted. 


# Algorithms

### Data pre-processing

* Log Transformation was applied in order to reduce the skewness of some variables. 
* Synthetic Minority Oversampling Technique (SMOTE) used to handle imbalanced classes.
* Feature scaling such as Standardization.




### Models

The data was divided to training set where 70% of the data were used to train the model. Then the remaining set 30% were used to evaluate the model performance. Two approaches were used to classify our target. The first approach was linear classification where assume that classes are linearly separable. A Logistic Regression model was used in this case and the accuracy of the model on test set was 86% which indicates a good fitting. Also, the model shows a recall of 86%, precision of 87%  and F-score of 86%. 


The second approach was non-linear classification where assume that nonlinear function used to separate classes. A Random Forest model was used in this case and the accuracy of the model on test set was 95% which shows a great fit. Also, the model shows 95% in each of a recall, precision, and F-score.

As the main objective of this project is to predict the actual employees who most likely to get promoted. The recall of random forest model is preferable in comparison with logistic regression model. Therefore, the random forest model will be selected as predictive model of this project.



# Tools


Numpy and Pandas for data manipulation, Matplotlib and Seaborn for plotting, Plotly for interactive visualization, Imblearn for dealing with imbalanced classes and Scikit-learn for machine learning models. 

# Communication


Giving a summary of the analysis process and findings in form of short presentation


