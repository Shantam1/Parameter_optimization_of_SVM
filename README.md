# Parameter Optimization of SVM
Assignment for UCS654

## About SVM and Parameter Optimization

Support Vector Machine or SVM is one of the most popular Supervised Learning algorithms, which is used for Classification as well as Regression problems. However, primarily, it is used for Classification problems in Machine Learning.

Some of the most important parameters of SVM such as kernel, C, and gamma can be changed in order to achieve a higher accuracy. This is called as Hyperparameter Tuning. 

We can perform this task using GridSearchCV for optimizing these parameters.

In this python file, I've used a Fitness Function to optimize the parameters.

## Dataset

The dataset for the project has been downloaded from the UCI Machine Learning Repository.
[https://archive.ics.uci.edu/ml/datasets/default+of+credit+card+client]


Number of Instances: 30000

Number of Attributes: 25

## Final Result Table
![fuck](https://user-images.githubusercontent.com/117478558/233180612-5158ac56-8999-4a76-90a6-0321eea8569b.png)


## Convergence Graph
![fuckkk](https://user-images.githubusercontent.com/117478558/233180532-9479bb9f-a994-4ff1-b7b0-f0979c6e0783.png)


## Discussion
From the above graph, we can conclude that the model is well trained and parameter have been optimized due to the less gap between training and cross-validation curve.

The graph is made for the sample which has best accuracy. Sample 9 has the best accuracy of 0.97 having kernel = Poly, Nu = 1.27 and Epsilon = 6.87.

## Written By
Name : Shantam Anand
  
Roll No. : 102017142

Sub-Group: 3CS6
