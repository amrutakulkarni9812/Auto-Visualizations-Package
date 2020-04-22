# Auto-Visualizations-Package
Build and upload a package to PyPi
This package is built on top of Python matplotlib library to create various visualizations for a given dataframe.

## Instructions:
You need to pass: data file name, plot type, id variable name and metric/ output variable name to the plot_data function.
The code separates quantitative variables and categorical variables, drops the id variable since it is not useful for data analysis
and plots the type of chart you need with appropriate type of variables.

## Installation
You need to have following python libraries in order to execute the code using visualization package
1. pandas
2. numpy 
3. matplotlib
4. sys
5. itertools

## Files:
1. Generalvisualization.py
    This file contains Generic visualization class for commonly used visualization techniques, functions to read the data file, 
    separate data types and plot the charts based on use inputs.
2. Histogramvisualization.py
    This file contains the Histogram class and function to plot it for all quantitative variables.
3. Barchartvisualization.py
    This file contains Barchart class and functions to plot barchart for all categorical variables and stacked bar charts for categorical variable combinations.
4. Bubblechartvisualization.py
    This file contains Bubble chart class and function to plot correlation between two or more quantitative variables.
5. Piechartvisualization.py
    This file contains Pie chart class and function to plot distribution of one variable across categories of another variable.
6. Execution_code.py
    This file contains test code to execute after installing the package.
7. test_data.csv
	This file contains dummy data.
  
## Acknowledgement
Thanks to Udacity Data Scientist Nanodegree content creators for providing us the opportunity to work on this project.
