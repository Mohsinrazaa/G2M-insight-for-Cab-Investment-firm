# G2M-insight-for-Cab-Investment-firm

In the G2M insight for Cab Investment firm ( Must for all Specialization) project, we will show which company (`Yellow Cab` or `Pink Cab`) is the better opportunity to invest in it.

Here is some points before checking the results out:

We use 5 datasets, **US Bank holidays.csv** is added dataset which describes US holidays

`Cab_Data.csv` 

`City.csv` 

`Customer_ID.csv` 

`Transaction_ID.csv` 

`US Bank holidays.csv`

Profit is defined by me: Profit = Price Charged - Cost of Trip

"df_total" is a dataframe is created by merging mentioned 5 dataframes : The days which is not a holiday, has "-" value in "Holiday" column After Merging if any record has at least 1 NaN value, the whole record is dropped. it means we do not have enough information of that trip

Pickle is used for efficient working with jupyter, the parts related to "pkl" are commented

Hypothesis and Conclusions are provided in the EDA notebook

The profiling method helps me find informative data that guide me to take an analysis on the specific area and plot them, so profiling results are not discussed in detail but the files are attached, you can check it
