# Predicting Mortgage Approvals
## Capstone project for my Microsoft Professional Program in Data Science 
[Link to my blog post](https://medium.com/analytics-vidhya/predicting-mortgage-approvals-data-analysis-and-prediction-with-azure-ml-studio-part-1-8629d2f938a8
)

This repository contains many of the notebooks developed to analyze a dataset of mortgage approvals. This exercise is the capstone project in the Microsoft Professional Program in Data Science and the report included is the result of this analysis. Then as part of the capstone I developed a machine learning model to classify when a mortgage application would be accepted or not by the loan company. The ml model was developed using the Microsoft tool, Azure Machine Learning Studio.

I have all included some Jupyter notebooks used to built some basic classfication model based in decision trees. But they are not intended to be the best classifier, they are just some simple excercises in building a classifier using the Sci-Kit Learn lybrary on Python.

Some of the notebooks are under construction and maybe some new model will be included in the future.

### Content
- [Predicting_Mortgage_Approvals_EDA](https://github.com/edumunozsala/Predicting_Mortgage_Approvals/blob/master/Predicting_Mortgage_Approvals_EDA.ipynb)
    Code and visualization in Python to develop a Exporatory Data Analysis of the problem and data. 
- [PDF Report with detailed explanations](https://github.com/edumunozsala/Predicting_Mortgage_Approvals/blob/master/Report%20Challenge%203.pdf)
- [Logistic Regression Classifier with SKlearn](https://github.com/edumunozsala/Predicting_Mortgage_Approvals/blob/master/Capstone%20MS%20in%20DS%20Logistic%20Regression.ipynb)
    Jupyter notebook with a simple logistic regression classifier to show how to deal with this dataset 
- [Decision Tree Classifier with SKlearn](https://github.com/edumunozsala/Predicting_Mortgage_Approvals/blob/master/Capstone%20MS%20in%20DS%20Decision%20Tree.ipynb)
    Jupyter notebook with a Decision Tree classifier to show how to deal with this dataset
- [Gradient Boosted Classifier with SKlearn](https://github.com/edumunozsala/Predicting_Mortgage_Approvals/blob/master/Capstone%20MS%20in%20DS%20Gradient%20Boosted%20Decision%20Tree.ipynb)
    Similar to the previous notebook but using a Gradient Boosted classifier
- [AdaBoost Classifier with SKlearn](https://github.com/edumunozsala/Predicting_Mortgage_Approvals/blob/master/Capstone%20MS%20in%20DS%20Boosted%20Decision%20Tree.ipynb])
    An example of applying a AdaBoost classifier

## Problem and data description
Predicting if a mortgage application will either be accepted or denied within the USA will be very useful. This report describes the process taken to do exactly that, and notably the prediction is accomplished without industry standard features such as credit score, debt to income ratio, and loan to value ratio. The datasets provided for this project were adapted from the Federal Financial Institutions Examination Council, or better known as the FFIEC. The training dataset included 500,000 observations across 23 features, with a unique row identifier, and a known acceptance outcome. This data was used to train a binary classification model using Supervised Machine Learning (SML). A second dataset with 500,000 additional observations, lacking a known acceptance outcome, was then utilized to ‘test’ the model by creating predictions of the acceptance outcome.

A full description can be found in the [Exploratory Data Analysis described in this post](https://medium.com/analytics-vidhya/predicting-mortgage-approvals-data-analysis-and-prediction-with-azure-ml-studio-part-1-8629d2f938a8).

## Machine learning model built in Azure Machine Learning Studio
From Microsoft Doc:

*Microsoft Azure Machine Learning Studio (classic) is a collaborative, drag-and-drop tool you can use to build, test, and deploy predictive analytics solutions on your data. Azure Machine Learning Studio (classic) publishes models as web services that can easily be consumed by custom apps or BI tools such as Excel.

Machine Learning Studio (classic) is where data science, predictive analytics, cloud resources, and your data meet.*

In the second part of the capstone I built a predictive model on Azure ML Studio to predict when an mortgage approval would be accepted or not, [here is the link for a description](https://medium.com/analytics-vidhya/predicting-mortgage-approvals-data-analysis-and-prediction-with-azure-ml-studio-part-2-2c190e83c9f4)

#### Important: This repository is still under construction and new files may be included in the coming weeks

## License
This repository is under the GNU General Public License v3.0