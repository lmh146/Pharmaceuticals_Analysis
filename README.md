# Matplotlib_Challenge

## Overview
This project looks at the data provided from a study on the effects different drug regimens had on the size of tumors in mice over time. The program first looks to merge the mouse data with the gathered study data to then pull information. The program works to create visuals focusing on different aspects of the data from the study to examine information about the mice as well as the effectiveness of different drugs.

## Pymaceuticals    
The application works with *pandas* and *Matplotlib* to take the data provided in two csv files and merges them. The resulting table is used to generate a summary statistics table using two different methods. This multi-method usage continues as the program generates multiple visuals including bar and pie graphs based on the merged data set to examine timepoint sums for each drug and the male to female ratio of the mice. It then focuses on four drug regimens to locate any outliers within the data and plot in a box plot. The project closes with a focus on a single drug regimen, using scatter plots to calculate the correlation coefficient and linear regression. It should be noted that within the data one mouse had to be removed following the merging process because some information was duplicated and we do not have the means to determine the original.  

## Analysis
Considering the information this project provides, there is a strong positive correlation between the mice's weight and the tumor size that is shown as the correlation coefficient was 0.84. While this indicates there is correlation, it is essential to be cautious as it does necessarily tell about causation and therefore other factors could be influencing the tumor size in mice population. Though, it can be concluded that this correlation is not related to gender as we can see from the gender pie graph that the distribution within the mouse population of male to female is almost half and half. It can also be said that the average final tumor size was smaller in the mice taking Capomulin and Ramicane than those taking Infubinol and Ceftamin, which could infer that Capomulin and Ramicane have a greater effectiveness in decreasing tumor volume.


