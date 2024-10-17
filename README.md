# Pymaceuticals Inc.
In this study, mice identified with SCC tumor growth were treated with a variety of drug regimens. Over the course of 45 days, tumor development was observed and measured. The purpose of this study was to compare the performance of Pymaceuticals' drug of interest, Capomulin, versus the other treatment regimens.

Initial data had beed clean to remove duplicates after merging two data sets using Pandas DataFrame.Duplicated.

Summary Statistics of the tumor volume for each regimen was calculated.
![image](https://github.com/user-attachments/assets/c627d553-6182-47e8-ade0-18141bebda35)

Bar Charts to show the number of mice for each drug regimen were added, using both Pandas and Matplotlib.
![image](https://github.com/user-attachments/assets/5fc9fe97-268f-4b1c-b97c-f98886b54c2e)

Pie Charts to show the distribution of male/female mice in the study were added, using both Pandas and Matplotlib.
![image](https://github.com/user-attachments/assets/1afb624f-2681-44f9-9ff7-d37671aa9cec)

Boxplot to compare distribution of tumor volume by four drug regimen and spot outliers was added.
![image](https://github.com/user-attachments/assets/f69c8b53-b2e3-435c-b6e2-5a061803f42d)

Line plot generated to analyze progression of tumor for a specific mouse.
![image](https://github.com/user-attachments/assets/d8c21358-6827-4550-97b4-f8e739a20c47)

Scatter Chart generated to see if there is a correlation btw mouse weigh and average tumor volume.
![image](https://github.com/user-attachments/assets/f17a0e2b-4d9b-4dd9-b496-f987803e57ce)

Correlation and Linear regression model between mouse weigh and average tumor volume was calculated and visualized via Scatter and Line Plots.
![image](https://github.com/user-attachments/assets/1981850f-b9b2-4607-8cab-732dde6449b9)

Analysis
According to Summary statistics, Ramicane and Capomuline drug regimens are the most efficient as they have:
the minimum average tumor volume among other regimens: Ramicane: 40.216745, Capomuline: 40.675741
the minimum standart deviation: Ramicane: 4.846308; Capomuline: 4.994774
Bar Chart also shows that for Ramicane and Capomuline drug regimens the total number of mice tested were significant (over 200 mice), which makes summary statistics more reliable
Line plot of tumor volume vs. time point for a mouse treated with Capomulin shows that Capomulin is effective drug as the tumor volume is reducing with time (Tested on different mice)
