# Pharmaceuticals_Analysis

## Overview
This project looks at the data provided from a study on the effects different drug regimens had on the size of tumors in mice over time. The program first looks to merge the mouse data with the gathered study data to then pull information. The program works to create visuals focusing on different aspects of the data from the study to examine information about the mice as well as the effectiveness of different drugs.

## Pymaceuticals    
The application works with *pandas* and *Matplotlib* to take the data provided in two csv files and merges them. The resulting table is used to generate a summary statistics table using two different methods. This multi-method usage continues as the program generates multiple visuals including bar and pie graphs based on the merged data set to examine timepoint sums for each drug and the male to female ratio of the mice. It then focuses on four drug regimens to locate any outliers within the data and plot in a box plot. The project closes with a focus on a single drug regimen, using scatter plots to calculate the correlation coefficient and linear regression. It should be noted that within the data one mouse had to be removed following the merging process because some information was duplicated and we do not have the means to determine the original.  

## Analysis
Considering the information this project provides, there is a strong positive correlation between the mice's weight and the tumor size that is shown as the correlation coefficient was 0.84 as seen in the first graph below. While this indicates there is correlation, it is essential to be cautious as it does necessarily tell about causation and therefore other factors could be influencing the tumor size in mice population. Though, it can be concluded that this correlation is not related to gender as we can see from the gender pie graph (the second graph below) that the distribution within the mouse population of male to female is almost half and half. It can also be said, based on the third graph below, that the average final tumor size was smaller in the mice taking Capomulin and Ramicane than those taking Infubinol and Ceftamin, which could infer that Capomulin and Ramicane have a greater effectiveness in decreasing tumor volume.

![image](https://user-images.githubusercontent.com/88953017/147602683-1d5bffcb-1afb-4178-b2e8-4d8429308ec1.png)

![image](https://user-images.githubusercontent.com/88953017/147602537-2f0e8d21-b821-4b2b-885f-ac60055a72de.png)

![image](https://user-images.githubusercontent.com/88953017/147602916-5270030f-2705-4690-b48f-5fd3c1f67a42.png)
