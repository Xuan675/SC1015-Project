# SC1015 Data Science Project - Titanic

# About
This is our Mini-Project for SC1015 which focus on predicting the survial rate of passengers in Titanic. 
![alt text](https://services.meteored.com/img/article/titanic-10-curiosidades-sobre-el-naufragio-mas-famoso-de-la-historia-1681429632845_768.jpg)

For detailed walkthrough, please view the source code in order from:
Mini-Project_1_Data_Preperation
Mini-Project_2_Data_Visualization
Mini-Project_3_Finding_Best_Model
Mini-Project_FinalSolution

# Contributors
1. Tham Mao Hen - Data Visualization
2. Ng Yi Xiang - Data Cleaning, Data Extraction
3. Law Zhi Xuan - Model Implementation

# Problem Statement
To find out what is the best prediction model and the best predictor to predict the survival rate of the passengers on the Titanic. 

# Content Page
This is our content for our project on how we went about doing the project.
1. Import required libraries
2. Importing data
3. Data Preparation
4. Data Visualization and Analysis
5. Split Training and Test data
6. Choosing the best model
7. Finding individual predictor that best predict survival
8. Comparing Sex vs Survival on actual test data
9. Conclusion

# Models/Classifiers used
1. Logistic Regression
2. KNN or k-Nearest Neighbors
3. Support vector machines
4. Naive Bayes Classifier
5. Decision Tree
6. Random Forest
7. Perceptron

# What did we learn from this project?
1. Logistic Regression from sklearn
2. Random Forest from sklearn
3. Collaborating using GitHub
4. Converting Numeric Data to Categorical Data

# Conclusion
Through the entire course the project, there are clear conclusions that we were able to draw from analyzing the datasets provided.

1. It is clear to use that out of all the different Prediction models we've used, we have found that Random Forest Classification method has the highest accuracy for predicting the Survival of the people in our data set.

2. We have also found that 3 predictors played an impactful part in the predictions, which are Sex,Pclass and Fare. With Sex being the best predictor out of the 3.

3. One special case would be evidence of people aged 16 had a higher chance of survival when comparing to other ages based on the proportion of their sample size. This means that in general the youngest age group (age below 16) has a higher chance of survival.

In terms of what these conclusions tells us about the dataset, we can conclude that during the tragic accident on the Titanic, woman and children's safety and wellbeing was prioritized, which would have explained the data we used.

# References
https://www.kaggle.com/competitions/titanic

https://www.datacamp.com/tutorial/understanding-logistic-regression-python

https://www.analyticsvidhya.com/blog/2021/06/understanding-random-forest/
