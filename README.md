# Appusersegmentation
# overview
This repository contains codes for user data in an app to analyze the segments for better data management and for marketing strategies.This project used K-means cluster in jupyter notebook for determining its data analysis.
# Prerequisties
1. pip
2. python
3. Jupyter Notebook
# Libraries
1. pandas
2. matplotlib
3. sklearn
# Setup instructions
1. Load the dataset using Pandas.
2. Perform exploratory data analysis to understand user behavior.
3. Apply K-means clustering for user segmentation.
4. Visualize results using Plotly to understand user segments.
# Given data
The dataset (userbehaviour.csv) contains user-level data including:
1. Average Screen Time
2. Average Spending on App (INR)
3. Review Left (Yes/No)
4. User Ratings
5. Password Reset Requests
6. Last Visited Time
7. User Status (Installed/Uninstalled)
# Processing technique
1. load the dataset and handling any missing values and check the information of column and its descriptive statatics
2. Data is read and visualized to understand basic statistics like average, highest, and lowest screen time and spendings.
3. Check the relationships between different data
4. Apply k-mean cluster on data to visualize different segments
