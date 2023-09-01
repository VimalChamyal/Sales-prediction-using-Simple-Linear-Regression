# Sales prediction using Simple Linear Regression

In this project have used Simple Linear Regression to model the data. 
I have tried to predict 'sales' using the 'amount spent on advertisement using TV as the medium'.

Find the dataset <a href="https://raw.githubusercontent.com/VimalChamyal/Advertisement/main/advertising.csv"> here </a>

## How I made it? 

Step 1: Performed EDA to understand the data. This step helped me eliminate Radio and Newspaper columns as I wasn't able to see any relation of these columns with Sales. I used pandas for checking basic info, then using pairplot (seaborn) checked out pairwise relationships (w.r.t Sales) in the dataset.

Step 2: Performed test train split using sklearn. 

Step 3: Using the statsmodels python package built a SLR model that was at last used to predict 'Sales' using 'T.V' values (Amount spent on advertisement using T.V as the medium) that we got from the test dataset.

Checkout the code <a href="https://github.com/VimalChamyal/Advertisement/blob/main/Predicting_sales_using_SLR.ipynb)https://github.com/VimalChamyal/Advertisement/blob/main/Predicting_sales_using_SLR.ipynb"> here </a>
