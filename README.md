# Marketing Campaign Performance Analysis
 
 # Project Overview

This project focuses on analyzing marketing campaign performance using a large-scale dataset of 200,000 campaigns. The goal is to extract actionable insights that help businesses understand how different marketing channels, campaign types, customer segments, and target audiences impact ROI, conversion rates, engagement, and efficiency.

The analysis is performed using Python, Pandas, Matplotlib, and Seaborn, with extensive exploratory data analysis (EDA) and feature engineering.


# Dataset Description

The dataset contains 200,000 rows and 16 columns, representing individual marketing campaigns.

Key Columns:

Campaign_ID – Unique campaign identifier

Company – Company running the campaign

Campaign_Type – Email, Social Media, Influencer, Display, etc.

Target_Audience – Demographic group targeted

Duration – Campaign duration

Channel_Used – Platform used (Google Ads, Facebook, YouTube, etc.)

Conversion_Rate – Percentage of users converted

Acquisition_Cost – Cost spent on the campaign

ROI – Return on Investment

Clicks / Impressions – Engagement metrics

Engagement_Score – User engagement score (1–10)

Customer_Segment – Market segment category

Date – Campaign start date

# Data Cleaning & Preprocessing
Checked and removed duplicate records

Converted date column to datetime format

Extracted Month from the date for trend analysis

Handled missing values

Identified and fixed data type issues

# Feature Engineering

New metrics were created to enhance analysis:

CTR (Click Through Rate)
CTR = Clicks / Impressions

ROI per Cost Unit
ROI_per_Cost = ROI / Acquisition_Cost

Cost per Conversion
Cost_per_Conversion = Acquisition_Cost / Conversion_Rate

ROI per Engagement Score

ROI per CTR

High Conversion Flag (above median conversion rate)

# Exploratory Data Analysis (EDA)

# Overall Campaign Performance

Average Conversion Rate

Mean ROI

Average CTR

Engagement Score distribution

# Channel Performance Analysis

ROI comparison across channels

Channel usage distribution (pie chart)

Identification of high-performing platforms

#  Campaign Type Analysis

ROI distribution by campaign type (boxplot)

#  Marketing Funnel Analysis

Impression → Click → Conversion

Funnel visualization

Clicks vs Impressions scatter plot

#  Customer Segment Analysis

Performance comparison across customer segments

Conversion rate, ROI, and engagement trends

# Target Audience & Localization

ROI by target audience

Conversion rate by language

ROI by geographic location

#  Engagement Threshold Discovery

Comparison of engagement scores for high vs low conversion campaigns

# Visualizations Included

Pie charts

Boxplots

Scatter plots

Bar charts

Histograms

All visualizations are designed to clearly communicate insights and trends.

# Technologies Used

Python 3

Pandas – Data manipulation

NumPy – Numerical operations

Matplotlib & Seaborn – Data visualization

Jupyter Notebook – Interactive analysis

# Key Insights

All marketing channels show similar ROI, but engagement and CTR vary

Certain customer segments and age groups consistently outperform others

High impressions do not always guarantee high conversions

Engagement score alone does not strongly differentiate high-conversion campaigns





