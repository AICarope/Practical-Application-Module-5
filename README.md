# In-Vehicle Coupon Acceptance Study

## Project Overview

This repository contains the analysis of an in-vehicle coupon recommendation system. The dataset was collected from the UCI Machine Learning Repository and a survey conducted via Amazon's Mechanical Turk. The primary goal is to analyze customer behavior regarding coupon acceptance or rejection while driving through a town. The available coupons could be used at restaurants, coffee shops, bars, or carry-out locations, with a value of less than $20 or between $20 and $50, expiring either within 2 hours or in 1 day after receipt.

## Dataset Summary

- **Source**: UCI Machine Learning Repository and Amazon Mechanical Turk
- **Total records**: 12,684 rows (after cleaning: 12,610 rows)
- **Features**: 26 attributes, including both quantitative and qualitative data
- **Duplicate entries**: 74 duplicates were removed

## Problem Statement

This project aims to apply data visualization and statistical analysis to understand customer behavior patterns regarding coupon acceptance while driving. Specifically, analyze both descriptive and inferential statistics to determine factors influencing coupon acceptance across different categories.

## Descriptive Statistics

### Key Findings

- **Total samples**: 12,610 (after removing duplicates)
- **Coupon Acceptance rates**:
  - Accepted: 56.76% (7,157)
  - Rejected: 43.24% (5,453)
  
- **Coupon category acceptance**:
  - Coffee House: 30.59%
  - Restaurant (< $20): 22.02%
  - Carry out & Take away: 18.58%
  - Bar: 15.94%
  - Restaurant ($20-50): 11.80%
<img src="https://github.com/user-attachments/assets/8a2733be-e20e-451c-bfd2-8cdbcc779dd0" alt="AI Product Manager Icon" width="150" height="150" align="left">
<br><br><br>

## Core Responsibilities

- **Temperature conditions**:  
  - 80°F: 6,475 records
  - 55°F: 3,830 records
  - 30°F: 2,305 records

### Bar Coupon Acceptance

- From 2,010 participants who received a bar coupon:
  - 59% (1,186) rejected the coupon
  - 41% (824) accepted the coupon
- Acceptance rate for drivers who go to a bar fewer than three times a month: 37.04%
- Acceptance rate for drivers who go to a bar more than three times a month: 76.88%

### Demographics

- Age group that accepted the most coupons: 21 and 26 years old.
- Occupation:
  - **Top groups accepting coupons**:
    - Unemployed: 934 participants
    - Students: 847 participants
    - Computer and Mathematical professionals: 3rd highest group
- Income levels:  
  - $25,000 - $37,499: 1,051 participants accepted coupons.
  
- Behavioral Insights:  
  - Coupons were more likely to be accepted during "Home Alone" status at 6 PM, followed by "Work-Alone" status at 7 AM.
  
## Inferential Statistics

- **Outliers**:
  - In "toCoupon_GEQ25min", outliers show extreme values in travel times over 25 minutes.
  - Significant outliers in "direction_same" and "direction_opp", indicating irregular travel patterns relative to the coupon location.
  
- **Bar Coupon Acceptance**: There was insufficient data to conclude a difference in acceptance rates based on drivers going to bars more than once a month, and further data collection is recommended for better inference.

## Conclusion

The data analysis indicates that certain demographic factors (age, occupation, income, and travel patterns) strongly influence coupon acceptance. Coupons for coffee houses and restaurants with low price points (< $20) are the most popular, with higher acceptance rates, while more expensive coupons ($20-50) have a lower acceptance rate. The behavior of individuals accepting coupons also varies based on their time of day and social context (e.g., being alone or with friends).

## Next Steps

- **Data Collection**: Additional data needs to be collected, particularly for drivers over 25 who visit bars more than once a month, to further explore acceptance patterns.
- **Further Analysis**: Investigate coupon acceptance patterns during other time periods and expand the analysis to other coupon categories and demographics.
- **Business Recommendations**:
  - Target individuals in specific occupations (e.g., unemployed, students) and those with mid-range income for coupon campaigns.
  - Focus on promoting coupons during specific times of the day (breakfast and dinner) when drivers are most likely to be alone and receptive to offers.
