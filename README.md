# ML-project-Popularity-of-News-Items
Aim of project is by using numerical features obtained from a popular news site to predict the popularity of individual news items. 

# Data:
The provided training data encompasses 280 numerical features for a website page, along with a single positive integer-valued label indicating the number of comments posted on the page. In the training data, the last column represents the label and should be extracted prior to training. The test data adheres to the same structure.

# Task 1: Regression
In this task, numerical features obtained from a popular news site are utilized to predict the popularity of individual news items. The number of comments on a page is employed as a reasonable proxy for its popularity. The objective is to train a regression model to predict the number of comments that will be posted on a page, based on the given (numerical) properties of the webpage (features). Following models are tested: OLS, RIDGE, LASSO

# Task 2: Classification
The aim is to transition the integer-valued target variable into two distinct classes utilizing the (arbitrary) thresholds outlined below:
Popularity Likes Not-Popular 0 Popular ≥ 1. In this segment, the focus is on classifying articles into these two popularity categories based on their attributes. For this task, the following classifiers will be implemented. Following models are tested: k-nearest neighbor (k-NN), a linear SVM model with default parameters.

**Results are presented inside WebStats.ipynb file**

**Credits:** This project was part of group project and was completed together with Lorenzo Parma, Aleksandra Twardowska and Sushut Munje.
