# Project Topic: MTN Customer Churn

MTN Customer Churn Data Wrangling and Retrieval

This repository contains a Jupyter Notebook project focused on data wrangling, retrieval, exploratory data analysis (EDA), and insights generation related to customer churn incidents at MTN, a mobile telecom network in Nigeria.  The notebook titled (MTN Customer Churn Project) presents the workflow and findings in a structured, reproducible manner.
# Project Overview
This project aims to analyze customer churn patterns for MTN Nigeria, one of the leading telecommunications providers in the country. By leveraging a dataset containing demographic, usage, satisfaction, and Customer Tenure in Months details of MTN customers, I explore the factors that influence churn decisions.

#This project is a Final project for module 1 : Data Wrangling & Retrieval, aimed at building foundational skills in working with messy real-world data using Python and pandas.
Files Included
MTN Customer Churn Project.ipynb: The main notebook containing the data wrangling, retrieval and EDA.
README.md: Project documentation and summary.
mtn_customer_churn.csv: The original dataset.
List of Nigeria state by population(2).xlsx
Technologies Used
Python 3.x
Jupyter Notebook
pandas
numpy
matplotlib
Seaborn


Key Features
Data Cleaning: Handling of null values, inconsistent formatting, and irrelevant columns.
Feature Engineering: Creation of clean and consistent columns such as Federal Capital Territory to Abuja (FCT) and merging of another column from another dataset. Exploratory Data Analysis (EDA): Visualizations highlighting patterns in average customer satisfaction rate, average shorter tenure and average data usage.
Insights:
Customers with lower satisfaction rates
Shorter tenures
Lower data usage are more likely to churn from MTN Nigeria.


Sample Visualizations
Bar chart average satisfaction rate  by churn status
Bar chart average tenure  by churn status
Bar chart average data usage  by churn status




 I’ll start by testing the hypothesis with exploratory data analysis (EDA). We'll look into how satisfaction rate, tenure, and data usage relate to churn status. And even check for the percentage of customers in each state.
Here’s what I’ll do:
Compare average satisfaction rate for churned vs. non-churned customers.


Compare average tenure for churned vs. non-churned customers.


Compare average data usage for churned vs. non-churned customers.


Visualize distributions to make trends easier to interpret.







Key Insights:
Surprisingly, churned customers had slightly higher satisfaction, longer tenure, and higher data usage on average.


This contradicts the initial hypothesis.

Presentation for this project link: https://docs.google.com/presentation/d/1Mti7lTVIjWX4x2MSKRNazBXOI9tl8i2-nt0WBXVo0wU/edit?slide=id.g350a4cb0044_0_73#slide=id.g350a4cb0044_0_73


🔁 Updated Hypothesis:
Perhaps other factors like subscription plan, price, or competition are stronger drivers of churn than dissatisfaction or low usage.
Would you like to dig deeper (e.g., by examining the “Reasons for Churn” or modeling churn with machine learning)? ​.
