# Interview Preperation
This is for me and others to prepare themselves for their data science interview.

# Table of Contents
1. [Statistics](#statistics)
2. [Programming](#programming)
    1. [General](#general)
    2. [Big Data](#bigdata)
    3. [Python](#python)
    4. [R](#r)
    5. [SQL](#sql)
3. [Modeling](#modeling)
4. [Behavioral](#behavioral)
5. [Culture Fit](#culturefit)
6. [Problem-Solving](#problemsolving)
    
## Statistics <a name="statistics"></a>
Statistical computing is the process through which data scientists take raw data and create predictions and models backed by the data. Without an advanced knowledge of statistics it is difficult to succeed as a data scientist – accordingly it is likely a good interviewer will try to probe your understanding of the subject matter with statistics-oriented data science interview questions. Be prepared to answer some fundamental statistics questions as part of your data science interview. 

1. What is the *Central Limit Theorem* and why is it important?

**Answer**: In probability theory, the central limit theorem (CLT) establishes that, in most situations, when independent random variables are added, their properly normalized sum tends toward a normal distribution (informally a "bell curve") even if the original variables themselves are not normally distributed.

2. What is sampling? How many sampling methods do you know?

**Answer**: Sampling is taking a small sample from a bigger population. There are many types of sampling:

Random: Everyone in the target population has an equal chance of being selected

Stratified: Working out proportions needed for the sample be representative (IQ, Gender, etc.)

Opportunity: Basically based on convenience

Systematic: Chooses subjects in a systematic (i.e. orderly / logical) way from the target population, like every nth participant on a list of names.

3. What is the difference between Type I vs Type II error?

**Answer**: Type I is the incorrect rejection of a true null hypothesis. Type II is the failure to reject a false null hypothesis.

4. What is linear regression? What do the terms P-value, coefficient, R-Squared value mean? What is the significance of each of these components?

**Answer**: **Linear regression** is an analysis that assesses whether one or more predictor variables explain the dependent (criterion) variable. The **p-value** for each term tests the null hypothesis that the coefficient is equal to zero (no effect). A low p-value (< 0.05) indicates that you can reject the null hypothesis. In other words, a predictor that has a low p-value is likely to be a meaningful addition to your model because changes in the predictor's value are related to changes in the response variable. **Regression coefficients** represent the mean change in the response variable for one unit of change in the predictor variable while holding other predictors in the model constant. **R-squared** is a statistical measure of how close the data are to the fitted regression line. It is also known as the coefficient of determination, or the coefficient of multiple determination for multiple regression.

5. What are the assumptions required for linear regression?

**Answer**: There are four major assumptions: 1. There is a linear relationship between the dependent variables and the regressors, meaning the model you are creating actually fits the data, 2. The errors or residuals of the data are normally distributed and independent from each other, 3. There is minimal multicollinearity between explanatory variables, and 4. Homoscedasticity. This means the variance around the regression line is the same for all values of the predictor variable.

6. What is a statistical interaction?

**Answer**: Basically, an interaction is when the effect of one factor (input variable) on the dependent variable (output variable) differs among levels of another  factor.

7. What is selection bias?

**Answer**: Selection bias is the bias introduced by the selection of individuals, groups or data for analysis in such a way that proper randomization is not achieved, thereby ensuring that the sample obtained is not representative of the population intended to be analyzed.

8. What is an example of a dataset with a non-Gaussian distribution?

**Answer**: The Maxwell-Boltzmann distribution is a probability distribution mainly used in physics and statistical mechanics. The distribution, which describes the kinetic energy of air particles in a particular sample, was devised by James C. Maxwell and Ludwig Boltzmann.

9. What is the Binomial Probability Formula?

**Answer**: 
<p align="center">
  <img width="250" height="80" src="https://raw.githubusercontent.com/joochanshin/Interview-Prep/master/Data%20Science/img/SS1.png">
</p>

where P(x) is the probability of x successes out of N trials, N is the number of trials, and π is the probability of success on a given trial.

## Programming <a name="programming"></a>
To test your programming skills, employers will ask two things during their data science interview questions: they’ll ask how you would solve programming problems in theory without writing out the code, and then they will also offer whiteboarding exercises for you to code on the spot.

### General <a name="general"></a>
1. With which programming languages and environments are you most comfortable working?

**Answer**: This depends on what you are good with, but I would personally chose Python for data science.

2. What are some pros and cons about your favorite statistical software?

**Answer**: This is for Python

#### Advantages
* Python is easy to learn for even a novice developer. Its code is easy to read and you can do a lot of things just by looking at it. Also, you can execute a lot of complex functionalities with ease, thanks to the standard library.

* Supports multiple systems and platforms.

* Object Oriented Programming-driven.

* With the introduction of Raspberry Pi, a card sized microcomputer, Python has expanded its reach to unprecedented heights. Developers can now build cameras, radios and games with ease. So, learning Python could open new avenues for you to create some out-of-the box gadgets.

* Python has a plethora of frameworks that make web programming very flexible. Django is the most famous Python framework for web development.

* Gives rise to quick development by using less code. Even a small team can handle Python effectively.

* Allows to scale even the most complex applications with ease.

* A large number of resources are available for Python.

* Offers a built in testing framework to set debugging time and enable fastest workflows.

* IT giants like Yahoo, Google, IBM, NASA, Nokia and Disney prefer Python.

#### Disadvantages

* Python is slow

* Python is not a very good language for mobile development

* Python is not a good choice for memory intensive tasks

* It's near impossible to build a high-graphic 3D game using Python

* Has limitations with database access

* Python is not good for multi-processor/multi-core work

