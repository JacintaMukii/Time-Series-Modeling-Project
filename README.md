# Time-Series-Modeling-Project
# Predicting Real Estate Market Trends with Time Series Analysis

![](https://blogs.sap.com/wp-content/uploads/2019/10/Fig-00-scaled.jpg)

## Introduction
In 2022, the U.S. real estate industry reached a valuation of USD 3.75 trillion and was projected to grow annually by 5.2% from 2022 to 2030, driven by a growing U.S. population, offering substantial investment prospects. Effective risk management and informed investment decisions are essential for success in this dynamic market. 

It was revealed that residential properties yield an average annual return of 10.6%, while commercial properties offer an average return of 9.5%. This project delves into the complexities of the U.S. real estate sector, providing insights, trends, and strategies to empower investors in harnessing the potential of this lucrative market.


This project serves as a consulting opportunity for a  real estate investment firm, emphasizing the application of time series analysis. Their core objective is to leverage Zillow Research data for predicting property price trends in diverse zip codes. By harnessing the power of data-driven insights, the firm seeks to enhance investment decision-making, reduce risks, and gain a competitive advantage in the real estate sector. Time series modeling will be instrumental in guiding them toward profitable, compliant, and strategic investments aligned with their long-term goals.

## Problem Statement

Over the past two decades, real estate investment in the United States has experienced a remarkable journey, marked by significant shifts, triumphs, and challenges. The period spanning from 1996 to 2018 witnessed a rollercoaster ride in the American real estate market, characterized by boom and bust cycles, regulatory reforms, and evolving market dynamics. From the exuberant highs of the early 2000s housing bubble to the depths of the 2008 financial crisis and subsequent recovery, this era is a fascinating case study in the resilience and adaptability of real estate as an investment vehicle. 

To better understand the real estate landscape in the U.S., InnovateIQ Consultants aim to use time series analysis to shed a light on the key factors that influenced investment decisions, and ultimately, the lessons learnt from this dynamic and ever-evolving sector by delving into the transformative events and trends that shaped the U.S. real estate landscape.By harnessing the power of data-driven insights, the firm seeks to enhance investment decision-making, reduce risks, and gain a competitive advantage in the real estate sector

## Main Objective

The primary aim of this project to leverage time series modeling by providing consultancy for a real-estate investment firm with actionable insights and forecasts pertaining to real estate price dynamics in various zip codes. These time-driven analyses will enable the firm to make informed investment decisions, uncover potential opportunities, and proactively address risks within the ever-changing landscape of the real estate market.

## Specific Objectives

- 1. Choose and train appropriate time series forecasting models for real estate  
     price data in zip  codes.

- 2. Evaluate the potential risks associated with investing in various zip codes   
     based    on forecasted real estate price trends, and develop strategies to mitigate these risks.  
  
- 3. Provide tailored investment recommendations for each zip code, including which 
     areas present promising opportunities, which ones require caution, and strategies for optimizing the real estate investment portfolio.  

## Experimental Design

   - Data Collection
   
   - Data Preprocessing
   
   - Exploration Data Analysis 
   
   - Reshape from Wide to Long Format
   
   - Time Series Modelling

   - Forecasting and Model evaluation

   - Conclusion

   - Recommendations 

## Metric 

Mean Absolute Percentage Error(MAPE):
     
   - It quantifies the accuracy of forecasts or predictions by measuring the average   
     percentage difference between the predicted values and the actual values in a dataset. We will use it compare the accuracy of the forecasting models used.
    
## Data Understanding

In this project, we have utilized a dataset sourced from various states within the United States, capturing historical median house prices spanning a 22-year period, ranging from April 1996 to April 2018. This comprehensive dataset was acquired from the Zillow website.

The dataset comprises 14,723 rows and boasts a substantial 272 columns.

Within these 272 columns, four are of a categorical nature, while the remainder are numerical. Here's an overview of the key columns:

  - RegionID: This is a unique identifier for each region.
  - RegionName: Corresponds to the names of regions, typically representing zip codes.
  - City: Provides the city names associated with the respective regions.
  - State: Indicates the states in which these regions are located.
  - Metro: Identifies the metropolitan areas to which these regions belong.
  - County Name: Specifies the names of the counties where these regions are situated.
  - Size Rank: Represents the rank of zip codes based on their level of urbanization.
  - Date Columns (265 Columns): These encompass a vast array of columns that are   
    likely   to contain   median house prices over the 22-year duration, providing a detailed historical perspective.


 ## Conclusions

1. One Step Ahead forecasting model is more accurate than the prophet model because it has a lower MAPE. We are confident in choosing this model.
   
2. In the future, we should analyze various zipcodes to answer investor questions. However, for this particular zipcode, we strongly advise against investing right now.
        
 ## Recommendations
 
1. The real estate company should explore investment prospects in Artheton, California;  
   Palm Beach, Florida; Snowmass Village,Colorado; Portola Valley, California; and Newport Coast, California, as these cities offer some of the highest property values.
   
2. The impact of urbanization on property values appears to be minimal, suggesting that  
   it should not be a significant factor  for consideration. 

3. With the highest ROI, New York City presents a compelling opportunity for real estate 
   investors. Therefore, it is advisable to encourage investors to explore the real estate market in this vibrant city.

4. Among the mentioned zip codes, including 02116 (Boston, Massachusetts), 56041 (New   
   Ulm, Minnesota), 16102 (New Castle, Pennsylvania), 43103 (Columbus, Ohio), and 31027 (Dublin, Georgia), real estate investment may prove less predictable due to 
   the pronounced price volatility. As a result, it is advisable for real estate investors to exercise caution when considering    investments in these regions.   
   
5. Companies should account for market anomalies when making investment predictions, 
   such as the the 2008 financial crisis, as    these can have a significant influence on stock prices. By taking into account factors like the financial crisis, companies    can ensure that their housing price predictions are as accurate as possible.   
 





