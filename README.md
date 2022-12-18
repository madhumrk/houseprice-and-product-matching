# houseprice-and-product-matching
Completed the given 2 assignment as part of Shack Labs DS Internship Assignment:

House Price Prediction
Matching of Amazon and Flipkart Products

Libraries & Frameworks Used
For assignment 1: House Price Prediction
Numpy
Pandas
Matplotlib
Seaborn
Sk-learn
linear regresion
R square and adjusted R square

For assignmet 2: Product Matching
pandas
Tensorflow_hub

Machine Learning Models Performance Comparison for Task 1: House Price Prediction
Drawbacks related to Underlying Assumptions of Machine Learning Algorithms

The assumptions associated with regression modeling and machine learning in general are as follows:

Multicollinearity : There is minimal or no multicollinearity among the independent variables. It usually requires a large sample size to predict properly. It assumes the observations to be independent of each other.
Homoscedasticity: The variance of residual should be the same for any value of X.
Observations are assumed to be independent of each other.
For most of the machine learning algorithms such as Linear Regression and many clustering algorithms, normal distribution is necessary for producing better outcomes.
Unstability: Tree-based models are relatively unstable. A small change in the data can cause a large change in the structure of the decision tree causing instability.
Non-scalability: Several boosting models such as XGBoost and Gradient Boosting models are very sensitive to outliers since every classifier is forced to fix the errors in the predecessor learners. The overall method is hardly scalable. Moreover, they don't perform well enough on sparse and unstructured data due to their internal working and underlying assumptions.
