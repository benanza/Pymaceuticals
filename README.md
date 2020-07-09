# Pymaceuticals

### Python Jupyter Notebook that analyzes lab results of pharmaceutical drugs used on mice for tumor reduction.

The situation: As a senior data analyst at your research facility, you've been given access to the complete data from their most recent animal study. In this study, 250 mice identified with SCC tumor growth were treated through a variety of drug regimens. Over the course of 45 days, tumor development was observed and measured. The purpose of this study was to compare the performance of Pymaceuticals' drug of interest, Capomulin, versus the other treatment regimens. You have been tasked by the executive team to generate all of the tables and figures needed for the technical report of the study. The executive team also has asked for a top-level summary of the study results.

Using MatPlotLib and Pandas Python libraries in a Jupyter notebook, the following is generated:

A summary statistics table consisting of the mean, median, variance, standard deviation, and SEM of the tumor volume for each drug regimen.

A bar plot using both Pandas's DataFrame.plot() and Matplotlib's pyplot that shows the number of data points for each treatment regimen.

A pie plot using both Pandas's DataFrame.plot() and Matplotlib's pyplot that shows the distribution of female or male mice in the study.

Calculation of the final tumor volume of each mouse across four of the most promising treatment regimens (Capomulin, Ramicane, Infubinol, and Ceftamin), the quartiles, IQR and potential outliers across all four treatment regimens.

A box and whisker plot of the final tumor volume for all four treatment regimens and highlight any potential outliers in the plot by changing their color and style.

A line plot of time point versus tumor volume for a single mouse treated with Capomulin.

A scatter plot of mouse weight versus average tumor volume for the Capomulin treatment regimen.

Calculation of the correlation coefficient and linear regression model between mouse weight and average tumor volume for the Capomulin treatment. Plotted the linear regression model on top of the previous scatter plot.

Observations or inferences that can made from the data included at the top of the notebook.
