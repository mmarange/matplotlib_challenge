# Matplotlib Case Assignment - The Power of Plots

## Background

Pymaceuticals specializes in anti-cancer pharmaceuticals. In its most recent efforts, it began screening for potential treatments for squamous cell carcinoma (SCC), a commonly occurring form of skin cancer.

In this study, 249 mice identified with SCC tumor growth were treated through a variety of drug regimens. Over the course of 45 days, tumor development was observed and measured. The purpose of this study was to compare the performance of Pymaceuticals' drug of interest, Capomulin, versus the other treatment regimens.

Contained in here is an analysis of the results from the regimen used and a brief interpretation of the analysis. 

# Summary of Analysis
* One mouse with ID was removed from the analysis because of duplicates at Timepoint yet different  Tumor Volume recorded at the same timepoint hence making the result unrealiable.
* Capomulin and Ramicane had the highest number of mice tested 
* There are more male mice than female mice in the test at 51% male and 49% female
* Tests for Capomulin, Ramicane, and Ceftamin are consitent because their results are devoid of any potential outliers, whereas Infubinol only has one potential outlier.
* From the statistical table Ramicane was the best regimen followed by Capomulin because they had the lowest tumor volume at the end of the tests respectively. In addition, results from Ramicane and Capomulin had the lowest standard deviations respectively which means that the results show drug precision and consistancy. 

## Results

* A total of 249 mice were tested, however only 248 mice results were analyzed. 

* Mouse with ID g989 was disregarded

### Fig 1: Figure showing the mouse with duplicate records
![Duplicate](https://github.com/mmarange/matplotlib_challenge/blob/main/01-Case-Assignment/Images/Duplicated%20Mouse.PNG)

### Fig 2: Figure showing statistical summary accross drug regimen
![Stats2](https://github.com/mmarange/matplotlib_challenge/blob/main/01-Case-Assignment/Images/Statistical%20Results2.PNG)

### Fig 3: Figure showing the bar chart of total number of mice tested on each drug regimen
![BarChart](https://github.com/mmarange/matplotlib_challenge/blob/main/01-Case-Assignment/Images/BarChart%20Mice%20tested%20on%20regimen.PNG)

### Fig 4: Figure showing the pie chart of gender distribution of mice tested
![piechart](https://github.com/mmarange/matplotlib_challenge/blob/main/01-Case-Assignment/Images/Female_male%20pie%20chart.PNG)

### Fig 5: Figure showing potential outliers of drug regimen results
![outliers](https://github.com/mmarange/matplotlib_challenge/blob/main/01-Case-Assignment/Images/Outliers%20summary.PNG)

### Fig 6: Figure showing the box plots of four regimen to show the IQR and potential outliers
![Boxplot](https://github.com/mmarange/matplotlib_challenge/blob/main/01-Case-Assignment/Images/Boxplot.PNG)

### Fig 7: Figure showing mouse I509 tumor volume vs timepoint on Capomulin
![lineplot](https://github.com/mmarange/matplotlib_challenge/blob/main/01-Case-Assignment/Images/Plot%20on%20mouse%20I509.PNG)

### Fig 8: Figure showing the mouse average weight vs tumor volume and the regression model
![Scatter](https://github.com/mmarange/matplotlib_challenge/blob/main/01-Case-Assignment/Images/Scatter%20plot.PNG)


![Laboratory](Images/Laboratory.jpg)
### Copyright

Trilogy Education Services © 2020. All Rights Reserved.
