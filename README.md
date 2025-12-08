# Coffee-Quality-Analysis-SAS-PROC-
Analisys on coffee quality dataset using SAS.

This is a repository analyzing a coffee quality dataset, here you can find basic functions and the process of analysis using SAS PROC with SQL and SAS Functions,

Dataset
The dataset used is an open source from Kaggle, I will share the link to the original dataset, but I will attach also a dataset pre-clean to the repository locatged in the data folder.

Variables of Interest
Total_Cup_Points, This is the target variable (overall quality score).
Aroma, Flavor, Acidity, Body, Balance, Sweetness, are the individual values of score quality metrics.
Country_of_Origin, Variety, Processing_Method, are the Categorical variables.

About the environment, you can run it in SAS Studio, SAS Enterprise Guide, just need to upload the file to the environment.

Script:
The purpose of having one induvial script and the sequential executions is to demonstrates the capabilities of PROC functions across the entire data science pipeline.

The script demonstrates these functions (all following a logical sequence):

    1. PROC PRINT.

    2. PROC SORT.
	
    3: PROC MEANS and PROC UNIVARIATE.

    4: PROC FREQ.

    5: PROC REPORT (PROC TABULATE is also present in this section).

    6: PROC REG (statistical modeling).

    7: PROC EXPORT and PROC COPY for data management.

    8: PROC SQL querying and aggregation.


Insights:
- The linear regression model indicated that the Flavor and Aroma are the most statistically significant predictors of our target Total_Cup_Points.
- Coffees from Ethiopia and Colombia consistently showed the highest average Total_Cup_Points when summarized by PROC MEANS.
- The chi square test from PROC FREQ indicates that there is a significant association between Washed/Wet processing and high-scoring Arabica species.



