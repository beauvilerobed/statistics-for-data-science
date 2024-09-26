# Notes on Statistics for Data Science

## Exploratory Data Analysis
-  Estimates of Location
-  Elements of Structured Data
-  Compute the mean, trimmed mean, the median of the state 
-  Compute the average murder rate for the country
-  Compute the median murder rate for the country
-  Estimates of Variability
-  Estimates Based on Percentiles
-  Percentile: Precise Definition
-  Computing standard deviation, quantiles, and MAD of State Population
-  Exploring Data Distribution
-  Percentiles and Boxplots
-  Compute some percentiles of the murder rate by state
-  Plotting boxplot of the population by state
-  Frequency Table and Histograms
-  Compute Frequency Table for Population By State
-  Plotting a Histogram
-  Density Plots and Estimates
-  Plotting density plot superposed on a histogram
-  Exploring Binary and Categorical Data
-  Plotting Bar Charts of Airport Delays Per Year By Cause
-  Mode and Expected Value
-  Probability
-  Further Reading
-  Correlation
-  Compute Correlation Between Telecommunication Stock Returns From June 2015 Through July 2021 
-  Compute Heatmap of Daily Returns for Major Exchange-traded Funds (ETFs)
-  Scatterplots
-  Plotting Scatterplot of Correlation Between Returns for ATT and Verizon
-  Exploring Two or More Variables
-  Hexagonal Binning and Contours (Plotting Numeric Versus Numeric Data)
-  Plotting Hexagonal Binning of Relationship Between the Finished Square Feet and Tax-assessed Value for Homes in King County
-  Plotting Contour Plot for Tax-assessed Value vs. Finished Square Feet
-  Two Categorical Variables
-  Compute Contingency Table Between a Grade of a Personal Loan and Outcome of That Loan
-  Categorical and Numeric Data
-  Plotting Boxplot of Percentage of Flights in a Month By Carrier’s Control
-  Plotting Violin Plot of Percent of Airline Delays by Carrier
-  Visualizing Multiple Variables
-  Plotting Facets (Hexagonal Bins of Tax-assessed Value vs. Finished Square Feet Conditioning on Zip Code)

## Data and Sampling Distributions
-  Random Sampling and Sample Bias
-  Size Versus Quality: When Does Size Matter?
-  Sample Mean Versus Population Mean
-  Selection Bias
-  Sampling Distribution of a Statistic
-  Plotting histogram of annual income of loan applicants, mean of 5 applicants, mean of 20 applicants
-  The Bootstrap
-  Bootstrap confidence interval for the annual income of loan applicants, based on a sample of 20
-  Compute boostrap statistics (bias and standard error)
-  Confidence Intervals
-  Normal Distribution
-  Standard Normal and QQ-Plots
-  Plotting QQ-Plot of a sample of 100 values drawn from a standard normal distribution
-  Long-Tailed Distribution
-  Plotting QQ-Plot of the returns for Netflix(NFLX)
-  Student's t-Distribution
-  Binomial Distribution
-  Compute binomial PMF and CDF of observing 3 sales in 200 clicks with p = .02
-  Chi-Square Distribution
-  F-Distribution
-  Poisson and Related Distributions
-  Simulating and plotting poisson distribution
-  Simulating and plotting exponential distribution
-  Simulating and plotting weibull distribution

## Statistical Experiments and Significance Testing
-  A/B Testing
-  Why Have a Control Group?
-  Why Just A/B? Why Not C, D,…?
-  Caution Story (Facebook)
-  Further Reading
-  Hypothesis Tests
-  The Null Hypothesis
-  Alternative Hypothesis
-  One-Way Versus Two-Way Hypothesis Tests
-  Resampling
-  Permutation Test
-  Example: Web Stickiness
-  Exhaustive and Bootstrap Permutation Tests
-  Permutation Tests: The Bottom Line for Data Science
-  Table for ecommerce experiment results
-  p-Value
-  Alpha
-  p-value controversy
-  Practical signicance
-  Type 1, Type 2 Errors, Data Science, and p-Values
-  Statistical Significance and p-Values
-  t-Tests
-  Multiple Testing
-  Degrees of Freedom
-  Further Reading
-  ANOVA
-  Plotting Boxplots Of The Four Webpages
-  Compute the permutation test (ANOVA)
-  F-Statistic
-  Two-Way ANOVA
-  Chi-Square Test
-  Chi-Square Test: A Resampling Appproach
-  Compute Permutation Test (Chi-Square)
-  Chi-Square Test: Statistical Theory
-  Plotting Chi-Square Distribution With Different Degrees Of Freedom
-  Fisher's Exact Test
-  Detecting Scientific Fraud
-  Relevance for Data Science
-  Multi-Arm Bandit
-  Further Reading
-  Power and Sample Size
-  Sample Size

## Regression and Prediction
-  Simple Linear Regression
-  Multiple Linear Regression
-  Assessing the Model
-  Cross-Validation
-  Model Selection and Stepwise Regression
-  Weighted Regression
-  Prediction Using Regression
-  Factor Variable in Regression
-  Factor Variables with Many Levels
-  Ordered Factor Variables
-  Interpreting the Regression Equation
-  Regression Diagnostics
-  Polynomial and Spline Regression

## Classification
- Naive Bayes
- Why Exact Bayesian Classification Is Impractical
- Discriminant Analysis
- Covariance Matrix
- Fisher's Linear Discriminant (A Simple Example)
- Using Discriminant Analysis for Feature Selection
- Logistic Regression
- Logistic Response Function and Logit
- Logistic Regression and the GLM
- Interpreting the Coefficients and Odds Ratios
- Linear and Logistic Regression: Similarities and Differences
- Maximum Likelihood Estimation
- Evaluating Classification Models
- Confusion Matrix
- The Rare Class Problem
- Precision, Recall, and Specificity
- ROC Curve
- Precision-Recall Curve
- AUC
- Lift
- Strategies for Imbalanced Data
- Undersampling
- Oversampling and Up/Down Weighting
- Data Generation
- Cost-Based Classification
- Exploring the Predictions

## Statistical Machine Learning
- K-Nearest Neighbors
- A Small Example: Predicting Loan Default
- Distance Metrics
- One Hot Encoder
- Standardization (Normalization, z-Scores)
- Choosing K
- KNN as a Feature Engine
- Tree Models
- A Simple Example
- The Recursive Partitioning Algorithm
- Measuring Homogeneity or Impurity
- Stopping the Tree from Growing
- Controlling tree complexity in Python
- Predicting a Continuous Value
- How Trees Are Used
- Bagging and the Random Forest
- Variable Importance
- Hyperparameters
- Boosting
- The Boosting Algorithm
- XGBoost
- Regularization: Avoiding Overfitting
- Ridge Regression and the Lasso
- Hyperparameters and Cross-Validation
- XGBoost Hyperparameters

## Unsupervised Learning
- Principal Components Analysis
- A Simple Example
- Computing the Principal Components
- Interpreting Principal Components
- How Many Components to Choose?
- Correspondence Analysis
- K-means Clustering
- A Simple Example
- K-Means Algorithm
- Interpreting the Clusters
- Selecting the Number of Clusters
- Hierarchical Clustering
- A Simple Example
- The Dendrogram
- The Agglomerative Algorithm
- Measures of Dissimilarity
- Model-Based Clustering
- Multivariate Normal Distribution
- Mixtures of Normals
- Selecting the Number of Clusters
- Scaling and Categorical Variables
- Scaling the Variables
- Dominant Variables
- Categorical Data and Gower's Distance
- Problems in clustering with mixed data types