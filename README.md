# DataAnalitics
Template that will be helpfull to create other repositories in order to build ML or similar projects.

## Table of contents
- [First steps](#first-steps)
    * [Find data](#find-data)
    * [Understand problem](#understand-problem)
    * [Define objectives](#define-objectives)
- [Data preparation](#data-preparation)
    * [Upload data](#upload-data)
    * [Data cleaning](#data-cleaning)
    * [Data transformation](#data-transformation)
- [Exploratory data analysis](#exploratory-data-analysis)
- [Data modeling](#data-modeling)
- [Visualisation](#visualization)
- [Deploy and Maintain](#deploy-and-maintain)

# First steps
## Find data
Most important thing at the very beggining, there must be some data to analyze. In order to do so, look for some data (ex. Kaggle).

Good sources of data:
- web sevices
- logs
- databases
- API's 
- online repositories
## Understand problem
After finding data set, there must be something to solve. Some predictions, analysis etc. has to be done.

Define business requirements.
## Define objectives
Moving foreward, to solve problems, define objectives. It means that, it has to be known what to do and why. Order is also important.

Don't be afraid to ask questions. More questions done more answers get.
# Data preparation
## Upload data
First of all it has to be some data to analyze. In order to do so put ur train/test .csv files into data folder.
## Data cleaning
Think about what to do with invalid data.

Things that may appear:
- inconsistent DataTypes
- misspelled attributes
- missing values
- duplicate values
## Data transformation
Modify data basing on what is necessary in solving project problems.

Helping tools that will perform complex transformations:
- talend
- informatica.

It will help understanding data structure better.
# Exploratory data analysis
Data mining starts with geting some knowledge about data package. 
Give a look into:
* content - what is the content of each column
* types - each column has its own data type, it may be int, float or object
* classes - if You want to do a ML project with predictions included You have to pick which column is Your class that You will try to predict
* usefullness - think about which column is usefull and which is not, if some columns are potencially usefull make sure they have proper data type.

Then define and refine the selection of variables that will be usefull in the model development.

# Data modeling
Core activity of a data science project. It involves apllying different machine learning techniques.

Examples:
- KNN
- Naive Bayes
- Decision tree
- Linear Regression

Identify the model that fits best with business requirements. Train models and test and after few attempts compare, then select best performing one.

# Visualization
Next part is based on visualizing results of data analysis. Create summary to explain what has been done. Good way is to present reulst using graphs. 
Remember to clearly specifie every important detail. Summary should be short and to the point.

# Deploy and Maintain

Last part of project is to test model before deploying and check if everything is working properly.

After deploying project, generate and use reports and dashboards to get real time analytics.