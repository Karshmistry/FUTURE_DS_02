# FUTURE_DS_02
Social Media Campaign Performance Tracker | Power BI dashboard analyzing reach, engagement, CTR, conversions &amp; ROI — created as part of Data Analytics Internship at Future Interns.

# 📊 FUTURE_DS_02 – Social Media Campaign Performance Tracker (2022–2024)

##  Overview
This repository contains **Task 2** of my **Data Science & Analytics Internship** at **Future Interns**.  
The goal of this project was to analyze and visualize **social media campaign data** across multiple platforms (Facebook, Instagram, LinkedIn, Twitter, and YouTube) to measure performance, engagement, and ROI.

##  Objectives
- Evaluate key campaign metrics such as reach, impressions, clicks, and conversions  
- Compare platform-wise engagement and ROI performance  
- Identify the most effective campaigns based on conversion and ad spend  
- Build an interactive Power BI dashboard for data-driven insights  

##  Tools & Technologies
- **Power BI** – Data visualization & analytics  
- **Excel / CSV** – Data preparation and cleaning  
- **DAX (Data Analysis Expressions)** – Custom metrics and KPIs  
- **Canva** *(optional)* – Visual enhancement  

##  Key Insights
- Total Reach: 250M+ across all platforms  
- Instagram delivered the highest engagement rate (~8%)  
- Facebook achieved the best ROI (1.5x returns)  
- LinkedIn showed lower reach but higher conversion efficiency  
- Seasonal peaks during Diwali & New Year campaigns  

##  Key DAX Measures
```DAX
Total Revenue = SUM('SocialMedia_Campaign_Data'[Revenue])
Total Ad Spend = SUM('SocialMedia_Campaign_Data'[Ad_Spend])
Overall ROI % = DIVIDE([Total Revenue] - [Total Ad Spend], [Total Ad Spend], 0)
CTR % = DIVIDE([Total Clicks], [Total Impressions], 0)
Conversion Rate % = DIVIDE([Total Conversions], [Total Clicks], 0)
