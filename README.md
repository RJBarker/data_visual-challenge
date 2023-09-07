# Data_Visual-Challenge

## Pymaceuticals Inc.

### Description  

Using the data files "Mouse_metadata.csv" and "Study_results.csv", merge together into one DataFrame and display summary statistics and bar, pie, box and scatter plots using the Matplotlib libary.

This assignment was broken down into sections, with tasks assined to be completed:

### Preparing the Data  

Using the data sets provided:

  - Import the data
  - Merge into a single DataFrame
  - Display the original unique Mouse ID count
  - Remove any Mouse ID's with duplicate Timepoint entry's into a new "clean" DataFrame
  - Re-display unique Mouse ID count with duplicates removed

### Generate Summary Statistics

Create a Summary Statistics DataFrame which:

  - Contains each Drug Regimen as the index and on a seperate row
  - Contains five statistics generated on each Drug Regimen's Tumor Volume
     - Mean
     - Median
     - Variance
     - Standard Dev.
     - Standard Err. Mean

### Create Bar Charts and Pie Charts

Create two identical Bar Charts which show:

  - The total number of rows for Mouse ID/Timepoint by Drug Regimen
      - First Bar Chart must be created through Pandas DataFrame
      - Second Bar Chart must be created by Matplotlib's pyplot

Create two identical Pie Charts which show:

  - The distribution of female vs male mice
      - First Pie Chart must be created through Pandas DataFrame
      - Second Pie Chart must be created by Matplotlib's pyplot

### Calculate Quartiles, Find Outliers, and Create a Box Plot

On the 4 most effective Drug Regimens: Capomulin, Ramicane, Infubinol, and Ceftamin:

  - Create a grouped DataFrame that shows the last (greatest) time point for each mouse
  - Merge this grouped DataFrame with the original cleaned DataFrame
  - Create a list that holds the treatment names as well as a second, empty list to hold the tumor volume data
  - Loop through each drug in the treatment list, locating the rows in the merged DataFrame that correspond to each treatment
  - Append the resulting final tumor volumes for each drug to the empty list
  - Determine outliers by using the upper and lower bounds, and then print the results
  - Using Matplotlib
     - Generate a box plot that shows the distribution of the final tumor volume for all the mice in each treatment group
     - Highlight any potential outliers in the plot by changing their color and style

### Create a Line Plot and a Scatter Plot

Select a single mouse that was treated with Capomulin:
  
  - Generate a line plot of tumor volume versus time point for that mouse

Using only the data on mice treated with the Capomulin regimen:

  - Generate a scatter plot of mouse weight versus average observed tumor volume

### Calculate Correlation and Regression

With the data used to create the previous scatter plot:

  - Calculate the correlation coefficient and linear regression model between mouse weight and average observed tumor volume
  - Plot the linear regression model on top of the previous scatter plot

### Analysis

Finally, provide a top-level summary of the study results


## References














