

# 🏡 Airbnb Listings EDA

## Overview

This project performs an exploratory data analysis (EDA) of Airbnb listings data from six global cities:

* **Austin**
* **Bangkok**
* **Buenos Aires**
* **Cape Town**
* **Istanbul**
* **Melbourne**

The dataset was sourced from [Inside Airbnb](https://insideairbnb.com/), a platform that provides publicly available Airbnb data for cities worldwide. After combining the datasets, the total number of listings analyzed amounted to **103,817 records**.

The analysis was conducted using the **R programming language**, employing popular packages such as `tidyverse`, `ggplot2`, `dplyr`, and `lubridate` for data wrangling and visualization.

## 🔍 Key Objectives

* Investigate price distributions across different cities
* Identify high-value listing types and outliers
* Analyze correlations between listing features and popularity
* Examine host trends for high-earning profiles

## 💡 Insights

### 1. 💰 Price Distribution & Currency Adjustment

* Initial price distributions across cities were heavily **right-skewed**, with **Buenos Aires** appearing to have the highest prices.
* Upon adjusting for local currencies (excluding Austin, which was already in USD), **Austin** and **Melbourne** emerged as the cities with the **highest adjusted listing prices**.

### 2. 🏠 Listing Type & Price Impact

* **Entire home/apt** and **Private room** listings command **higher prices per night** across all six cities compared to other listing types.

### 3. 🚨 Price Outliers

* After isolating and analyzing **outlier listings**, the trend persisted: **Austin** and **Melbourne** maintained the **highest-priced listings**, even among the outliers.

### 4. 📏 Minimum Nights vs Price

* There is **no linear correlation** between the minimum number of nights allowed and listing price.
* However, **Entire home/apt** and **Private room** listings not only have higher prices but also tend to require **longer minimum stays**.

### 5. 📉 Popularity vs Minimum Stay

* Listings requiring **a week or more** as the minimum stay receive **fewer reviews**, indicating **lower popularity** compared to listings with **shorter minimum stay requirements**.

### 6. 👩‍💼 High-Earning Hosts

* **Austin** leads with the **highest number of high-earning listings**, followed by **Melbourne** and **Bangkok**.
* These cities show consistent profitability among hosts with multiple high-value listings.

### 7. 🏘 Listing Type among Top Earners

* In cities with the highest earning hosts, **Entire home/apt** is the **most common listing type**.

  * **Austin** has the largest share of such listings, followed by **Bangkok** and then **Melbourne**.


## 🛠 Technologies Used

* **Language:** R
* **Libraries:** `tidyverse`, `ggplot2`, `dplyr`, `lubridate`
* **Source of Data:** [Inside Airbnb](https://insideairbnb.com/)


## 📂 Dataset Summary

* **Cities:** 6
* **Total Listings:** 103,817
* **Source:** Combined `.csv` files from Inside Airbnb for each city


## 📈 Next Steps

* Investigate seasonal price trends and booking rates
* Analyze geospatial patterns within cities
* Build predictive models for price estimation or host revenue forecasting


## 🔗 Acknowledgments

Thanks to [Inside Airbnb](https://insideairbnb.com/) for making this dataset publicly available for open data analysis.



