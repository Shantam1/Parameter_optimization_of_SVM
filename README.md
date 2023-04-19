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

| Sample  | Best Accuracy | Best Kernel | Best Nu | Best Epsilon |
| -----   | ------------- | ----------- | ------- | ------------ |
| 1 | 0.62 | Linear | 2.46 | 8.23 |
| 2 | 0.78 | Sigmoid | 5.13 | 9.82 |
| 3 | 0.68 | Sigmoid | 3.13 | 9.28 |
| 4 | 0.77 | Poly | 1.49 | 2.92 |
| 5 | 0.69 | Linear | 3.52 | 7.54 |
| 6 | 0.77 | Sigmoid | 5.60 | 3.80 |
| 7 | 0.77 | Sigmoid | 0.29 | 7.74 |
| 8 | 0.72 | Linear | 4.87 | 3.13 |
| 9 | 0.26 | Poly | 1.27 | 3.63 |
| 10 | 0.73 | Poly | 3.96 | 0.52 |

## Convergence Graph
![graph](https://user-images.githubusercontent.com/72306997/233000047-3bbc6cf2-8ec0-4276-8519-17da7da2fb25.png)

## Discussion
From the above graph, we can conclude that the model is well trained and parameter have been optimized due to the less gap between training and cross-validation curve.

The graph is made for the sample which has best accuracy. Sample 9 has the best accuracy of 0.97 having kernel = Poly, Nu = 1.27 and Epsilon = 6.87.

## Written By
Name : Shantam Anand
  
Roll No. : 102017142

Sub-Group: 3CS6
