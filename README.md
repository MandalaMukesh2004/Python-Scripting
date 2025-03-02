# Power BI Project: Python Scripting in Power BI

# Project Overview

* This Power BI project demonstrates the integration of Python scripting within Power BI to perform data manipulation and visualization. The script processes the dataset by removing duplicate rows and visualizing the relationship between Age and Weight using a scatter plot.

# Key Insights

* Data Cleaning: Removed duplicate rows to ensure data integrity.

* Visualization: Created a scatter plot to analyze the correlation between Age and Weight.

* Python Integration: Used Python scripting to extend Power BI's analytical capabilities.

# Features

Python Scripting for data preprocessing and visualization.

Automated Data Cleaning by removing duplicate entries.

Matplotlib Integration to generate a scatter plot.

Power BI & Python Synergy for advanced analytics.

# Dataset Information

* Dataset: Contains demographic information.

* File Format: Power BI (python scripting.pbix)

* Key Columns: Age, Children, Fname, Gender, Pets, State, Weight

# How to Use

Install Power BI Desktop.

Ensure Python is installed with matplotlib and pandas libraries.

Download and open the python scripting.pbix file.

Run the Power BI Python script to generate visualizations.

# Python Script Used
The following code to create a dataframe and remove duplicated rows is always executed and acts as a preamble for your script: 

dataset = pandas.DataFrame(Age, Children, Fname, Gender, Pets, State, Weight)

dataset = dataset.drop_duplicates()

Paste or type your script code here:

import matplotlib.pyplot as plt

dataset.plot(kind = 'scatter',x = 'Age',y = 'Weight',color = 'red')

plt.show()
