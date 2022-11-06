# Automatic Ticket Classification

## Problem statement

For a financial company, customer complaints carry a lot of importance, as they are often an indicator of the shortcomings in their products and services. If these complaints are resolved efficiently in time, they can bring down customer dissatisfaction to a minimum and retain them with stronger loyalty. This also gives them an idea of how to continuously improve their services to attract more customers. 

These customer complaints are unstructured text data; so, traditionally, companies need to allocate the task of evaluating and assigning each ticket to the relevant department to multiple support employees. This becomes tedious as the company grows and has a large customer base.

In this case study, We will be working as an NLP engineer for a financial company that wants to automate its customer support tickets system. As a financial company, the firm has many products and services such as credit cards, banking and mortgages/loans. 

## Business goal

Goal is to build a model that is able to classify customer complaints based on the products/services. By doing so, we can segregate these tickets into their relevant categories and, therefore, help in the quick resolution of the issue.

With the help of non-negative matrix factorization (NMF), an approach under topic modelling, We will detect patterns and recurring words present in each ticket. This can be then used to understand the important features for each cluster of categories. By segregating the clusters, We will be able to identify the topics of the customer complaints. 

We do topic modelling on the .json data provided by the company. Since this data is not labelled, we need to apply NMF to analyse patterns and classify tickets into the following five clusters based on their products/services:

    Credit card / Prepaid card

    Bank account services

    Theft/Dispute reporting

    Mortgages/loans

    Others 

With the help of topic modelling, we will be able to map each ticket onto its respective department/category. We can then use this data to train any supervised model such as logistic regression, decision tree or random forest. Using this trained model, We can classify any new customer complaint support ticket into its relevant department.

## Dataset
Downloaded the data set from here . 
https://drive.google.com/file/d/1Y4Yzh1uTLIBLnJq1_QvoosFx9giiR1_K/view?usp=sharing

The data set given to We is in the .json format and contains 78,313 customer complaints with 22 features. We need to convert this to a dataframe in order to process the given complaints.

## Tasks performed

We need to perform the following eight major tasks to complete the assignment:

    Data loading

    Text preprocessing

    Exploratory data analysis (EDA)

    Feature extraction

    Topic modelling 

    Model building using supervised learning

    Model training and evaluation

    Model inference

Note: Once We have finalised the clusters/categories for customer complaints, the next step is to create a data set that contains the complaints and labels (which We found using NMF). This labelled data set will be used for model building using supervised learning. 

We need to try at least any three models from logistic regression, naive Bayes, decision tree and random forest. 

We need to select the model that performs the best according to the evaluation metrics.
