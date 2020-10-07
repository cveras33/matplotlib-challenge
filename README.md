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
Two bar charts using identical data were generated. The first bar chart was generated using Pandas `.plot.bar()` function which essentially is using the matplotlib library, just through the pandas function call. The second bar chart was generated using Matplotlib `plt.bar()` function. Below I provided just the Matplotlib bar chart, as both bar charts essentially use the same code to generate the bar chart and are statistically identical. To view the Pandas bar chart, please scroll to the approprite section within Jupter Notebook. 

The bar chart gives a visual representation of the total number of datapoints for each drug regimen. The chart shows that Capomulion, Pymaceutical's drug, had the most datapoints, and Propriva has the least amount of data points. 

![Pyplot Bar Plot](https://github.com/cveras33/matplotlib-challenge/blob/main/Pymaceuticals/plt_bar_plot.png) 

### Pie Charts ### 

Similarly to the bar charts, two pie charts were generated as well. The first pie chart was generated using Pandas `.plot.pie()` function, and the second pie chart was generated using Matplotlib `plt.pie()` function. Below I provided just the Matplotlib pie chart. Since, again, the same code is being used both through Pandas and Matplotlib and both pie charts are statistically identical. To view the Pandas pie chart, please scroll to the approprite section within Jupter Notebook. 

The below pie chart gives a visual representation of the distribution of male versus female mice. The chart shows there were slightly more males in the study than females. 

![Pyplot Pie Plot](https://github.com/cveras33/matplotlib-challenge/blob/main/Pymaceuticals/plt_pie_plot.png)

## Quartiles, Outliers and Boxplots ##

## Line and Scatter Plots ##

### Line Graph ### 

The line graph below was generated using Matplotlib `.plt.plot()`, and shows tumor volume versus time point for a single mouse treated with Capomulin. The particular data shown here is for the mouse s185. 

![Line Plot](https://github.com/cveras33/matplotlib-challenge/blob/main/Pymaceuticals/line_plot.png)

### Scatter Plot ### 

The scatter plot below was generated using Matplotlib `.scatter()`, and shows the average tumor volume versus mouse weight for all mice in the Capomulin regimen. 

![Line Plot](https://github.com/cveras33/matplotlib-challenge/blob/main/Pymaceuticals/scatter_plot.png)

## Correlation and Regression ##

## Observations and Insights ##

### Status ###

Project is: *in progress*
