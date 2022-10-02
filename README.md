# BlackFriday Data

## Overview:
We have Zomata Data containing detailed information of partenered restaurants in different countries. The dataframe contains of different variables which we will be working on are mentioned below:
- Restaurant ID	
- Restaurant Name	
- Country Code	
- City	
- Address	
- Locality	
- Cuisines	
- Has Table booking	
- Has Online delivery	
- Is delivering now
- Price range	
- Aggregate rating	
- Rating color	
- Rating text	
- Votes

## Objective:
- Perform Exploratory Data Analysis and Feature Engineering

## Programming Language & Tools:
- Python 
- Jupyter Notebook

## Tasks:
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

