# Pharmas_project

We went through the exercise by a few steps-data processing; generating summary statistics; generating bar charts, pie charts using different methods; calulating quartile, find outliers and created a box plot. Last but not least we calculated correlation coefficient and linear regression model and generated scatter plot and linear regression line.

1) Data processing:
   We begin by merging meta data and study result datasets. We found one mouse ID had duplicate records. based on mouse ID and timepoint. We then dropped all the records pertaining to this particular mouse ID to legitamize the data we use.
3) Generate Summary Statistics:
   We calculated the mean, media, variance, standard deviation and SEM by using groupby drug regimen and agg function and created a new data frame to hold the results.
4) We used two different methods to generate bar charts which showed the number of timepoints over each drug regimen. Based on the visuals, Capomulin and Ramicane are close in the number of timepoints. We also generated a pie charts showing sex distribution of the tested mice, which showed a roughly equal ratio.
5) We created a box plots for the 4 main regimens-Capomulin, Ramicane, Infubinol, and Ceftamin, after creating a dataframe with the last timepoint tumor volume results, then calculated Quartiles, Find Outliers, and Created a Box Plot to show the distribution of the final tumor volume for all the mice in each treatment group.
6) We then created a Line Plot that shows the tumor volume vs. time point for one mouse treated with Capomulin and a Scatter Plot showing average tumor volume vs. mouse weight for the Capomulin regimen. We calculated correlation and regression to see the relationship between mouse weight and tumor size at the last timepoint.

# Conclusions:
1) Distribution of the final tumor volume seems close between Capomulin and Ramicane. Maybe worth further examine both drug regimens.
2) We can see from the result of the correlation of 0.84 that there is a fairly strong correlation between weight and tumor size. The bigger the weight, the larger the tumor size.

# Limitations of the analysis:
1) There was no analysis on the effect of each drug between the beginning and ending timepoints. Any drug regimen effectively controlled or shrank the tumor size? 
2) Was any drug regimen more effective on mice in a specified weight range. For example, one can be more effective on an overweight mouse only. 
 