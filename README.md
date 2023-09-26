# Module5 Challenge

Prepare the data

1.  Import the dependencies required for the activity. Setup the path to read the files. Merge the two dataframe "study_results" and "mouse_metadata" with  "Mouse   ID" .

2.   Identify the Duplicate Mice Id  and remove the duplicate value from the dataframe and store the cleaned data in a seperate dataframe.

Generate summary statistics

1. Generate a summary statistics table of mean, median, variance, standard deviation, and SEM of the tumor volume for each regimen using groupby.

2.  Store all the calculated values in the seperate dataframe (df) and display the data.

3. We can also get the exact result in a single line code by aggregation method.

Create bar charts and pie charts  

1. Create a bar chart using pandas and generate abar plot using matplotlib.

2. Generate a pie plot based on the male and female mice using pandas and matplotlib seperately.

Calculate quartiles, find outliers, and create a box plot

1. Create a seperate list "treatment_name" for the Drug regimens - Capomulin, Ramicane, Infubinol, and Ceftamin.  Store the greatest time point for each mouseid and store the data in  max_tumor.

2. Merge this data with the cleaned dataframe  using Mouse Id and Timepoint. 

3. Create a empty list to append the tumor values of the specified drug regimens. 

4. Calculate the lower quartile, upper quartile and interquartile range for the four drug regimen. Identify the lower boundary and upper boundary to calculate the outliers. Display the Interquartile and outliers for the drug regimen.

5.  Generate a box plot that shows the distrubution of the tumor volume for each treatment group. Based on the box plot we can identify infubinol has a outlier.

Create a line plot and a scatter plot

1.  Generate a line plot of tumor volume vs. time point for a single mouse(mouse id - 'l509') treated with Capomulin. Add the labels and title to the graph.

2. Generate a scatter plot of mouse weight vs. the average observed tumor volume for the entire Capomulin regimen. Add the labels to the graph.

Calculate correlation and regression

1. Calculate the correlation coefficient and a linear regression model for mouse weight and average observed tumor volume for the entire Capomulin regimen and plot the linear regression model on top of the previous scatter plot

