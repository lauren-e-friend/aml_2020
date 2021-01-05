Task 1: Classification on the ‘credit-g’ dataset.

Notebook Steps:

1. Determining which features are continuous and which are categorical.
2. Visualizing the univariate distribution of each continuous feature, and the distribution of the
target.
3. Spliting data into training and test set, preprocessing the data without using a pipeline and evaluating an initial LogisticRegression model with a training/validation split.
4. Using ColumnTransformer and pipeline to encode categorical variables and evaluating Logistic Regression, linear support vector machines and nearest neighbors using cross-validation. 
5. Tuning the parameters using GridSearchCV and Visualize the performance as function of the parameters for all three models.
6. Changing the cross-validation strategy from ‘stratified k-fold’ to ‘kfold’ with shuffling to optimize. 
7. Visualizing the 20 most important coefficients for LogisticRegression and Linear Support Vector Machines using hyper-parameters that performed well in the grid-search.

Task 2: Regression on Sydney Dataset.

Notebook Steps: 

1. Determining which features are continuous vs categorical. Dropping rows without a valid sales price.
2. Visualizing and analyzing the univariate distribution of each continuous feature, and the distribution of the target. 
3. Visualize the dependency of the target on each continuous feature
4. Preprocessing (Splitting data in training and test set. Using ColumnTransformer and pipeline to encode categorical variables, Imputing missing
values using SimpleImputer.) Evaluating Linear Regression (OLS), Ridge, Lasso and ElasticNet using cross-validation with the default parameters. 
5. Tuning the parameters of the models using GridSearchCV and visualizing the dependence of the validation score on the parameters for Ridge, Lasso and ElasticNet.
6. Visualizing the 20 most important coefficients of the resulting models.
