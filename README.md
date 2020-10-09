# Matplotlib Homework - The Power of Plots 

This project looks into Pymaceuticals Inc.'s, a pharmaceutical company specializing in anticancer pharmaceuticals, and their most recent efforts to find a potential treatment for squamous cell carcinoma (SCC). With access to their data from the most recent animal study, I analyze, develop insights and draw conclusions based off the data provided. In this study, there were 249 mice identified to have an SCC tumor growth, which were then treated through a variety of drug regimens. Over the course of 45 days, tumor development was observed and measured. The purpose of this study was to compare the performance of Pymaceuticals' drug of interest, Capomulin, versus the other treatment regimens. The following tables and figures will supplement the company's technical report needed for the study, by providing cohesive analysis and observations of the data.

## Table of Contents ##
* [Summary Statistics](#summary-statistics)
* [Bar and Pie Charts](#bar-and-pie-charts)
* [Quartiles, Outliers and Boxplots](#quartiles-outliers-and-boxplots)
* [Line and Scatter Plots](#line-and-scatter-plots)
* [Correlation and Regression](#correlation-and-regression)
* [Observations and Insights](#observations-and-insights)
  
## Summary Statistics ##

## Bar and Pie Charts ##

### Bar Charts ### 
Two bar charts using identical data were generated. The first bar chart was generated using Pandas `plot.bar()` function which essentially is using the matplotlib library, just through the pandas function call. The second bar chart was generated using Matplotlib `plt.bar()` function. Below I provided just the Matplotlib bar chart, as both bar charts essentially use the same code to generate the bar chart and are statistically identical. To view the Pandas bar chart, please scroll to the approprite section within Jupter Notebook. 

The bar chart gives a visual representation of the total number of datapoints for each drug regimen. The chart shows that Capomulion, Pymaceutical's drug, had the most datapoints, and Propriva has the least amount of data points. 

![Pyplot Bar Plot](https://github.com/cveras33/matplotlib-challenge/blob/main/Pymaceuticals/Images/plt_bar_plot.png) 

### Pie Charts ### 

Similarly to the bar charts, two pie charts were generated as well. The first pie chart was generated using Pandas `plot.pie()` function, and the second pie chart was generated using Matplotlib `plt.pie()` function. Below I provided just the Matplotlib pie chart. Since, again, the same code is being used both through Pandas and Matplotlib and both pie charts are statistically identical. To view the Pandas pie chart, please scroll to the approprite section within Jupter Notebook. 

The below pie chart gives a visual representation of the distribution of male versus female mice. The chart shows there were slightly more males in the study than females. 

![Pyplot Pie Plot](https://github.com/cveras33/matplotlib-challenge/blob/main/Pymaceuticals/Images/plt_pie_plot.png)

## Quartiles, Outliers and Boxplots ##

### Boxplot ###

The boxplot below was generated using Matplotlib `plt.boxplot()` function.  

The plot shows the final tumor volume, measured in cubic millimeters, for all mice in each of the four drug regimens of interest (Capomulin, Ramicane, Infubinol, Ceftamin). As shown in the boxplot below, Infubinol and Ceftamin both had greater final tumor volumes, whereas Capomulin and Ramicane had similarly low final tumor volumes. 

![Boxplot](https://github.com/cveras33/matplotlib-challenge/blob/main/Pymaceuticals/Images/plt_box_plot.png)

## Line and Scatter Plots ##

### Line Graph ### 

The line graph below was generated using Matplotlib `plt.plot()`. 

The graph shows tumor volume measured in cubic millimeters versus time point measured in days for a single mouse treated with Capomulin. The spacific data shown in the line graph is for the mouse ID s185. 

![Line Plot](https://github.com/cveras33/matplotlib-challenge/blob/main/Pymaceuticals/Images/line_plot.png)

### Scatter Plot ### 

The scatter plot below was generated using Matplotlib `plt.scatter()`, and shows the average tumor volume in cubic millimeters versus mouse weight in grams for all mice in the Capomulin regimen. 

![Scatter Plot](https://github.com/cveras33/matplotlib-challenge/blob/main/Pymaceuticals/Images/scatter_plot.png)

## Correlation and Regression ##

### Linear Regression ###

The linear regression model below was generated based on the scatter plot for average tumor volume versus mouse weight. The linear regression equation for this model is *y = 0.74x + -10.15*. 

![Linear Regression](https://github.com/cveras33/matplotlib-challenge/blob/main/Pymaceuticals/Images/linear_regression.png)

## Observations and Insights ##

### Status ###

Project is: *in progress*
