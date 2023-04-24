# FInal_project
 A Comparative Study of New and Used Car Prices"
# Final_camp_project
[prezi](https://prezi.com/p/oxl9thc73tuw/?present=1)
[data](https://www.kaggle.com/datasets/muhammedzidan/car-prices-market)


# „A Comparative Study of New and Used Car Prices"
**Nancy Omozokpea**  
**IronHack, Duisburg 21 April 2023**

## Overview

* Finding new ans used cars Price trends and analysing the reasons?  

Used:

	* Python
        *pandas as pd
        *seaborn 
        *matplotlib.pyplot 
        * numpy 
        * EDA
	* Statistical analysis
        * Jupyter NotebookMachine Learning (Logistic Regression)
        * Machine Learning (Logistic Regression)
        * Data visualization
        * Web scrapping/ API


	
  
 ## Data Preparation

 ### Overview: 
 * Data is about new and used cars prices.
	* [dataset](https://www.kaggle.com/datasets/muhammedzidan/car-prices-market)
  
New car prices:
* 11 columns 
* 3433 rows 
* columns: 

web-scraper-order	Car Model	Old Price	Price Change	New Price

Comment:
web-scraper-order was removed because  the columns was not needed



Car Make	Car Model 1	Car Model 2	Year1	Old Price	New Price	Price Increase	Price Decrease	Day	Month	Year

Comment:
Car model1, Car Model2, Day, Month & Year were added to understand the the car prices better and make the filtering easier.

### Data Wrangling and Cleaning
  
- Overall Data description
- Looking for outliers column by column 
- Dealing with Nan Values for each column
- Creating plots for each column to check the correlation to price
- Checking for correlation with target feature



Used car prices:
*14 columns
*79090 rows 

 Initial Column: 

web-scraper-order	Car Model	Month/Year	Average price	Minimum price	Maximum price

 Comment:
web-scraper-order was removed because  the columns was not needed



New Column:
Car Make	Car Model 1	 Car Model 2	Year1	Average price	Minimum price	Maximum price	Month	Year


Comment:
Car model1, Car Model2, Month & Year were added to understand the the car prices better and make the filtering easier.

### Data Wrangling and Cleaning
  
- Overall Data description
- Looking for outliers column by column 
- Dealing with Nan Values for each column
- Creating plots for each column to check the correlation to price
- Checking for correlation with target feature


### Data Storage

* Dump your data as `.csv` file. 

## Data Analysis
* Use EDA tools  to analyze the data


### Data Exploration and Visualization [prezi](https://prezi.com/p/oxl9thc73tuw/?present=1)
Used Prezi to visualize my overall data.

### Model Training and Evaluation
- Define predictors and target values (X, y)
- Standard scaling for numericals : for Train and Test set
- OneHotEncoding for categoricals : for Train and Test set
- Balancing data : Oversampling our target values in our Train set. 
- Models : LogisticRegression, XGBRegressor
- Compared accuracy 


## Conclusion
LogisticRegression:
- mse: 5.590513548086145e+27
- rmse: 74769736846441.72

XGBRegressor:
-MSE:  18881724452.23581
-RMSE:  137410.78724843916

- Due to small available dataset, modeling could not produce reliable prediction.  Analysis would be the best method here. 
