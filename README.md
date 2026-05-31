# Will The Customer Accept The Coupon?

## Overview

The goal of this project was to analyze customer coupon acceptance behavior using a dataset from the UCI Machine Learning Repository. The analysis explores differences between customers who accepted coupons offered in different driving scenarios and those who did not through data cleaning, visualization, and exploratory analysis using Python, Pandas, Matplotlib, and Seaborn.

## Dataset

The dataset contains information about driving scenarios, including destination, time of day, weather, passengers, income, age, and coupon type. Customers were asked whether they would accept a coupon under various circumstances.

## Key Findings

### Bar Coupon Analysis

- Customers who visited bars more frequently were significantly more likely to accept bar coupons.
- Drivers who visited bars more than once per month had much higher acceptance rates than those who rarely visited bars.
- Previous customer behavior was one of the strongest predictors of coupon acceptance.

### Independent Investigation: Restaurant (<20) Coupons

- Customers who frequently visited inexpensive restaurants accepted Restaurant(<20) coupons more often than those who rarely visited these restaurants.
- Customers who never visited inexpensive restaurants accepted the coupon only about 55.6% of the time, while those visiting more than 8 times per month accepted at a rate of approximately 76.0%.
- Age showed only a weak relationship with coupon acceptance.
- Income appeared to have some influence, but there was no strong linear relationship.
- Customers who frequently visited inexpensive restaurants and were traveling with friends had the highest acceptance rate at 81.8%.
- Customers who frequently visited inexpensive restaurants and received the coupon during common meal times also showed elevated acceptance rates.

## Conclusions

The strongest predictor of coupon acceptance was whether customers already participated in the activity associated with the coupon. For Restaurant(<20) coupons, customers who frequently visited inexpensive restaurants and were traveling with friends were the most likely to accept the offer. Social situations and dining habits appear to influence coupon acceptance more than demographic factors such as age or income.

## Recommendations

- Target Restaurant(<20) coupons toward customers who regularly dine at inexpensive restaurants.
- Focus promotions on customers traveling with friends or in social settings.
- Distribute restaurant coupons during common meal times to improve acceptance rates.
- Use past customer behavior as a primary factor when designing targeted marketing campaigns.

## Files Included

- `Will_the_Customer_Accept_the_Coupon- Anushiya Shiley.ipynb`
- `coupons.csv`
