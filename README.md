# Data-science-concepts

## Implement Data smoothing and Data Transformation techniques without using library

1. Dataset used - Zomato Dataset (from - https://www.kaggle.com/ronidas39/zomato-india-data-set)
2. Carried out following techniques on price column
3. Data smoothing - Binning by mean, median and boundary
4. Data Transformation - Z score and Min Max transformation
 

## Handling Missing values

1. Dataset used - Titanic Dataset (from - https://www.kaggle.com/c/titanic/data)
2. 3 columns ( 2 categorical - Cabin,Embarked and 1 numerical - Age) have missing value
3. Used 4 different approach to handle missing value and compared their performance using SVM

![image](https://user-images.githubusercontent.com/67454437/121644370-8c30df00-cab0-11eb-85c1-b54d1b0e0022.png)


## Calculate pearson correlation coefficient without any library between numerical attributed and present them in heatmap

1. Dataset used - Housing price Dataset 

## Central limit theorem

1. Dataset used - Zomato Dataset (from - https://www.kaggle.com/ronidas39/zomato-india-data-set)
2. Carried out CLT on price column


## k means clustering

1. Implemented k means without using sklearn on toy dataset
2. Visuliazed result of above implementation
3. Implemented k means using sklearn on credit card dataset (https://www.kaggle.com/arjunbhasin2013/ccdata)
4. Compared random and k means++ intialization of centroid for k means using Silhoutte score

## Naive Bayes

1. Implemented Naive Bayes on Toy dataset(given in above repository) without using sklearn
2. Implemented Gaussian probability function for numerical valued attributes
3. Used concept of laplace smoothing to avoid zero probability problem for categorical variable 

## Linear regression by sklearn

1. Dataset used - Boston house (Inbuilt in sklearn)
2. Implemented Linear regression using sklearn for different number of iteration(10-10000)
3. Calcualted Mean Absoulte error(MAE) and Mean square error(MSE) for each iteration
4. Plotted MAE and MSE vs number of iterations

## Implement linear regression with Ridge regularization using Gradient descent method

1. Dataset used - Boston house (Inbuilt in sklearn)
2. Implement Linear regression using gradient descent for different values of alpha
3. Plot MAE vs number of iterations for different values of alpha
4. Find optimal alpha value from plot
5. calculated test and train error for different value of lambda (regularization parameter)
6. plot train and test error vs lambda values
7. Found optimal value of lambda

## KNN for uniform and distance weight

1. Dataset used - Iris Dataset
2. Compared the result of different number of neighbours for uniform and distance weight
3. Found that as number of neighbours increases, accuracy decreased drastically for uniform while remain almost constant for distance weight

## Transfer learning

