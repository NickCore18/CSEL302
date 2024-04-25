# **CSEL302- Introduction to Intelligent Systems**
___
## **Introduction**
  > Welcome to my CSEL302 Webpage! CSEL302 is the Introduction to Intelligent Agents course I'm currently taking under Mr. Mark Bernardino. Below is a compilation of all assigned activities, and bits of info relating most notably to Linear and Logistic Regression, two techniques used in predictive modelling that allows us to have valuable insights into datasets.
___
## **Table of Contents**


*   [Introduction to AI and Intelligent Agents](#introduction-to-ai-and-intelligent-agents)
*   [Data Analysis and Visualization](#data-analysis-and-visualization)
*   [Probability and Statistics ](#probability-and-statistics)
*   [Linear Regression](#linear-regression)
*   [Logistic Regression](#logistic-regression)
- [Activities](#activities)
- [Midterm Exam](#midterm-exam)
- [Conclusion](#conclusion)
___
## **Introduction to AI and Intelligent Agents**
>AI refers to the intelligence demonstrated by machines, as opposed to the natural intelligence possessed by humans and animals.

>It encompasses a wide range of techniques and technologies that enable machines to perceive, learn, reason, solve problems, and act autonomously.
___
## **Data Analysis and Visualization**
### Data Processing
> Data collection is the process of gathering information. Just like collecting different types of toys or stamps, data collection involves bringing together pieces of information from various sources. This information could be anything from survey responses and observations to measurements and interviews.
### Data Preprocessing
> Data preprocessing is the process of getting your data ready for analysis or machine learning by cleaning, organizing, and formatting it. It involves tasks like removing errors, dealing with missing information, and making sure the data is in a usable form. Think of it as preparing ingredients before cooking – you want them clean and well-prepared for the best results. In data analysis, having clean and well-organized data ensures accurate and meaningful insights.
### Exploratory Data Analysis
> It is a critical process in data analysis, and it serves as the initial step before diving into more in-depth analysis or modeling. It helps:


1. Understand Data
2. Identify Patterns
3. Detect Anomalies
4. Formulate Hypotheses
5. Guide Decision-Making
6. Communicate Insights


### Data Visualization Tools
- Matplotlib is like a versatile artist's toolkit for creating all sorts of charts and graphs. It's as if you have a canvas, and Matplotlib provides you with brushes and colors to paint your data.
- Seaborn is like a stylist that makes your data look fashionable. It's built on top of Matplotlib and adds some extra beauty and ease to your visualizations.
___
## **Probability and Statistics**
### Probability
>Probability implies 'likelihood' or 'chance'. When an event is certain to happen then the probability of occurrence of that event is 1 and when it is certain that the event cannot happen then the probability of that event is 0.

### Probability Distributions
> A probability distribution describes the likelihood of each possible outcome for a random variable. It tells us how probable each value is and provides a complete picture of the random variable's behavior.

### Descriptive Statistics
- **Mean (Average):** It's the sum of all values divided by the number of values.
- **Median:** It's the middle value when data is sorted, or the average of the two middle values if there's an even number of values.
- **Variance:** It quantifies the spread or dispersion of data points from the mean.
- **Standard Deviation:** It's the square root of the variance and measures the average deviation from the mean.
___
## **Linear Regression**
### Linear Regression
> a statistical method used in the field of data analysis and predictive modeling. It's particularly useful in understanding and modeling relationships between a dependent variable (target) and one or more independent variables (features or predictors). 

> Linear Regression is used when you want to understand the relationship between variables and make predictions based on that relationship. It's often applied in fields like economics, finance, and the natural sciences.

### Types of Variables
- The dependent variable, also known as the "response variable" or "outcome variable," is the variable that you are trying to understand, predict, or explain in a statistical analysis or experiment. It's the variable that you measure or observe. Its value depends on the values of other variables in the study.
- The independent variable, also known as the "explanatory variable" or "predictor variable," is the variable that you manipulate or examine to see how it affects the dependent variable.

### Types of Errors in Linear Regression
- **Residuals:** The difference between the observed and predicted values.
- **Mean Squared Error (MSE):** A measure of the average squared difference between observed and predicted values.
- **Root Mean Squared Error (RMSE):** The square root of MSE, providing a more interpretable measure of error.

### Model Selection
- **Adjusted R-Squared:** A measure of model goodness-of-fit that penalizes for adding unnecessary variables.
- **AIC (Akaike Information Criterion):** A measure that takes into account both goodness of fit and the number of parameters.
- **BIC (Bayesian Information Criterion):** Similar to AIC but places a higher penalty on model complexity.

### Regression Diagnostics
- **Linearity:** You can use scatterplots or residual plots to check for linearity.
- **Homoscedasticity:** Check the spread of residuals at different levels of the independent variable.
- **Normality:** Use normal probability plots or statistical tests to assess the normality of residuals.
- **Independence:** Ensure that residuals are not correlated over time or among observations.
___

## **Logistic Regression**
> Logistic Regression is a statistical technique used for predicting the outcome of a categorical dependent variable based on one or more predictor variables. It models the probability of a binary event occurring, such as success/failure, yes/no, or pass/fail scenarios.

>Logistic Regression is based on the concept of odds and log-odds. The odds of an event is the ratio of the probability of the event to its complement. The logistic model uses these odds, transformed via the logarithm, to predict the probability of the target class.

>Logistic Regression's flexibility makes it applicable in many fields. In medicine, it predicts disease presence or absence. In finance, it assesses credit risk. In marketing, it helps predict customer churn. These examples underscore its versatility.

>Developing a Logistic Regression model involves several key steps: First, selecting relevant features. Second, using a training dataset to fit the model. Finally, interpreting the model coefficients to understand the influence of each predictor.

>Evaluating the performance of a Logistic Regression model involves metrics such as Accuracy, Precision, Recall, and the F1 Score. The ROC Curve and AUC provide insights into the model's ability to distinguish between classes.

> While powerful, Logistic Regression faces challenges like multicollinearity among predictors and the risk of overfitting. Techniques such as regularization and careful feature selection can mitigate these issues, enhancing model reliability.

## Activities
- <a href = "https://nbviewer.org/github/NickCore18/CSEL302/blob/main/2A_CORONADO_EXER4.ipynb">Exercise 4</a>
- <a href = "https://nbviewer.org/github/NickCore18/CSEL302/blob/main/2A_CORONADO_EXER5.ipynb">Exercise 5</a>
- <a href = "https://nbviewer.org/github/NickCore18/CSEL302/blob/main/2A_CORONADO_EXER6.ipynb">Exercise 6</a>
- <a href = "https://nbviewer.org/github/NickCore18/CSEL302/blob/main/2A_CORONADO_EXER7.ipynb">Exercise 7</a>

## Midterm
- <a href = "https://nbviewer.org/github/NickCore18/CSEL302/blob/main/2A_CORONADO_MIDTERM.ipynb">Exercise 7</a>

## Conclusion
> Throughout my learning journey in data analysis and visualization, I have gained invaluable insights into predictive modeling. Linear regression has allowed me to understand relationships between variables and make informed predictions, while logistic regression has enabled me to predict outcomes based on categorical variables. The hands-on activities and midterm exam have been particularly helpful in reinforcing my learning and challenging me to apply these concepts in various scenarios. Overall, this journey has not only expanded my knowledge but also equipped me with the skills to confidently tackle complex data analysis tasks.
