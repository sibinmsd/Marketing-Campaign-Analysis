## Marketing Campaign ROI Analysis | GlowUp
**An interactive Power BI dashboard analyzing 40 marketing campaigns across 4 channels to maximize ROI for a beauty & skincare startup.** 

![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=flat&logo=powerbi&logoColor=black)
![DAX](https://img.shields.io/badge/DAX-0078D4?style=flat)
![Status](https://img.shields.io/badge/Status-Completed-success?style=for-the-badge)

**Project Overview**

This project analyzes Marketing Campaign data consisting details of 40 campaigns such as start date, end date, channel, impressions, clicks, amount spend on campaigns for 12 months period.
Power BI is used to create interactive visuals to obtain insights and to recommend strategic actions.

**Problem Statement**

GlowUp, a beauty & skincare startup, wants to identify which campaigns delivered the best return on investment (ROI) and how to allocate marketing budgets efficiently in the future.

**Key Questions:**
- Which channel delivers the highest ROI?
- Which campaigns should be scaled up or discontinued?
- How does performance vary month-over-month?
- What is the optimal customer acquisition cost per channel?

**Dataset**
- **Period:** July 2024 – June 2025 (12 months)
- **Campaigns:** 40
- **Channels:** Email, Event, Influencer, Social Media
- **Metrics:** Impressions, Clicks, Spend, Revenue, Conversions

## Dashboard Preview 

<img width="1305" height="701" alt="image" src="https://github.com/user-attachments/assets/0520d40f-e31b-43ab-8bf9-0f06bac35fae" />

<img width="1298" height="736" alt="Screenshot 2026-08-20 163329" src="https://github.com/user-attachments/assets/3fb4dc7a-bb72-4d80-81e3-423bf38f88bd" />

<img width="1310" height="721" alt="Screenshot 2026-08-20 163419" src="https://github.com/user-attachments/assets/21386f1c-7026-44b3-8317-c1b9b2871e21" />


## Dataset
- 40 campaign records
- Start and End date
- Channel
- Impressions
- Clicks
- Conversions
- Amount spend on campaigns

## Tools Used
- Power Query
- Power BI
- DAX Measures
- Dashboard Design

## KPIs 
- Return on Investment :- The measure of revenue generared in comparison with invested amount
- Cost per Acquisition :- Average amount spend for a conversion [Total Spend/Total Conversions]
- Conversion Rate :- Percentage of clicks resulted in conversion
 
**Analysis used**
1. Return on investment by channel
2. Cost per Acquisition by channel 
3. Conversion Rate by channel
4. ROI - Monthly analysis

**DAX Measures used**
1. Handled missing values using statistical DAX measures and conditional DAX measures. 
2. Calculated Return on investment, Cost Per Acquisition, Conversion Rate. 
3. Used buttons and page navigator to navigate through multiple pages of the dashboard. 


**Key Insights**

1. Email campaigns are the most effective channel with highest ROI and lowest Cost Per Acquisition
2. Offline event campaigns are net-negative (ROI = −29.06%), dragging overall performance
3. Most influencer campaigns perform well with average ROI of 61.36% and Cost Per Acquisition less than overall cost per acquisition
4. Social Media campaigns are underperforming with low ROI (25.66%) and lowest conversion rate
5. Event Campaigns have higher conversion rate due to in person audience whereas Influencer andSocial Media Campaigns affected by passive scrolling behaviour, reducing conversion intent

**Business Recommendations**
1. Get rid of majority of the offline events which are at loss and reallocate their budget for Influencer and Social Media festive season campaigns to increase ROI by 3-5%
2. Blackfriday Email campaign is the best in terms of ROI and Conversion rate. So, launch campaigns on other channels with exiting offers during Black Friday to increase ROI by 2-4%
3. Identify the factors causing higher spend for offline event campaigns (Location, Transportation etc) and take necessary actions to bring it down by 10-20% thereby increasing ROI by up to 5%.
4. Social Media campaigns has lowest conversion rate and average ROI. So redesign the content and visuals of campaigns to increase conversion rate, thereby increase ROI.
5. Consistently identify the trends in social media and collaborate with viral influencer/social media stars to launch campaigns to increase conversion rate by up to 5%
6.  Reduce budget of the underperforming campaigns by 20% and allocate it to well performing campaigns to increase overall ROI by up to 5% 
