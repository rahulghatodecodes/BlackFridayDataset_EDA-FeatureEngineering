# BlackFriday Data

## Overview:
We have Black Friday Customer Data containing detailed information of purchase summary of various customers for selected high volume products. The dataset also contains customer demographics are other variables mentioned below:
- User_ID	
- Product_ID	
- Gender	
- Age	
- Occupation	
- City_Category	
- Stay_In_Current_City_Years	
- Marital_Status	
- Product_Category_1	
- Product_Category_2	
- Product_Category_3
- Purchase



## Objective:
- Perform Exploratory Data Analysis and Feature Engineering

## Programming Language & Tools:
- Python 
- Jupyter Notebook

## Tasks:

Append test data:, The basic measures of descriptive statistics:, Dropping "User_ID" column:, Handling categorical feature 'Gender':, Handling Categorical feature age:, Second technique through LABEL ENCODING:, Fixing categorical variable city_category:, Combining the df_city and df:, Dropping city_category feature:, Checking the missing values:, Replacing missing values:, Replacing the missing values with mode, Converting object into integers in Stay_In_Current_City_Years:, Visualiaztion diagram of AGE vs PURCHASE: , Observation: 1.Purchasing of men is high then women. Visualization of purchase with occupation:, Finding the unique values present in occupation: Bar plot for product_category1, product_category2 and product_category3 vs purchase, Observation: Product_Category_1 is bought the most.




- Checked the basic measures of descriptive statistics.
- Checked missing values, missing values using.
- Combined two dataframes w.r.t country code.
- Checked Data Types of the variables.
- Created a dataframe having features 'Aggregate rating', 'Rating color', 'Rating text' and 'Rating count'.
- Implemented sorting on the dataframe by "Aggregate rating".
- Extracted the unique values of Country column.

## Findings:
- The name of different countries and number of records of those specific countries.
- The countries that has given 0 ratings.
- The currency used by each country.
- The countries that have online delivery option.
- The top 10 cuisines.

## Visualizations:
- Pie chart of top 3 countries using Zomato.
- Bar plot showing relation between rating text and rating count.
- Bar plot showing relation between aggregate rating and rating count.
- Modifying the bar plot, color the aggregate rating as color that is given (using hue= rating color).
- Making count plot w.r.t rating color.
- Pie chart for top 5 cities distribution.

## Observations:
- 94.39% of zomato partnered restaurants are in India, 4.73% in US and 0.87% in UK. 
- Not Rated count is very high. Maximum number of ratings are between 2.5 and 3.4
- Around 2148 records have 0 ratings.
- Maximum number of zero ratings are from Indian customers.
- Online deliveries are available in India and UAE In India and UAE, some areas online delivery is not there.
- North Indian Cuisines has most number of records followed by Chinese Cuisines.
- When rating is between 4.5 to 4.9 ---> Excellent.
- When rating is between 4.0 to 4.4 ---> Very Good.
- When rating is between 3.5 to 3.9 ---> Good.
- When rating is between 3.0 to 3.4 ---> Average.
- When rating is between 2.5 to 2.9 ---> Average.
- When rating is between 1.8 to 2.4 ---> Poor.

