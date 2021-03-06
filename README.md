# Seattle AirBnB Data Analysis

_Project 1 of Udacity Data Scientist Nanodegree_ 

Estimated Revenue metrics [[1](https://towardsdatascience.com/airbnb-in-seattle-data-analysis-8222207579d7)] is introduced and used to answer the following questions:
- What is the Estimated Property revenue in different Seattle neighbourhoods?
- What are the busiest months for renters?

Linear Regression is used to model the rental property price dependency on several objective characteristics:
number of bedrooms and bathrooms, number of beds and how many peoples can be accomodated.
One-hot encoded information about property location is included as explanatory variables. 

### Installation
`$ git clone git@github.com:barkas62/data_scientist_project1.git`

`$ cd data_scientist_project1`

### Required libraries 
- pandas, v0.23.4
- matplotlib, v3.0.0
- seaborn, v0.9.0
- sklearn, v0.20.0

### airbnb_data_analysis.ipnb notebook

Main notebook. Data are loaded, and preprocessed.
New data (Estimated Property Revenue) are derived from *listings* and *reviews* data.
These data are used to get a answers on stated questions and create a predicive model

### Seattle AirBnB data

Can be downloaded from [here](https://www.kaggle.com/airbnb/seattle).
Unzipped data files (*listings.csv and reviews.csv*) must be placed in */data* subfolder.

### Usage
`$ jupyter notebook`

Jupyter environment will be running in browser. Click on `airbnb_data_analysis.ipynb`

### Summary of Resilts

Estimated Revenue metric is really useful for getting some important insight from Seattle AirBnB data:

- Ranked Seattle neighbourhoods for prospective hosts; three central neighbourhoods can provide highest revenue. 
- Distribution of revenue by month showes that late summer and early fall are busiest months; the property maintenance should be better done from late fall to early spring.   

Also we created and trained a simple Linear Regression model which can be used for helping the prospective buyers to estimate the rental price of their property, depending on several property features (number of bedrooms, bathrooms, beds; how many peoples can be accomodated) and on the neighbourhood, where the property is located.
 
 ### Medium Blog post link:
 
 [https://medium.com/@barkas62/using-airbnb-data-to-help-prospective-hosts-b80b0cd74375](https://medium.com/@barkas62/using-airbnb-data-to-help-prospective-hosts-b80b0cd74375)
 
## References:

1: [https://towardsdatascience.com/airbnb-in-seattle-data-analysis-8222207579d7](https://towardsdatascience.com/airbnb-in-seattle-data-analysis-8222207579d7)
