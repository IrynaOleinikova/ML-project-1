ML-project-1
Predicting Engagement of Social Media Posts Using Content Type & Timing Features

Project Overview This project aims to predict engagement levels of social media posts for the company, based on content types and timing features. The ultimate goal is to guide content strategy for higher engagement and better resource allocation across platforms.

Stakeholder Head of Product Marketing – looking for actionable insights to improve social media performance and campaign planning.

Problem Statement Which features of a social media post — including content type, day of the week, and platform — influence engagement the most? Can we build a model to predict future engagement and guide strategy?

Dataset Source: - Internal Sprout Social data export (Jan 1 – Apr 30, 2025)

Platforms: Facebook, TikTok, X
Features: Content Type, Post Text, Platform, Post Time, Day of Week, Engagements, Reach, Video Views, etc.
Target: Engagements Data Cleaning & Feature Engineering

Removed irrelevant or duplicated columns
Encoded categorical variables (Network, Content Type)
Extracted day of week and hour from timestamps
Normalized engagement to control for reach disparities
Exploratory Data Analysis Key visualizations included:

Avarage Engagement by Platform
Avarage Engagement by Content Type and Platform
Avarage Engagement by Weekday
Avarage Engagement by Hour
Modeling Tested models:

Linear Regression
Decision Tree Regressor
Random Forest Regressor (Best performance)
Evaluation Metrics: MAE, RMSE, R² Cross-validation used to ensure generalization

Results & Insights Content Type is the strongest predictor of engagement. Posts on Mondays, Tuesdays and Fridays tend to perform better. X and Facebook platforms show the highest engagement levels.(Tiktok could be at the top as well, but the results likely to be squed because of the different posting cadence on these platforms). 8 PM is the best posting hour for higher engagements.

Business Recommendations Prioritize short-form video content on high-engagement days. Use predictions to guide campaign scheduling and budget planning. Use data-driven content calendars.
