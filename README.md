# Time-series-Analysis

Sales forecasting based on Rossman store sales available on https://www.kaggle.com/c/rossmann-store-sales

The dataset contains sales data for daily sales from 2013 to 2015 for 1115 outlets of Rossman outlets across europe.
Task : To predict future 6 weeks of sales 

**Note:** The store outlets are of 4 types - **A, B, C, D**
An individual models was built for a random subsample of each type.

Random subsampling was done by selecting a subsample of 10% of stores present in the same store type group
(**Student's T test** used to check if sample's behaviour matched with the population)

Scripts

