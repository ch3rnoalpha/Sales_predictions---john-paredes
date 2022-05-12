# Sales Prediction Modeling
=======================================================================================================================================================
In this project, I aimed to create two models who attempt to predict a given outlet's sales numbers based on a several store metrics.
Given the
+ Item Weight
+ Item Fat Content
+ Item Visibility
+ Item Type
+ Item Manufacturer Retail Price

for each item in the store and the

+ Outlet Size
+ Year of Establishment 
+ Type


![Outlet sales over time](https://i.gyazo.com/0ebbd04fc45809eb82a3325cb86dd4a0.png)
=======================================================================================================================================================
Visualization - Sales seem to have dipped following 2005, there coould be many factors taht play into it, and spending more time exploring the relation of each condition at the time should give insights as to why this might have happend.
=======================================================================================================================================================
for the store, a linear regression and tree regression models were crafted using Pandas, Numpy, seaborn, and scikit-learn.
These models were tested on a 6000+ item training se and tested on a 2000+ item test set.
Their performance was subsuquently evaluated using R^2 and RMSE metrics. These findings are summarized in the PowerPoint presentation provided.
=======================================================================================================================================================
Visualizations included were
=======================================================================================================================================================
+ Total Store Sales Based on Year Store was Established
   -Historically steady sales, with a recent downturn for newer stores
+ Store Tier’s Compared to Total Store Sales
   -Tier 3 stores have greater potential sales than others, but lower total sales on average.
=======================================================================================================================================================
![Outlet sales over time](https://i.gyazo.com/f89c123277823bc0b82dba8b013f413f.png)
