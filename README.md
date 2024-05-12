# AP_Moller_Assessment
Here i have a dataset realted to sourcing of products where i have nearly 5 lakh 50 thousand something rows. I have applied two approaches on this dataset:
##Approach-1
In this method i will not not be removing the duplicate entries rather **i would consider them as an independent datapoint at different time stamps and would remove the outliers from the dataset** further i would be apply various Machine Learning models on that dataset.
##Approach-2
Here i have interpreted the duplicate entries as number of quanties for a particular product as a single row of dataset represent the one unit product so the **duplicate entries represent the multiple units of the particular product hence we got the new column of quantity** and then i have removed the duplicate entries and to get the new cost i have multiplied the Sourcing Cost Column with the Quantity column to get the total Price of Product. Further i have implemented Machine Learning models on this dataset.
