# Objective
The objective of this project is to explore a data set, define a research question, build models to solve the problem.
Activities include:
* Exploring and preparing the data
* Defining the problem
* Defining an experiment setup
* Implementing the proposed approach
* Evaluating and analysing the results

# Problem
The goal is to build a model to estimate the amount of suicides for a given group provided its socio￾economic conditions. This will be of great use for support organizations in enabling them to focus on the right 
groups. We will focus our research to answer the below.
* For a given group can we classify the amount of suicides into high, medium or low. We will use macro f1-
score for evaluation in order to give importance to every class.
* Are suicides more in a particular age / gender? We will take help of visual plots for evaluation.
* Does any socio-economic condition i.e. GDP, HDI has a linear relation on suicides? We will use R-squared 
to estimate the variability explained.
The null hypothesis here would be that the classifiers have the same performance over the given data while the 
alternate hypothesis would be that the classifiers have different performance over the given data. We will use one￾sided paired t-test to reject null hypothesis for p < 0.05.

# Dataset
I have chosen Suicide Rates Overview 1985 to 2016 Dataset from [Kaggle](https://www.kaggle.com/russellyates88/suicide-rates-overview-1985-to-2016/download)

# Report
The report details out the Setup, Approach, Experiments, Results and Conclusion. Please refer to [EstimateSuicideRate - Report.pdf](https://github.com/harinath0906/Estimate-Suicide-Rates/blob/master/EstimateSuicideRate%20-%20Report.pdf)

# Notebook:
Please refer to the colab version of the notebook from here [https://colab.research.google.com/drive/1UUQ901QUUEsLt8qrblZ_jYpy6wrC5DWe?usp=sharing](https://colab.research.google.com/drive/1UUQ901QUUEsLt8qrblZ_jYpy6wrC5DWe?usp=sharing) as GitHub is unable to open this notebook due to large size.
