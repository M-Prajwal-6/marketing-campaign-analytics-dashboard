📊 Marketing Campaign Analytics Dashboard
🚀 Overview

This project presents an end-to-end data analysis of marketing campaign performance using Python and Power BI. The goal is to analyze user engagement, identify optimal campaign strategies, and generate actionable business insights.

The analysis focuses on:

🌍 User behavior across different time zones
⏰ Best sending times for campaigns
🤖 Performance comparison (AI vs Manual campaigns)
👥 User segmentation (personas)
📈 Engagement and conversion insights
🎯 Objectives
  Analyze campaign performance metrics (open rate, click rate, conversion rate)
  Identify optimal sending times for maximum engagement
  Understand user behavior across time zones
  Segment users into meaningful personas
  Provide data-driven recommendations to improve campaign performance
  
📂 Dataset
  The dataset contains ~50,000 records with the following features:
  User Information: user_id, age, gender, country, timezone
  Campaign Details: campaign_id, campaign_type (AI / Manual)
  Time Features: send_time, send_hour
  Performance Metrics: open_rate, click_rate, conversion_rate
  Other: device, delivery_status
  
🧰 Tools & Technologies
  🐍 Python
    pandas
    numpy
    seaborn
    matplotlib
  📊 Power BI (Dashboard Visualization)
  
🔍 Key Analysis Performed
🌍 Time Zone Analysis
  Compared user engagement across different regions
  Identified peak engagement hours per timezone
⏰ Best Sending Time
  Found optimal time windows:
  Morning (9–11 AM)
  Evening (6–9 PM)
🤖 AI vs Manual Campaign Analysis
  Compared performance metrics across campaign types
  Evaluated impact of personalization
👥 User Segmentation
  Applied clustering to identify:
  High engagement users
  Medium engagement users
  Low engagement users
📉 Engagement Funnel Analysis
  Observed drop from:
  Open → Click → Conversion
  Identified optimization opportunities
  
📊 Dashboard (Power BI)
  The Power BI dashboard includes:
  
  📈 Open rate trends by hour
  🌍 Time zone-based engagement
  🤖 AI vs Manual campaign comparison
  📱 Device-based performance
  🥧 Delivery status distribution
  
🧠 Key Insights
  📌 Engagement varies significantly across time zones
  ⏰ Peak engagement occurs during morning and evening hours
  🤖 AI campaigns outperform manual campaigns in all metrics
  👥 User base can be segmented into distinct personas
  📉 Conversion funnel shows drop-offs requiring optimization
  
📌 Recommendations
  🎯 Schedule campaigns based on user timezone
  🤖 Use AI-driven campaigns for better personalization
  👥 Target high-value users with customized content
  ⏰ Avoid sending emails during low engagement hours
  📈 Improve email content and CTA to increase conversions
  
📁 Project Structure
  📦 marketing-campaign-analytics-dashboard
   ┣ 📂 data
   ┃ ┗ marketing_campaign_dataset_50k.csv
   ┣ 📂 notebooks / scripts
   ┃ ┗ analysis.ipynb
   ┣ 📂 dashboard
   ┃ ┗ powerbi_dashboard.pbix
   ┣ 📂 images
   ┃ ┗ dashboard_screenshot.png
   ┗ README.md
   
📸 Screenshots
<img width="1345" height="742" alt="image" src="https://github.com/user-attachments/assets/f96bcc20-cf83-43ce-a760-5464079f54cb" />

🏁 Conclusion
  This project demonstrates how data-driven decision making can significantly improve marketing campaign performance. By combining:
  
  Time-based targeting
  AI-driven personalization
  User segmentation

organizations can enhance engagement, increase conversions, and maximize ROI.
