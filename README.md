# Taxing-Iowa-Liquor-Sales

![liquor-2687103_1280](https://user-images.githubusercontent.com/35437820/38502789-5ac5b04e-3bde-11e8-959e-8edd9e592683.jpg)

# Overview
The state of Iowa provides many datasets on their website, including this which contains transactions for all stores that have a class E liquor license.

NOTE: The dataset may be too big for you to analyze. In this case, feel free to use this 10% dataset version of Iowa liquor sales. You may want to use it anyway to test your code since it will be faster.

Please save these .csv files on your local computer. Do NOT put them in your GitHub repo. The size of the files can cause github to crash if you attempt to push them to the remote repo.

# Scenario
The Iowa State legislature is considering changes in the liquor tax rates and wants a report of current liquor sales by county and projections for the rest of the year to inform their decision.

# Goal for Scenario:

Calculate the yearly liquor sales for each store using the provided data. You can add up the transactions for each year, and store sales in 2015 specifically will be used later as your target variable.
Use the data from 2015 to make a linear model using as many variables as you find useful to predict the yearly sales of all stores. You must use the sales from January to March as one of your variables.
Use your model for 2015 to estimate total sales in 2016, extrapolating from the sales so far for January to March of 2016.
Report your findings, including any projected increase or decrease in total sales (over the entire state) for the tax committee of the Iowa legislature.
Use cross-validation to check how your model predicts to held out data compared to the model metrics on the full dataset.
Fit your model(s) using one or both of the regularization tactics covered. Explain whether the regularized or the non-regularized model performed better and what the selected regression(s) are doing.
