# Home_Sales
module 22 challenge

## Welcome
In this repository, we can find code to explore some data about home sales for the purpose of comparing performance with caches and parquet file formatting
### Contents
- The "Home_sales.ipynb" is the main file we are using for the purpose of this excercise.
- Next you will see a folder labeled "home_sales_partitioned" This folder contains the partitioned data as shown in the home sales notebook (ln 18)
### Results
With no Caching, my personal computer was able to run the query in about .14 seconds.
</br>
After Caching, the same computer could run the query in .10 seconds. 
</br>
After converting the data into parquet file format we saw the fastest response with .06 seconds.
