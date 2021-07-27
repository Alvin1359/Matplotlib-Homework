# Matplotlib - Mice Cancer Treatments
This challenge involves analysing a dataset on an animal study  
An animal study was conducted to measure the effects of some anti-cancer drugs on tumor sizes in mice  
 
Required: Generate all tables and figures needed for a technical report of the study and list three observations from the data  
  
_pymaceuticals.ipynb_ contains the main analysis and observations  
The folder _data_ contains the study results used in the analysis
# Tasks completed
- Merging the two dataset results into one DataFrame, checking for and removing any duplicate results
- Generate a summary table showing:
  - Mean
  - Median
  - Variance
  - Standard Deviation
  - Standard Error Measurement (SEM)
- Generating a bar plot of the total mice treated by each regimen using
  - Panda's _DataFrame.plot()_
  - Matplotlib's _pyplot_
- Generating a pie plot showing the distribution of female or male mice in the study using
  - Panda's _DataFrame.plot()_
  - Matplotlib's _pyplot_
- Finding the final tumor volume of each mouse across four treatment regimens and calculating
  - Quartiles
  - IQR
  - Any Outliers
  - Generating a box and whisker plot of these results and highlighting any outliers using Matplotlib
- For mice treated with Capomulin 
  - Generating a line plot of tumor volume vs. timepoint for a single mouse
  - Generating a scatter plot showing the relationship between mouse weight and average tumor volume for the Capomulin treatment
  - Calculating correlation coefficient and linear regression model for the scatterplot
