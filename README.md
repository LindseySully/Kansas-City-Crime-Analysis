# Analyzing Crime Dynamics in Kansas City: A Study on Violent and Non-Violent Offenses Using Machine Learning

## Project Overview
The objective of this project is to leverage the KCPD_5_Year_Analysis data set supplied by the Board of Police Commissioners of Kansas City, Missouri to be open data used by the public within Open Data KC. This data set contains reports surrounding criminal offenses within the Kansas City Metropolitan area. 

## Project Goal
The goal is to leverage machine learning algorithms to break down time series data provided within the data set to understand and predict the likelihood of age groups becoming a victim of a crime and the most common times of year, quarter, month, and day of the week in which individuals within the Kansas City metropolitan region has a more significant likelihood of becoming a victim of a crime and provide a predictive model that can iterate to provide a proactive solution and understanding of the trends that have been occurring over the past five years. 

## Project Prerequisities
1. Git
1. Python 3.7 + (3.11+ Preferred)
1. VS Code Editor
1. VS Code Extension: Python (by Microsoft)
1. dotenv (**May change)
    - Install **dotenv** by `pip install python-dotenv`

## Getting Started 
1. Fork this repo into your GitHub.
1. Clone your repo down to your machine.
1. View/ Command Palette - then Python: Select Interpreter
1. Select your conda environment
1. Install necessary libraries listed below and within the `requirements.txt` file using `pip install -r requirements.txt`

## Project Libraries

- Pandas
- matplotlib.pyplot
- Numpy
- sklearn.model_selection
- sklearn.metrics

## Project Files

- **Crime_Analysis_EDA.ipynb**: this is the file that contains the necessary information for the exploratory data analysis. This will leverage python pyplot, pandas, pandas scatter_matrix to provide the initial data analysis within python. 
- **Crime_Analysis_ML.ipynb**: this is the file that contains the model detail inforamtion and the train/test set information and the comparison of the models. 
