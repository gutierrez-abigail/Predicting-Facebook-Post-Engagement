# Predicting-Facebook-Post-Engagement
University of San Diego, MSBA - 502 Analytics Programming I: Final Project\

Dataset: https://archive.ics.uci.edu/dataset/368/facebook+metrics

This project analyzes Facebook post performance using statistical modeling and machine learning techniques. The goal is to identify which factors have the greatest impact on user engagement and interactions, allowing businesses to make data-driven decisions when planning social media content.

The analysis uses both Multiple Linear Regression and Logistic Regression models to examine how content characteristics influence post performance.

Business Problem

Organizations invest significant resources into social media marketing but often struggle to determine which content strategies generate the highest engagement.

This project aims to answer the following questions:

What factors most strongly influence Facebook post interactions?
Which post types perform best?
Can future engagement be predicted before publishing a post?
How can marketing teams optimize content to increase audience interaction?

Dataset

The dataset contains Facebook post information including content characteristics and engagement metrics.

Features Used
Post Type
Category
Month Posted
Day Posted
Hour Posted
Paid Advertisement Status
Reach
Impressions
User Engagement Metrics
Target Variables
Linear Regression
Total Interactions
Logistic Regression
High Engagement (Above Median Interactions)
Low Engagement (Below Median Interactions)

Methodology
1. Data Preparation
Removed missing values
Converted categorical variables into dummy variables
Checked variable data types
Split data into training and testing datasets

3. Multiple Linear Regression
A multiple linear regression model was developed to predict the number of interactions a Facebook post receives.

Objectives
Identify significant engagement drivers
Quantify the effect of each predictor
Generate interaction forecasts and prediction intervals

3. Logistic Regression
A logistic regression model was developed to classify posts as either:
High Engagement
Low Engagement

Objectives
Estimate the probability of a successful post
Determine the factors that increase the likelihood of high engagement
Support content strategy decisions

Key Findings
Multiple Linear Regression
Reach was one of the strongest predictors of total interactions.
Impressions showed a positive relationship with engagement.
Certain post types generated significantly different interaction levels compared to the baseline category.
The model explained a substantial portion of variation in post performance.

Logistic Regression
Post reach significantly increased the probability of high engagement.
Higher audience engagement metrics were associated with successful posts.
Content type impacted engagement likelihood.
The model effectively classified posts into high- and low-engagement categories.

Business Recommendations
Increase Reach
Focus on strategies that maximize post visibility, including:
Optimized posting schedules
Targeted audience segmentation
Consistent content publishing
Prioritize High-Performing Content Types

Create more content formats that demonstrate strong engagement performance based on model results.

Use Predictive Analytics

Apply the regression models before publishing content to estimate engagement performance and guide content planning.
Optimize Advertising Spend
Use model predictions to identify posts most likely to generate strong engagement before investing additional advertising resources.

Conclusion

This project demonstrates how statistical modeling and machine learning can be used to understand Facebook engagement behavior. By leveraging both regression and classification techniques, businesses can predict content performance, identify key engagement drivers, and make more informed marketing decisions.
