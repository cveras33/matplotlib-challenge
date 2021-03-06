# Matplotlib Homework - The Power of Plots 

This project looks into Pymaceuticals Inc., a pharmaceutical company specializing in anticancer pharmaceuticals, and their most recent efforts to find a potential treatment for squamous cell carcinoma (SCC). With access to their data from the most recent animal study, I analyze, develop insights and draw conclusions based off the data provided. In this study, there were 249 mice identified to have an SCC tumor growth, which were then treated through a variety of drug regimens. Over the course of 45 days, tumor development was observed and measured. The purpose of this study was to compare the performance of Pymaceuticals' drug of interest, Capomulin, versus the other treatment regimens. The following tables and figures will supplement the company's technical report needed for the study, by providing cohesive analysis and observations of the data.

## Table of Contents ##
* [Summary Statistics](#summary-statistics)
* [Bar and Pie Charts](#bar-and-pie-charts)
* [Quartiles, Outliers and Boxplots](#quartiles-outliers-and-boxplots)
* [Line and Scatter Plots](#line-and-scatter-plots)
* [Correlation and Regression](#correlation-and-regression)
* [Observations and Insights](#observations-and-insights)
  
## Summary Statistics ##

The Summary Statistics dataframe contains the name of each of the drug regimens and all their summary statistics. The summary statistics include: 
* Mean `mean()`
* Median `median()`
* Variance `var()`
* Standard Deviation `std()`
* SEM `sem()`

The table was composed by doing a `groupby(["Drug Regimen])` on the merged dataframe, which was derived from two seprate csv files. The summary statistics were then performed on the data for each drug regimen seprately using the functions listed next to the respective summary statistics in the above bulleted list. To view the dataframe, click below. 

<details>
  <summary>Click to view Summary Statistics dataframe</summary>
  ![Summary Statistics](https://github.com/cveras33/matplotlib-challenge/blob/main/Pymaceuticals/Images/summary_statistics.png) 
</details>

## Bar and Pie Charts ##

### Bar Charts ### 
Two bar charts using identical data were generated. The first bar chart was generated using Pandas `plot.bar()` function which essentially is using the matplotlib library, just through the pandas function call. The second bar chart was generated using Matplotlib `plt.bar()` function. Below I provided just the Matplotlib bar chart, as both bar charts provide the same data. To view the Pandas bar chart, please scroll to the approprite section within Jupter Notebook. 

The bar chart gives a visual representation of the total number of datapoints for each drug regimen. The chart shows that Capomulion, Pymaceutical's drug, had the most datapoints, and Propriva has the least amount of datapoints. 

![Pyplot Bar Plot](https://github.com/cveras33/matplotlib-challenge/blob/main/Pymaceuticals/Images/plt_bar_plot.png) 

### Pie Charts ### 

Similarly to the bar charts, two pie charts were generated as well. The first pie chart was generated using Pandas `plot.pie()` function, and the second pie chart was generated using Matplotlib `plt.pie()` function. Below I provided just the Matplotlib pie chart for the same reasoning as above. To view the Pandas pie chart, please scroll to the approprite section within Jupyter Notebook. 

The below pie chart gives a visual representation of the distribution of male versus female mice. The chart shows there were slightly larger percentage of males in the study than females. 

![Pyplot Pie Plot](https://github.com/cveras33/matplotlib-challenge/blob/main/Pymaceuticals/Images/plt_pie_plot.png)

## Quartiles, Outliers and Boxplots ##

### Boxplot ###

The boxplot below was generated using Matplotlib `plt.boxplot()` function.  

The plot shows the final tumor volume measured in cubic millimeters, for all mice in each of the four drug regimens of interest (Capomulin, Ramicane, Infubinol, Ceftamin). Based on the data provided, and the plot created indicates Infubinol and Ceftamin both had greater final tumor volumes than Capomulin and Ramicane.

![Boxplot](https://github.com/cveras33/matplotlib-challenge/blob/main/Pymaceuticals/Images/plt_box_plot.png)

## Line and Scatter Plots ##

### Line Graph ### 

The line graph below was generated using Matplotlib `plt.plot()`. 

The graph shows tumor volume measured in cubic millimeters versus time point measured in days for a single mouse treated with Capomulin. The spacific data shown in the line graph is for the mouse ID s185. Based on the graph, it can be concluded that the Capomulin drug had a positive effect on the tumor growth of the mouse, causing it to shrink over the 45 day study period. 

![Line Plot](https://github.com/cveras33/matplotlib-challenge/blob/main/Pymaceuticals/Images/line_plot.png)

### Scatter Plot ### 

The scatter plot below was generated using Matplotlib `plt.scatter()`.

The plot shows the average tumor volume in cubic millimeters versus mouse weight in grams for all mice in the Capomulin regimen. Drawing from the graph alone, it can be said that mouse weight and tumor volume are in someway proportional to one another, since in more cases than not, the greater the weight of the mouse, the greater the volume of the tumor is as well. 

![Scatter Plot](https://github.com/cveras33/matplotlib-challenge/blob/main/Pymaceuticals/Images/scatter_plot.png)

## Correlation and Regression ##

### Linear Regression ###

The linear regression model below was generated based on the scatter plot for average tumor volume versus mouse weight. The linear regression equation for this model is *y = 0.95x + 21.55*. The correlation coefficient for mouse weight versus average tumor volume is **84**. 

![Linear Regression](https://github.com/cveras33/matplotlib-challenge/blob/main/Pymaceuticals/Images/linear_regression.png)
 
## Observations and Insights ##
* Looking at the box plot of tumor volume in the Capomulin, Ramicane, Infubinol and Ceftamin drug regimens, Capomulin and Ramicane were both able to decrease tumor volumes to a lesser volume than Infubinol or Ceftamin.
* Based off the line graph created for a single mouse in the Capomulin drug regimen, it can be said that for this specific mouse, the Capomulin drug had a positive effect on tumor growth in the mouse. The graph shows that over the 45-day study period, the volume of the tumor generally decreased, with only one instance of the tumor having a greater volume at a later timepoint than the last. 
* The scatter plot shows us that, at least for the mice within the Capomulin regimen, average tumor volume is somewhat proportional to weight. 

### Status ###

Project is: *complete*

#### Contact 
Chloe Veras  
chloemveras@gmail.com  
[LinkedIn](https://www.linkedin.com/in/chloeveras/)
