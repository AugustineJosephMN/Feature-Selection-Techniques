# Feature-Selection-Techniques
## Dropping constant features
Removing the features which have constant features which are actually not important for solving the problem statement.
### Variance Threshold 
Feature selector that removes all low-variance features.This feature selection algorithm looks only at the features (X), not the desired outputs (y), and can thus be used for unsupervised learning.
## Correlation
Removing the features which are highly correlated and also used to check the corelation between Input features and Target output.
## Mutual Information In Classification Problem Statements
MI Estimate mutual information for a discrete target variable.
Mutual information (MI) between two random variables is a non-negative value, which measures the dependency between the variables. It is equal to zero if and only if two random variables are independent, and higher values mean higher dependency.
The function relies on nonparametric methods based on entropy estimation from k-nearest neighbors distances.
#### Inshort
A quantity called mutual information measures the amount of information one can obtain from one random variable given another.
The mutual information between two random variables X and Y can be stated formally as follows:
I(X ; Y) = H(X) – H(X | Y) Where I(X ; Y) is the mutual information for X and Y, H(X) is the entropy for X and H(X | Y) is the conditional entropy for X given Y. The result has the units of bits.
### Mutual Information In Regression Problem Statements
Estimate mutual information for a continuous target variable.
Mutual information (MI) between two random variables is a non-negative value, which measures the dependency between the variables. It is equal to zero if and only if two random variables are independent, and higher values mean higher dependency.
The function relies on nonparametric methods based on entropy estimation from k-nearest neighbors distances
Mutual information is calculated between two variables and measures the reduction in uncertainty for one variable given a known value of the other variable.
#### Inshort
A quantity called mutual information measures the amount of information one can obtain from one random variable given another.
The mutual information between two random variables X and Y can be stated formally as follows:
I(X ; Y) = H(X) – H(X | Y) Where I(X ; Y) is the mutual information for X and Y, H(X) is the entropy for X and H(X | Y) is the conditional entropy for X given Y. The result has the units of bits.
## Difference Between Information Gain And Mutual Information
I(X ; Y) = H(X) – H(X | Y) and IG(S, a) = H(S) – H(S | a)
As such, mutual information is sometimes used as a synonym for information gain. Technically, they calculate the same quantity if applied to the same data.
##  Chisquare Test
Compute chi-squared stats between each non-negative feature and class.
This score should be used to evaluate categorical variables in a classification task.
This score can be used to select the n_features features with the highest values for the test chi-squared statistic from X, which must contain only non-negative features such as booleans or frequencies (e.g., term counts in document classification), relative to the classes.
Recall that the chi-square test measures dependence between stochastic variables, so using this function “weeds out” the features that are the most likely to be independent of class and therefore irrelevant for classification. The Chi Square statistic is commonly used for testing relationships between categorical variables.
It compares the observed distribution of the different classes of target Y among the different categories of the feature, against the expected distribution of the target classes, regardless of the feature categories.
