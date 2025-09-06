# Social Media Engagement Analysis

## Overview

This project analyzes social media engagement data to uncover trends in likes, shares, and comments across platforms (Facebook, Twitter, Instagram), post types, and posting times. It includes data preprocessing, exploratory data analysis (EDA), and visualization of engagement patterns.

## Dataset

The dataset (social_media_engagement1.csv) contains social media post details, including post time, type, platform, engagement metrics (likes, shares, comments), and sentiment scores.

## Key Steps




**Data Preprocessing**: Converted post_time to datetime, extracted posting hour, and verified no missing values.



**EDA**: Analyzed engagement by platform, post type, hour, day of the week, and sentiment using bar plots, line plots, boxplots, and heatmaps.



## Key Findings:





**Top post types**: Carousel and video for Facebook/Twitter; video and carousel for Instagram.



**Optimal posting days**: Friday (Facebook), Thursday (Twitter), Wednesday (Instagram).


Weak correlation between posting hour and engagement.

## Dependencies





Python 3.x



Pandas, NumPy, Matplotlib, Seaborn, Plotly

## Usage





Clone the repository.



Install dependencies: pip install -r requirements.txt



Place social_media_engagement1.csv in the project directory.



Run the script: python engagement_analysis.py

## Results





Visualizations revealed platform-specific engagement patterns, e.g., Instagram text posts as outliers.



Sentiment analysis showed varying engagement by sentiment score across platforms.



Day-of-week analysis identified peak engagement days for each platform.
