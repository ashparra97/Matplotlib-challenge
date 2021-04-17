# Matplotlib-challenge

###### Disclosure: This assignment was done in collaboration with Jason Wang. 

## Summary 

This assignment analyzed two sets of data on various cancer treatments given to mice. The two datasets (csv files) were combined into a singular dataframe that was then used for the analyses in this code.

## Process

These analyses in this assignment utilize three dependencies: pandas, matplotlib.pyplot, and scipy.stats. 

After combining the two datasets into one dataframe, the total number of unique mice was found, and mouse g989 was dropped from the dataset. 

A summary statistical summary was created by calculating the the means, median, variance, standard deviation, and SEM of tumor volume by regimen using the groupby function.

Bar plots and pieplots were created using both pandas and thenpyplot. The bar plots measured the number of regimen adminstrations per regimen, and the pie plots showed the distribution of gender of the mice.

The final tumor volume of each mouse was found, and then only mice that were treated with Capomulin, Ramicane, Infubinol, and Ceftamin were kept.

The IQR and outliers were determined for each regimen by using a for loop. A box plot was created for each regimen. 

A line plot was created for a random mouse highlighting the tumor volume at each timepoint.

Lastly, a scatterplot showing the average tumor volume and mouse weight was created, and the correlation coefficient and linear regression model were found.
 
