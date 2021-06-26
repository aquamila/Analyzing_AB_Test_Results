# Analyzing A/B testing results
# Is new advertising page better than old one?

## Overview

The main goal of this project is to analyze whether the company, which has developed a new web page in order to increase the number of users who "convert", should implement this new page or keep the old page. The methods which were used to solve this problem are A/B Test and regression analyses.

I analyzed the dataset and then communicated my findings about it. I shared all the steps in the Jupiter Notebook file [analyze_ab_test_results_.ipynb](https://github.com/aquamila/UDACITY_Analyze_AB_Test_Results/blob/master/analyze_ab_test_results_.ipynb).

## Data

The main dataset is [ab_data.csv](https://github.com/aquamila/UDACITY_Analyze_AB_Test_Results/blob/master/ab_data.csv) which contains information about the two groups of users, the types of page they have visited, and whether the pages have been "converted" or not.

The additional dataset is [countries.csv](https://github.com/aquamila/UDACITY_Analyze_AB_Test_Results/blob/master/countries.csv) which contains information what countries users are from. These data should help to analyze whether the conversion rate were effected by user's country or not.

Data Dictionary:

**user_id**	- user id;   
**timestamp** - exact date and time when a user visited a page;  
**group**	- whether a user from a control or treatment group;  
**landing_page** - what page user got: new or old;  
**converted** - whether there was conversion or not.  

## Technologies Used

- Jupyter Notebook
- Python with the following libraries and modules:
  - NumPy
  - pandas
  - Matplotlib
  - random
  - Statsmodels
